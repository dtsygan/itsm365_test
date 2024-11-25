<h1 MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Наполнение оргструктуры</h1><h2 MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Наполнение оргструктуры</h2>
Информацию об отделах и сотрудниках компании можно ввести в систему несколькими способами: импорт из  Active Directory или наполнить оргструктуру вручную.

<ul class="TOC" MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
  <li>
    <MadCap:xref href="#01">Импорт из  Active Directory</MadCap:xref>
  </li>
  <li>
    <MadCap:xref href="#02">Наполнение оргструктуры вручную</MadCap:xref>
  </li>
  <li>
    <MadCap:xref href="#05">Добавление сотрудников в команды</MadCap:xref>
  </li>
</ul>### Импорт из Active Directory

<p>Импорт из Active Directory — это автоматическое создание отделов и сотрудников в <MadCap:variable name="Base.ProductName" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd" /> на основании данных, зарегистрированных во внешнем каталоге LDAP (например, Microsoft Active Directory).</p>

<p class="beforeList">Если в Вашей компании используется каталог LDAP, то Вы можете отправить на наш электронный адрес <a href="mailto:cs@ITSM 365.com" target="_blank">cs@ITSM 365.com</a> параметры подключения к каталогу:</p>

<ul class="FirstLevel">
  <li>строка подключения к ldap: пример, ldap://dc:389;</li>
  <li>имя и пароль пользователя, который обладает правами на чтение;</li>
  <li>корень домена, из которого необходимо импортировать сотрудников: пример, OU=Типовая компания,DC=dc2, DC=local.</li>
</ul>
В процессе импорта из Active Directory в системе автоматически создаются объекты (отделы) со следующими значениями полей.

<table style="mc-table-style: url('../Resources/TableStyles/PatternedRows.css');width: 100%;margin-left: 0;margin-right: auto;" class="TableStyle-PatternedRows" cellspacing="0">
  <col style="width: 50%;" class="TableStyle-PatternedRows-Column-Column" />
  <col style="width: 50%;" class="TableStyle-PatternedRows-Column-Column" />
  <thead>
    <tr class="TableStyle-PatternedRows-Head-Header">
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">Атрибуты отдела в ITSM 365</th>
      <th class="TableStyle-PatternedRows-HeadD-Column-Header">Коды атрибутов в  AD</th>
    </tr>
  </thead>
  <tbody>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Название</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">name </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyB-Column-Body">Вышестоящий отдел</td>
      <td class="TableStyle-PatternedRows-BodyA-Column-Body">parent</td>
    </tr>
  </tbody>
</table>
В процессе импорта из Active Directory в системе автоматически создаются объекты (сотрудники) со следующими значениями полей.

<table style="mc-table-style: url('../Resources/TableStyles/PatternedRows.css');margin-left: 0;margin-right: auto;caption-side: top;mc-caption-repeat: true;width: 100%;" class="TableStyle-PatternedRows" cellspacing="0">
  <col style="width: 50%;" class="TableStyle-PatternedRows-Column-Column" />
  <col style="width: 50%;" class="TableStyle-PatternedRows-Column-Column" />
  <thead>
    <tr class="TableStyle-PatternedRows-Head-Header">
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">Атрибуты сотрудника в ITSM 365</th>
      <th class="TableStyle-PatternedRows-HeadD-Column-Header">Коды атрибутов в  AD</th>
    </tr>
  </thead>
  <tbody>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">ФИО</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">displayName</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Отдел</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">parent</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Должность</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">title</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Логин</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">sAMAccountName</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Адрес электронной почты	</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">mail</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Мобильный телефон</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">mobile</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Городской телефон</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">telephoneNumber</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Внутренний телефон</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">ipPhone</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyB-Column-Body">Домашний телефон</td>
      <td class="TableStyle-PatternedRows-BodyA-Column-Body">homePhone</td>
    </tr>
  </tbody>
</table>### Наполнение оргструктуры вручную

Чтобы наполнить оргструктуру вручную, в разделе "Оргструктура" необходимо создать отделы и в карточке отдела добавить вложенные отделы и сотрудников. По умолчанию в системе создан отдел с названием "ИТ-отдел", в который добавлен сотрудник "Администратор".

Наполнение оргструктуры выполняется пользователем с правами администратора (логин и пароль администратора были высланы Вам на электронную почту).

<p MadCap:conditions="Default.itsm,Default.itsm_OS" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Подробное описание формирования оргструктуры см. в разделе <MadCap:xref href="../org/orgstructura.htm">Оргструктура</MadCap:xref>.</p>

Краткое описание данных операций смотрите в разделах ниже.

<p class="hH4">Добавление отдела</p>

Чтобы создать отдел верхнего уровня, в списке отделов нажмите кнопку "+ Добавить отдел".

<p class="ris">
  <img src="../Resources/Images/itsm_SN/ou_add_1.png" title="Отделы - Добавить отдел" class="doc" />
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Отделы - Добавить отдел</p>

