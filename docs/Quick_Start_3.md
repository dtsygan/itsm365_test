<h1 MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Настройка оповещений по email и уведомлений в интерфейсе</h1><h2 MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Настройка оповещений по email и уведомлений в интерфейсе</h2><p MadCap:conditions="" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Для эффективной работы сервисного подразделения и своевременного информирования сотрудников о выполнении каких-либо действий в системе используются оповещения по электронной почте и пуш-уведомления в интерфейсе</p>

<ul MadCap:conditions="Default.WEB-HELP" class="TOC" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
  <li>
    <MadCap:xref href="#01">Группы оповещений по email и пуш-уведомлений в интерфейсе</MadCap:xref>
  </li>
  <li>
    <MadCap:xref href="#02">Настройка исходящей почты</MadCap:xref>
  </li>
</ul><h3 MadCap:conditions="" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
  <a name="01"></a>Группы оповещений по email и пуш-уведомлений в интерфейсе</h3><p MadCap:conditions="" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">В <MadCap:variable name="Base.ProductName" /> существует две группы оповещений и пуш-уведомлений в интерфейсе:</p>

<ul class="FirstLevel">
  <li MadCap:conditions="" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
    <p>Оповещения и пуш-уведомления о событиях с объектами системы: добавление объекта, смена статуса и прочее. </p>
    <p>
      <MadCap:variable name="Base.ProductName" /> предлагает определенный набор оповещений и пуш-уведомлений. По умолчанию все оповещения и пуш-уведомления включены. Вы можете отключить неиспользуемые в вашей компании оповещения и пуш-уведомления в интерфейсе технолога. </p>
    <p MadCap:conditions="Default.WEB-HELP" class="br">Подробное описание отключения оповещений и пуш-уведомлений, см. <MadCap:xref href="../technolog/action_ITSM.htm">Действия по событиям</MadCap:xref>.</p>
    <p class="ris">
      <img src="../Resources/Images/core_tech/dps.png" title="Действия по событиям" class="doc" />
    </p>
    <p class="img_num" MadCap:conditions="Default.PDF">Страница действия по событиям</p>
  </li>
  <li MadCap:conditions="" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
    <p>Оповещения о наступлении дедлайна заявки, задачи или согласования.</p>
    <p>
      <MadCap:variable name="Base.ProductName" /> предлагает определенный набор оповещений о наступлении дедлайна. По умолчанию все оповещения включены. Вы можете отключить неиспользуемые в вашей компании оповещения в интерфейсе технолога.</p>
    <p MadCap:conditions="Default.WEB-HELP">Подробное описание отключения оповещений, см. <MadCap:xref href="../technolog/eskalacig_ITSM.htm">Эскалация</MadCap:xref>.</p>
    <p class="ris">
      <img src="../Resources/Images/core_tech/eck.png" title="Эскалация" class="doc" />
    </p>
    <p class="img_num" MadCap:conditions="Default.PDF">Интерфейс настройки. Раздел "Эскалация"</p>
  </li>
</ul><p>Подпись к оповещениям и возможность отправки оповещений незарегистрированным пользователям настраиваются в карточке компании на вкладке "Настройки", см. <MadCap:xref href="../setting/settings_mail.htm#01" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Основные настройки почты</MadCap:xref>.</p>

<h3 MadCap:conditions="" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
  <a name="02"></a>Настройка исходящей почты</h3><p class="note">Для использования оповещений в настройках системы заполните параметры сервера исходящей почты и параметры отправки писем. </p>

<p MadCap:conditions="" class="hH4" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Подключение к серверу исходящей почты</p>

Чтобы заполнить параметры исходящей почты, перейдите в интерфейс технолога (иконка ![](../Resources/Images/icon_svg/int_adm.svg) в правом верхнем углу экрана), в раздел "Настройка системы" → "Почта" → "Параметры подключения" (вкладка "Исходящая почта") укажите параметры подключения к серверу исходящей почты.

Подключение к серверу исходящей почты возможно по протоколам SMTP и EWS.

