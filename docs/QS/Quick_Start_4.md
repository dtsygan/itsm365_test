<h1 MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Настройка регистрации заявок по почте</h1><h2 MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Настройка регистрации заявок по почте</h2>
В системе существует возможность автоматической регистрации заявок на основе писем, поступивших на определенный электронный адрес.

<p class="note">При подключении к почтовому серверу система в процессе обработки почты прочитает все письма в папке, удалит их с почтового сервера и обработает каждое письмо в соответствии с правилом обработки почты:<br />- POP3 — в папке "Входящие" (inbox);<br />- IMAP4, EWS — в папке, указанной для сканирования.<br />Если вы хотите, чтобы письма не удалялись, то используйте подключения IMAP4 или EWS. Укажите для данных подключений Папку для писем без ошибок и Папку для писем с ошибками. Система будет размещать обработанные письма в указанные папки.<br /></p>

Если вам важны существующие письма, но их не нужно забирать в систему, то можно перенести их в другую папку (не inbox) перед подключением почты.

<p class="note">Чтобы использовать возможность регистрации заявок по почте, укажите параметры сервера входящей почты в настройках системы. </p>

Чтобы указать параметры подключения к серверу входящей почты, в интерфейсе технолога перейдите в раздел "Настройка системы" → "Почта" → "Параметры подключения" (вкладка "Входящая почта") и укажите параметры подключения.

Подключение к серверу входящей почты возможно по протоколам POP3, IMAP и EWS.

<table style="width: 100%;margin-left: 0;margin-right: auto;mc-table-style: url('../Resources/TableStyles/PatternedRows.css');" class="TableStyle-PatternedRows" cellspacing="0">
  <col class="TableStyle-PatternedRows-Column-Column" />
  <col class="TableStyle-PatternedRows-Column-Column" />
  <col class="TableStyle-PatternedRows-Column-Column" style="width: 269px;" />
  <col class="TableStyle-PatternedRows-Column-Column" />
  <thead>
    <tr class="TableStyle-PatternedRows-Head-Header">
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">Параметры/Протокол</th>
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">POP3</th>
      <th class="TableStyle-PatternedRows-HeadE-Column-Header">IMAP4</th>
      <th class="TableStyle-PatternedRows-HeadD-Column-Header">EWS</th>
    </tr>
  </thead>
  <tbody>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">Сервер</td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body" colspan="2">IP адрес или DNS имя сервера, который используется для получения почты</td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">Полный адрес до точки подключения к серверу Exchange, который используется для получения почты, включая протокол (http(s)://), например, https://имя_или_адрес_Exchange/ews/Exchange.asmx.</td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Порт</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body" colspan="2">
        <p class="td">Порт, соответствующий типу соединения (цифрами)</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">— </p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Логин</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body" colspan="3">
        <p class="td">Имя почтового ящика (электронный адрес почтового ящика)</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Пароль</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body" colspan="3">
        <p class="td">Пароль для доступа к почтовому ящику</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">Протокол</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">POP3</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">IMAP4</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">EWS (Exchange Web Services)</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p class="td">SSL соединение</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body" colspan="2">
        <p class="td">Подключения к почтовому серверу с использованием защищенного соединения SSL (данное требование определяется настройками почтового сервера).</p>
        <p class="td">По умолчанию SSL-соединение не используется (флажок снят)</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">—</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyE-Column-Body">
        <p>Аутентификация OAuth2</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyE-Column-Body" colspan="2">
        <p class="td">—</p>
        <p class="td"> </p>
      </td>
      <td class="TableStyle-PatternedRows-BodyD-Column-Body">
        <p class="td">Признак, включающий использование для авторизации протокола OAuth2. Данный тип аутентификации позволяет подключаться без использования пароля на прямую. Для подключения используются токены доступа полученные из AzureAD.</p>
        <p class="td">Если флажок включен, то на форма отображаются дополнительные параметры:</p>
        <p class="td">- Идентификатор приложения</p>
        <p class="td">- Идентификатор каталога</p>
        <p class="td">- Секрет клиента</p>
        <p class="td">Значения параметров заполняются данными, полученными при регистрации приложения в Azure AD</p>
      </td>
    </tr>
    <tr class="TableStyle-PatternedRows-Body-Body">
      <td class="TableStyle-PatternedRows-BodyB-Column-Body">
        <p class="td">Папки для сканирования</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyB-Column-Body">
        <p class="td">—</p>
      </td>
      <td class="TableStyle-PatternedRows-BodyA-Column-Body" colspan="2">
        <p class="td"> Путь до папок, из которых будут забираться письма для обработки, в формате: "<i>INBOX/&amp;lt;наименование папки&amp;gt;</i>". </p>
        <p class="td">Пути к папкам перечисляются через запятую ",", точку с запятой ";". </p>
        <p class="td">В качестве разделителя пути используется слеш "\", "/". </p>
        <p class="td">Если указана папка "INBOX", то обработке подлежат входящие письма из данной папки</p>
      </td>
    </tr>
  </tbody>
</table><p class="ris">
  <img src="../Resources/Images/core_tech/mail_03.png" title="Параметры подключения Входящая почта" class="doc" />
</p>

<p class="img_num" MadCap:conditions="Default.PDF" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Вкладка "Входящая почта"</p>

<p class="beforeList">Подробное описание настройки регистрации заявок по электронной почте:</p>

<ul class="webHelp">
  <li>Процесс регистрации заявок по электронной почте <MadCap:conditionalText MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">см. <MadCap:xref href="../request/Inc_1.htm#02">Регистрация заявки по электронной почте</MadCap:xref></MadCap:conditionalText>.</li>
  <li>Настройка параметров входящей почты в интерфейсе технолога <MadCap:conditionalText MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">см. <MadCap:xref href="../technolog/incomingMail_ITSM.htm">Параметры подключения. Входящая почта</MadCap:xref></MadCap:conditionalText>.</li>
  <li>Настройка регистрации заявки незарегистрированным пользователем <MadCap:conditionalText MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">см. <MadCap:xref href="../setting/settings_mail.htm">Настройки почты</MadCap:xref></MadCap:conditionalText>. </li>
</ul><p class="note_stroca" MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd"> </p>

<ul class="webHelp">
  <li MadCap:conditions="Default.WEB-HELP" xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">Быстрый старт. Шаг 5. Система готова к регистрации заявки, см. <MadCap:xref href="Quick_Start_5.htm">Регистрация заявки</MadCap:xref>.</li>
</ul>