Чтобы создать вложенный отдел, в карточке отдела в блоке "Вложенные отделы и пользователи" нажмите кнопку "+ Добавить отдел".

<p class="ris">
  <img src="../Resources/Images/itsm_SN/ou_add_2.png" title="Карточка отдела - Добавить отдел" class="doc"></img>
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Карточка отдела - Добавить отдел</p>

На форме добавления отдела введите название отдела и нажмите кнопку "Сохранить".

<p class="hH4">Добавление сотрудника</p>

Чтобы добавить нового пользователя в карточке отдела, в блоке "Вложенные отделы и пользователи" нажмите кнопку "+ Добавить пользователя".

<p class="ris">
  <img src="../Resources/Images/itsm_SN/ou_add_2.png" title="Карточка отдела- Добавить пользователя&amp;quot;" class="doc"></img>
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Карточка отдела- Добавить пользователя"</p>

На форме добавления пользователя заполните поля и нажмите кнопку "Сохранить".

<p class="beforeList">Поля формы добавления пользователя:</p>

<ul class="FirstLevel">
  <li>
    <b>Фамилия</b> — фамилия пользователя;</li>
  <li>
    <b>Имя</b> — имя пользователя;</li>
  <li>
    <b>Отчество</b> — отчество пользователя;</li>
  <li>
    <b>Должность</b> — должность пользователя в компании;</li>
  <li>
    <p>
      <b>Email</b> — адрес электронной почты. </p>
    <p>На указанный email пользователю будут приходить оповещения о тех или иных активностях (создании заявки, комментария к заявке и т.д.)</p>
  </li>
  <li>
    <b>Логин</b> — логин пользователя для входа в систему.</li>
  <li>
    <b>Сгенерировать пароль и отправить пользователю на почту</b> — возможность сгенерировать пароль, удовлетворяющий всем установленным в системе требованиям безопасности паролей, и отправить его пользователю на указанный адрес электронной почты.</li>
  <li>
    <p class="beforeList">
      <b>Лицензия</b> — регламентирует доступ пользователя в систему:</p>
  </li>
  <ul class="FirstLevel">
    <li>Именная — пользователь с такой лицензией всегда может зайти в систему;</li>
    <li>
      <p>Конкурентная — пользователь может зайти в систему, если есть свободные лицензии этого типа.</p>
      <p>Например, всего есть 2 конкурентных лицензии, они назначены на трех пользователей. Если первые два пользователя работают в системе, то третий не сможет войти, пока кто-нибудь не выйдет.</p>
      <p>Подходит для пользователей со сменным графиком работы.</p>
    </li>
    <li>Контактное лицо (нелицензированный) — пользователь всегда может зайти в систему, но только как получатель услуг: для создания заявки или ответа по своим открытым заявкам.</li>
  </ul>
</ul>### Добавление сотрудников в команды

Данный шаг выполняется независимо от способа наполнения оргструктуры.

После того как все сотрудники добавлены в ITSM 365, необходимо сформировать команды,которые будут отвечать за поддержку ваших клиентов

<p class="Termin">Команда — функциональная единица, которая никак не связана с оргструктурой. Участником команды может стать сотрудник любого отдела, при этом их количество не ограничено. <br />Ответственным за заявку можно назначить либо сотрудника в рамках определенной команды, либо команду в целом.</p>

Список команд отображается на странице "Команды". По умолчанию в системе создана команда "Специалисты 1-ой линии", в ответственность которой будут попадать все новые заявки. При необходимости команду можно переименовать и добавить в систему новые команды.

Добавить сотрудника в команду можно двумя способами.

<p class="hH4">В карточке команды</p>

Чтобы добавить пользователя в команду, в карточке команды перейдите на вкладку "Информация" и нажмите кнопку "Добавить участника" в блоке "Участники команды". На форме "Добавить участника" выберите пользователей и нажмите кнопку "Сохранить"

<p class="ris">
  <img src="../Resources/Images/itsm_SN/t_4.png" title="Карточка команды. Кнопка &amp;quot;Добавить пользователя в команду&amp;quot;" class="doc" />
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Карточка команды. Кнопка "Добавить пользователя в команду"</p>

<p class="hH4">В карточке пользователя</p>

Чтобы добавить пользователя в команду, в карточке пользователя нажмите кнопку "Связать с командой" в блоке "Команды". На форме "Связать с командами" выберите команды и нажмите кнопку "Сохранить".

<p class="ris">
  <img src="../Resources/Images/itsm_SN/emp_2_4.png" title="Карточка пользователя. Блок &amp;quot;Команды&amp;quot;" class="doc"></img>
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">  Карточка пользователя. Блок "Команды"</p>

<p MadCap:conditions="Default.WEB-HELP" class="note_stroca" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd"> </p>

<ul class="webHelp">
  <li MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Быстрый старт. Шаг 2. <MadCap:xref href="Quick_Start_2.htm">Настройка правил для расчета времени на решение заявок</MadCap:xref></li>
</ul>