<table style="width: 100%;margin-left: 0;margin-right: auto;mc-table-style: url('../Resources/TableStyles/PatternedRows.css');" class="TableStyle-PatternedRows" cellspacing="0">
  <col class="TableStyle-PatternedRows-Column-Column" />
  <col class="TableStyle-PatternedRows-Column-Column" />
  <col class="TableStyle-PatternedRows-Column-Column" />
  <thead>
    <tr class="TableStyle-PatternedRows-Head-Header">
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">Параметры/Протокол</th>
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">SMTP</th>
      <th class="TableStyle-PatternedRows-HeadD-Column-Header">EWS</th>
    </tr>
  </thead>
  <tbody>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Сервер</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">IP адрес или DNS имя сервера исходящей почты</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">IP адрес или DNS имя сервера исходящей почты</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Протокол</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">SMTP</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">EWS</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Порт</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Порт, соответствующий типу соединения (цифрами)</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">—</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Протокол шифрования</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Возможные значения: "SSL", "TLS" или "Без шифрования"</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">—</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Аутентификация SMTP</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">При необходимости аутентификации на SMTP сервере установите флажок (данное требование определяется настройками SMTP сервера).</p>
        <p class="td">По умолчанию аутентификация SMTP не включена</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">—</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p>Аутентификация OAuth2</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p>—</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">При необходимости использования для авторизации протокола OAuth2 установите флажок. </p>
        <p class="td">Данный тип аутентификации позволяет подключаться без использования пароля на прямую. Для подключения используются токены доступа полученные из AzureAD.</p>
        <p class="td">Если флажок включен, то на форме отображаются дополнительные параметры:</p>
        <ul class="tab">
          <li>Идентификатор приложения</li>
          <li>Идентификатор каталога</li>
          <li>Секрет клиента</li>
        </ul>
        <p class="td">Значения параметров заполняются данными, полученными при регистрации приложения в Azure AD</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Логин</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Имя пользователя для отправки сообщений</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">Имя пользователя для отправки сообщений</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyB-Column-Body">
        <p class="td">Пароль</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyB-Column-Body">
        <p class="td">Пароль для отправки сообщений через SMTP-сервер</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyA-Column-Body">
        <p class="td">Пароль для отправки сообщений.</p>
        <p class="td">При включенном флажке "Аутентификация OAuth2" поле скрывается</p>
      </td>
    </tr>
  </tbody>
</table><p class="comment">Параметры "Логин" и "Пароль" имеют значение лишь при включенном параметре "Аутентификация SMTP".</p>

<p class="hH4">Настройка параметров отправки писем</p>

Текущие параметры отправки писем отображаются в карточке подключения.

<p class="ris">
  <img src="../Resources/Images/itsm/L-06.png" title="Вкладка &amp;quot;Исходящая почта&amp;quot;" MadCap:conditions="Default.itsm" class="doc" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd" />
  <img src="../Resources/Images/itsm_os/L-06.png" title="Вкладка &amp;quot;Исходящая почта&amp;quot;" MadCap:conditions="Default.itsm_OS" class="doc" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd" />
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Карточка подключения к серверу исходящей почты</p>

Чтобы изменить параметры отправки писем, нажмите кнопку "Редактировать" в блоке "Отправка писем". На форме редактирования заполните параметры отправки писем и нажмите кнопку "Сохранить".

<p class="beforeList">Параметры отправки писем:</p>

<ul class="FirstLevel">
  <li>E-mail адрес службы техподдержки — адрес электронной почты, который будет отображаться в поле "Обратный адрес (Reply-to)" письма, отправляемого системой.</li>
  <li>E-mail адрес системы — адрес электронной почты, который будет отображаться в поле "От кого (From)" письма, отправляемого системой.</li>
  <li>Имя отправителя писем из системы — имя, которое будет отображаться в поле "От кого (From)" вместе с "E-mail адресом системы".</li>
</ul><p class="note">Параметры "E-mail адрес службы техподдержки", "E-mail адрес системы" и "Имя отправителя писем из системы" являются обязательными для заполнения, иначе отправка писем не будет работать.</p>

<p>Подробное описание настройки параметров сервера исходящей почты и параметров отправки писем <MadCap:conditionalText MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">см. <MadCap:xref href="../technolog/outgoing_mail_ITSM.htm">Параметры подключения. Исходящая почта</MadCap:xref></MadCap:conditionalText>.</p>

<p MadCap:conditions="Default.WEB-HELP" class="note_stroca" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd"> </p>

<ul class="webHelp">
  <li MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Быстрый старт. Шаг 4. <MadCap:xref href="Quick_Start_4.htm">Настройка регистрации заявок по почте</MadCap:xref>.</li>
</ul>
