# Privacy Policy for A2Z

**Last Updated: January 24, 2026**

---

## English Privacy Policy

### Introduction

This Privacy Policy describes how A2Z ("we", "our", or "the app") collects, uses, and protects your information when you use our Android and web application.

**Important Context**: A2Z is a workplace application designed for operational accountability. The app is used in workplace contexts where shift-based work and operational control are required (for example: security, cleaning, facility management, retail/shopping malls, hotel operations/reception, and other on-duty roles). It helps organizations verify on-duty activity, route/checkpoint completion, and incident reporting during shifts. The purpose is to enable companies and organizations to verify on-duty activity and incident reports performed by their employees and other on-duty staff during shifts. We do NOT collect data for advertising or data brokerage purposes. Data is collected solely to provide the service to the customer organization (your employer or company) and to operate the app.

**This app is intended for authorized employees of participating organizations.**

The app is intended for workplace use by authorized staff and is not intended for children.

### Who Controls Your Data

- **Service Provider**: We (the app developers) provide the A2Z application and service infrastructure.
- **Data Controller**: The customer organization (your employer or company) that administers the app for its employees may act as a data controller and may have access to employee activity data collected via the app, including on-duty route/activity logs, incident reports, and related operational records.
- **Your Role**: As an employee or on-duty staff member using the app on behalf of your organization, data you enter or that is collected while you use the app may be accessible to your organization for operational and accountability purposes.

### What Data We Collect

The app collects the following categories of information:

- **Account and Authentication Data**: Email address, name (if provided), Firebase user identifier (UID), organization association, role/position, and authentication tokens. Phone numbers may be displayed or used for organization-level contacts (e.g., emergency contacts) or selected by the user to initiate calls, but are not stored in the user's account profile as an account field.
- **Location Data**: 
  - Precise location coordinates (latitude, longitude) when using location features
  - Location data for incident tagging and map features
  - Background location data for on-duty route/activity tracking when you are on duty
  - Location history and on-duty route/activity records stored as part of operational logs
  - When we collect location: Location is collected only when you use location features (e.g., incident tagging/maps) and, if enabled by your organization, during on-duty tracking.
- **Media Files**: Photos and audio recordings that you explicitly capture within the app for incident reporting purposes. These files are uploaded when you submit an incident report. Video recording is not currently supported.
- **Incident Reports**: Text descriptions, timestamps, location tags, media attachments, and metadata related to incidents you report.
- **On-duty Activity Data**: Checkpoint scans (NFC tag identifiers), on-duty route/activity records, duty status, timestamps, and related operational metadata.
- **Device and App Usage Data**: 
  - Device identifiers and push notification tokens (e.g., FCM token)
  - App interaction data may be collected through Firebase Analytics when enabled (including automatic collection such as app usage events and device/app information, as provided by Firebase)
  - Local storage data (cached settings, session state, offline data)
- **Communication Data**: Phone numbers you select to call within the app (the app does not record call content).

### How We Use Data

We use collected data for the following purposes:

- **Service Provision**: To provide the incident reporting, on-duty route/activity tracking, and operational accountability features to your organization.
- **On-duty Route/Activity Tracking**: To record and display routes and checkpoint/task verification when you are on duty (for roles where this feature is enabled).
- **Incident Management**: To process, store, and make available incident reports (including attached media) to your organization.
- **App Functionality**: To enable features such as maps, location tagging, NFC checkpoint scanning, camera capture, and phone call initiation.
- **Notifications**: To send operational notifications (e.g., duty reminders, incident updates) via Firebase Cloud Messaging. We use push notification tokens (e.g., FCM token) to deliver notifications to your device.
- **App Improvement**: To analyze app usage patterns and fix bugs (we may use Firebase Analytics for this purpose when enabled).
- **Security and Compliance**: To maintain security, prevent fraud, and comply with legal obligations.

In workplace contexts, processing is performed to provide the service to the organization and to support operational accountability; your organization may determine the purposes and legal basis for employee monitoring/records under applicable law. Processing may be based on contract with the customer organization and/or legitimate interests in operating workplace accountability features, and the customer organization may have additional obligations under local employment/privacy law.

### Permissions and Why We Request Them

The app requests the following permissions and uses them as described:

- **INTERNET**: Required to communicate with backend services (Firebase) and load web content.
- **ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION**: Used for incident location tagging, displaying maps, and location-based features. Location is accessed when you use location features or submit incidents with location data.
- **ACCESS_BACKGROUND_LOCATION**: Used to track on-duty routes/activities in the background when shift tracking is enabled. This allows the app to continue recording your route/activity even when the app is in the background or the screen is off. Background location tracking is only active when duty/shift tracking is enabled and may use a foreground service with a persistent notification when supported. You can stop tracking by ending your duty/shift in the app or revoking the permission in your device settings.
- **FOREGROUND_SERVICE / FOREGROUND_SERVICE_LOCATION**: Used when supported/required by Android to run on-duty location tracking as a foreground service (with a user-visible notification), helping ensure routes/activities are recorded reliably.
- **CAMERA**: Used to capture photos for incident reporting. The camera is accessed only when you explicitly choose to take a photo within the app. We do not access the camera in the background or without your direct action.
- **RECORD_AUDIO**: Used to record audio for incident reports when you explicitly start recording within the app. The app does not record audio in the background or without your direct action.
- **NFC**: Used to scan NFC tags for checkpoint verification during on-duty activities. NFC is used only when you actively scan a tag; it is not used in the background. NFC tag identifiers may be stored as part of on-duty activity logs visible to your organization.
- **CALL_PHONE**: Used to initiate phone calls to numbers you select within the app (e.g., dispatcher, support, emergency contacts). The app does not record call content.
- **POST_NOTIFICATIONS**: Used to display operational notifications (duty reminders, incident updates) and foreground service notifications for on-duty route/activity tracking.
- **VIBRATE**: Used for UI feedback and alerts within the app.

### Background Location and On-duty Activity Tracking

When you are on duty, the app may track your location in the background to record your on-duty route/activity. This tracking:

- May run as a foreground service when supported, which typically displays a persistent notification while tracking is active
- Is only active when duty/shift tracking is enabled in the app
- Can be stopped by ending your duty/shift in the app or by revoking location permissions in your device settings
- Records location data that may be stored in the backend (Firebase) as part of operational records visible to your organization
- Is used solely for operational accountability and route/activity documentation during shifts

### Data Storage and Sharing

- **Local Storage**: Data may be stored locally on your device using AsyncStorage or device storage for caching settings, session state, offline data, and temporarily storing captured media before submission.
- **Backend Storage**: 
  - Media files are uploaded only when you submit an incident report (or explicitly choose to attach/submit media)
  - Incident reports, on-duty route/activity data, checkpoint records, and related operational data may be stored in Firebase Firestore or Realtime Database
  - Uploaded media may be stored in Firebase Storage
- **Service Providers**: We use service providers to process data on our behalf:
  - **Firebase Services** (Google): Firebase Authentication, Firestore, Realtime Database, Storage, Cloud Functions, Analytics, and Cloud Messaging act as service providers/processors. They process data according to our instructions and their own privacy policies. Data may be processed on infrastructure in different regions depending on Firebase configuration. For Google Play Data Safety, Firebase is considered a third-party service provider, and certain data may be processed by Google/Firebase to provide analytics (when enabled), authentication, storage, messaging, and database functionality.
  - We do not sell personal data, and we do not disclose it to third parties for advertising, marketing, or data brokerage. We do not use collected data for targeted advertising or cross-app tracking.
- **Organization Access**: Data collected while you use the app on behalf of your organization may be accessible to your organization (the customer/employer) and its administrators for operational and accountability purposes. Your organization may determine which features are enabled and how the app is used, including how long operational data is retained.

### Data Retention

- Operational data (incident reports, on-duty route/activity logs, checkpoint records) may be retained as long as necessary to provide the service to your organization and as required by your organization's policies or legal obligations. We do not implement automatic data deletion or default TTL policies; data may be retained until deleted by your organization or processed via deletion request.
- Some records may be retained for legal, security, or audit purposes even after account deletion.
- You can request deletion of your account data, incident records, on-duty activity logs, and media stored on the backend through our manual process (see Contact Information section). Deletion requests are processed manually and subject to organizational policies and legal requirements.

### User Controls

You have control over:

- **Permissions**: You can grant or revoke permissions (location, camera, NFC, notifications) at any time through your device settings. Note that revoking certain permissions may limit app functionality.
- **Duty Tracking**: You can start or stop on-duty route/activity tracking by starting or ending your duty/shift in the app.
- **Camera**: You choose when to capture photos; the camera is not accessed automatically.
- **Notifications**: You can disable notifications through device settings, though this may affect operational communications.
- **Account**: You can request account deletion (see Contact Information section).

### Your Rights

You have the right to:

- **Access**: Request access to the personal data we hold about you
- **Deletion**: Request deletion of your personal data, incident records, on-duty activity logs, and media stored on the backend
- **Correction**: Request correction of inaccurate data
- **Withdrawal of Consent**: Withdraw consent for data processing where applicable (note that some processing may be necessary for service provision or required by your organization)
- **Information**: Request information about how your data is used

**Important Note**: Because this app is used in a workplace context and data may be controlled or accessible by your organization, you may also need to contact your organization's administrator or employer regarding access, deletion, or other data-related requests. Some data may be retained by your organization as the data controller even if you request deletion from us.

### Contact Information and Deletion Requests

If you have questions about this Privacy Policy or wish to exercise your rights, please contact us at:

**Email**: alina.altynbayeva.00@gmail.com

**To Request Deletion**: Email alina.altynbayeva.00@gmail.com with the subject line "Data deletion request" and include:
- Your email address or account identifier
- Your organization name (if applicable)
- Details needed to identify your account, incident records, or on-duty activity logs
- Any specific data you want deleted

Deletion requests are processed manually via email. We will review and process your request in accordance with applicable law and organizational policies. Note that some records may be retained for legal, security, or audit purposes even after deletion, and you may also need to contact your organization's administrator regarding data controlled by your employer.

### Security

We implement appropriate technical and organizational measures to protect your data against unauthorized access, alteration, disclosure, or destruction. However, no method of transmission over the internet or electronic storage is 100% secure, and we cannot guarantee absolute security.

### International Data Processing

Data may be processed and stored on infrastructure in different regions depending on service provider configuration (e.g., Firebase services may process data in various geographic locations). By using the app, you acknowledge that your data may be transferred to and processed in regions outside your country of residence.

### Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of material changes by updating the "Last Updated" date at the top of this document. Continued use of the app after such changes constitutes acceptance of the updated policy.

---

## Политика конфиденциальности для A2Z

**Последнее обновление: 24 января 2026**

**Примечание**: Русская версия является переводом; при расхождениях применяется английская версия.

---

### Введение

Настоящая Политика конфиденциальности описывает, как приложение A2Z ("мы", "наш" или "приложение") собирает, использует и защищает вашу информацию при использовании нашего Android и веб-приложения.

**Важный контекст**: A2Z — это рабочее приложение, предназначенное для оперативной отчетности. Приложение используется в рабочих контекстах, где требуется сменная работа и операционный контроль (например: охрана/безопасность, клининг, эксплуатация/Facility Management, торговые центры/ритейл, отели и ресепшн, а также другие роли "на дежурстве"). Приложение помогает организации подтверждать активность на смене, выполнение маршрутов/контрольных точек или задач и оформление инцидентов. Цель — позволить компаниям и организациям подтверждать активность на дежурстве и отчеты об инцидентах, выполняемые их сотрудниками и другим персоналом "на смене" во время дежурства. Мы НЕ собираем данные для рекламы или продажи данных. Данные собираются исключительно для предоставления услуги организации-клиенту (вашему работодателю или компании) и для работы приложения.

**Это приложение предназначено для авторизованных сотрудников участвующих организаций.**

Приложение предназначено для использования на рабочем месте авторизованным персоналом и не предназначено для детей.

### Кто контролирует ваши данные

- **Поставщик услуг**: Мы (разработчики приложения) предоставляем приложение и инфраструктуру услуг A2Z.
- **Контроллер данных**: Организация-клиент (ваш работодатель или компания), которая администрирует приложение для своих сотрудников, может выступать в качестве контроллера данных и может иметь доступ к данным о деятельности сотрудников, собранным через приложение, включая журналы маршрутов/активности на смене, отчеты об инцидентах и связанные операционные записи.
- **Ваша роль**: Как сотрудник или другой сотрудник "на смене", использующий приложение от имени вашей организации, данные, которые вы вводите или которые собираются при использовании приложения, могут быть доступны вашей организации для операционных целей и целей отчетности.

### Какие данные мы собираем

Приложение собирает следующие категории информации:

- **Данные учетной записи и аутентификации**: Адрес электронной почты, имя (если указано), идентификатор пользователя Firebase (UID), принадлежность к организации, роль/должность и токены аутентификации. Номера телефонов могут отображаться или использоваться на уровне организации (например, для экстренных контактов) или выбираться пользователем для инициации звонков, но не сохраняются в профиле пользователя как поле учетной записи.
- **Данные о местоположении**:
  - Точные координаты местоположения (широта, долгота) при использовании функций местоположения
  - Данные о местоположении для тегирования инцидентов и функций карт
  - Данные о местоположении в фоновом режиме для отслеживания маршрута/активности на смене, когда вы на дежурстве
  - История местоположений и записи маршрутов/активности на смене, хранящиеся как часть операционных журналов
  - Когда мы собираем данные о местоположении: Данные о местоположении собираются только при использовании функций местоположения (например, карты/тегирование инцидентов) и, если включено организацией, во время отслеживания на смене.
- **Медиафайлы**: Фотографии и аудиозаписи, которые вы явно создаёте в приложении для оформления инцидентов. Эти файлы загружаются при отправке инцидента. Запись видео в настоящее время не поддерживается.
- **Отчеты об инцидентах**: Текстовые описания, временные метки, теги местоположения, вложения медиафайлов и метаданные, связанные с инцидентами, о которых вы сообщаете.
- **Данные активности на смене**: Сканирование контрольных точек (идентификаторы NFC-меток), записи маршрутов/активности на смене, статус дежурства, временные метки и связанные операционные метаданные.
- **Данные об устройстве и использовании приложения**:
  - Идентификаторы устройств и токены push-уведомлений (например, токен FCM)
  - Данные о взаимодействии с приложением могут собираться через Firebase Analytics, когда включено (включая автоматический сбор событий использования и информации об устройстве/приложении, предоставляемой Firebase)
  - Данные локального хранилища (кэшированные настройки, состояние сеанса, офлайн-данные)
- **Данные связи**: Номера телефонов, которые вы выбираете для звонков в приложении (приложение не записывает содержание звонков).

### Как мы используем данные

Мы используем собранные данные для следующих целей:

- **Предоставление услуг**: Для предоставления функций отчетности об инцидентах, отслеживания активности/маршрута на смене и операционной отчетности вашей организации.
- **Отслеживание активности/маршрута на смене**: Для записи и отображения маршрута и проверки контрольных точек/задач во время дежурства (для ролей, где эта функция включена).
- **Управление инцидентами**: Для обработки, хранения и предоставления отчетов об инцидентах (включая прикрепленные медиафайлы) вашей организации.
- **Функциональность приложения**: Для включения функций, таких как карты, тегирование местоположения, сканирование NFC-контрольных точек, захват камеры и инициация телефонных звонков.
- **Уведомления**: Для отправки операционных уведомлений (например, напоминаний о дежурстве, обновлений об инцидентах) через Firebase Cloud Messaging. Мы используем токены push-уведомлений (например, токен FCM) для доставки уведомлений на ваше устройство.
- **Улучшение приложения**: Для анализа моделей использования приложения и исправления ошибок (мы можем использовать Firebase Analytics для этой цели, когда включено).
- **Безопасность и соответствие**: Для поддержания безопасности, предотвращения мошенничества и соблюдения правовых обязательств.

В рабочих контекстах обработка данных выполняется для предоставления услуги организации и поддержки операционной отчетности; ваша организация может определять цели и правовую основу для мониторинга сотрудников/записей в соответствии с применимым законодательством. Обработка может основываться на договоре с организацией-клиентом и/или законных интересах в работе функций операционной отчетности на рабочем месте, и организация-клиент может иметь дополнительные обязательства в соответствии с местным трудовым/законодательством о конфиденциальности.

### Разрешения и почему мы их запрашиваем

Приложение запрашивает следующие разрешения и использует их, как описано:

- **INTERNET**: Требуется для связи с серверными службами (Firebase) и загрузки веб-контента.
- **ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION**: Используется для тегирования местоположения инцидентов, отображения карт и функций на основе местоположения. Местоположение получается, когда вы используете функции местоположения или отправляете инциденты с данными о местоположении.
- **ACCESS_BACKGROUND_LOCATION**: Используется для отслеживания маршрутов/активности на смене в фоновом режиме, когда включено отслеживание смены. Это позволяет приложению продолжать записывать ваш маршрут/активность даже когда приложение находится в фоновом режиме или экран выключен. Отслеживание местоположения в фоновом режиме активно только когда включено отслеживание дежурства/смены и может использовать службу переднего плана с постоянным уведомлением, когда поддерживается. Вы можете остановить отслеживание, завершив дежурство/смену в приложении или отозвав разрешение в настройках устройства.
- **FOREGROUND_SERVICE / FOREGROUND_SERVICE_LOCATION**: Используется, когда поддерживается/требуется Android, для запуска отслеживания местоположения на смене как службы переднего плана (с видимым уведомлением), чтобы повысить надежность записи маршрутов/активности.
- **CAMERA**: Используется для съемки фотографий для сообщений об инцидентах. Камера получается только когда вы явно выбираете сделать фотографию в приложении. Мы не получаем доступ к камере в фоновом режиме или без вашего прямого действия.
- **RECORD_AUDIO**: Используется для записи аудио при оформлении инцидентов, только когда вы явно запускаете запись в приложении. Приложение не записывает аудио в фоновом режиме и без вашего действия.
- **NFC**: Используется для сканирования NFC-меток для проверки контрольных точек во время выполнения задач на смене. NFC используется только когда вы активно сканируете метку; он не используется в фоновом режиме. Идентификаторы NFC-меток могут храниться как часть журналов активности на смене, видимых вашей организации.
- **CALL_PHONE**: Используется для инициации телефонных звонков на номера, которые вы выбираете в приложении (например, диспетчер, поддержка, контакты экстренных служб). Приложение не записывает содержание звонков.
- **POST_NOTIFICATIONS**: Используется для отображения операционных уведомлений (напоминания о дежурстве, обновления об инцидентах) и уведомлений службы переднего плана для отслеживания активности/маршрута на смене.
- **VIBRATE**: Используется для тактильной обратной связи и предупреждений в приложении.

### Местоположение в фоновом режиме и отслеживание активности на смене

Когда вы на дежурстве, приложение может отслеживать ваше местоположение в фоновом режиме для записи вашего маршрута/активности на смене. Это отслеживание:

- Может работать как служба переднего плана, когда поддерживается, что обычно отображает постоянное уведомление, пока отслеживание активно
- Активно только когда включено отслеживание дежурства/смены в приложении
- Может быть остановлено завершением дежурства/смены в приложении или отзывом разрешений на местоположение в настройках устройства
- Записывает данные о местоположении, которые могут храниться на сервере (Firebase) как часть операционных записей, видимых вашей организации
- Используется исключительно для операционной отчетности и документирования маршрута/активности во время смены

### Хранение и передача данных

- **Локальное хранилище**: Данные могут храниться локально на вашем устройстве с использованием AsyncStorage или хранилища устройства для кэширования настроек, состояния сеанса, офлайн-данных и временного хранения захваченных медиафайлов перед отправкой.
- **Хранилище на сервере**:
  - Медиафайлы загружаются только когда вы отправляете отчет об инциденте (или явно выбираете прикрепить/отправить медиафайлы)
  - Отчеты об инцидентах, данные маршрутов/активности на смене, записи контрольных точек и связанные операционные данные могут храниться в Firebase Firestore или Realtime Database
  - Загруженные медиафайлы могут храниться в Firebase Storage
- **Поставщики услуг**: Мы используем поставщиков услуг для обработки данных от нашего имени:
  - **Службы Firebase** (Google): Firebase Authentication, Firestore, Realtime Database, Storage, Cloud Functions, Analytics и Cloud Messaging выступают как поставщики услуг/процессоры. Они обрабатывают данные согласно нашим инструкциям и своим собственным политикам конфиденциальности. Данные могут обрабатываться на инфраструктуре в разных регионах в зависимости от конфигурации Firebase. Для Google Play Data Safety Firebase считается сторонним поставщиком услуг, и некоторые данные могут обрабатываться Google/Firebase для аутентификации, хранения, сообщений, аналитики (когда включено) и работы базы данных.
  - Мы не продаём персональные данные и не передаём их третьим лицам для рекламы, маркетинга или перепродажи данных. Мы не используем собранные данные для целевой рекламы или межприложенного отслеживания.
- **Доступ организации**: Данные, собранные во время использования приложения от имени вашей организации, могут быть доступны вашей организации (клиенту/работодателю) и ее администраторам для операционных целей и целей отчетности. Ваша организация может определять, какие функции включены и как используется приложение, включая сроки хранения операционных данных.

### Хранение данных

- Операционные данные (отчеты об инцидентах, журналы маршрутов/активности на смене, записи контрольных точек) могут храниться столько, сколько необходимо для предоставления услуги вашей организации и в соответствии с политиками вашей организации или правовыми обязательствами. Мы не реализуем автоматическое удаление данных или политики TTL по умолчанию; данные могут храниться до удаления вашей организацией или обработки через запрос на удаление.
- Некоторые записи могут храниться для правовых, безопасностных или аудиторских целей даже после удаления учетной записи.
- Вы можете запросить удаление данных вашей учетной записи, записей об инцидентах, журналов активности на смене и медиафайлов, хранящихся на сервере, через наш ручной процесс (см. раздел Контактная информация). Запросы на удаление обрабатываются вручную и подлежат политикам организации и правовым требованиям.

### Контроль пользователя

Вы имеете контроль над:

- **Разрешениями**: Вы можете предоставить или отозвать разрешения (местоположение, камера, NFC, уведомления) в любое время через настройки устройства. Обратите внимание, что отзыв определенных разрешений может ограничить функциональность приложения.
- **Отслеживанием дежурства**: Вы можете начать или остановить отслеживание маршрута/активности на смене, начав или завершив дежурство/смену в приложении.
- **Камерой**: Вы выбираете, когда делать фотографии; камера не получается автоматически.
- **Уведомлениями**: Вы можете отключить уведомления через настройки устройства, хотя это может повлиять на операционные коммуникации.
- **Учетной записью**: Вы можете запросить удаление учетной записи (см. раздел Контактная информация).

### Ваши права

Вы имеете право:

- **Доступ**: Запросить доступ к персональным данным, которые мы храним о вас
- **Удаление**: Запросить удаление ваших персональных данных, записей об инцидентах, журналов активности на смене и медиафайлов, хранящихся на сервере
- **Исправление**: Запросить исправление неточных данных
- **Отзыв согласия**: Отозвать согласие на обработку данных, где применимо (обратите внимание, что некоторая обработка может быть необходима для предоставления услуги или требуется вашей организацией)
- **Информация**: Запросить информацию о том, как используются ваши данные

**Важное примечание**: Поскольку это приложение используется в рабочем контексте и данные могут контролироваться или быть доступны вашей организации, вам также может потребоваться связаться с администратором вашей организации или работодателем относительно доступа, удаления или других запросов, связанных с данными. Некоторые данные могут сохраняться вашей организацией как контроллером данных, даже если вы запросили удаление у нас.

### Контактная информация и запросы на удаление

Если у вас есть вопросы о настоящей Политике конфиденциальности или вы хотите воспользоваться своими правами, пожалуйста, свяжитесь с нами по адресу:

**Email**: alina.altynbayeva.00@gmail.com

**Для запроса удаления**: Напишите на alina.altynbayeva.00@gmail.com с темой письма "Запрос на удаление данных" и укажите:
- Ваш адрес электронной почты или идентификатор учетной записи
- Название вашей организации (если применимо)
- Детали, необходимые для идентификации вашей учетной записи, записей об инцидентах или журналов активности на смене
- Любые конкретные данные, которые вы хотите удалить

Запросы на удаление обрабатываются вручную по электронной почте. Мы рассмотрим и обработаем ваш запрос в соответствии с применимым законодательством и политиками организации. Обратите внимание, что некоторые записи могут храниться для правовых, безопасностных или аудиторских целей даже после удаления, и вам также может потребоваться связаться с администратором вашей организации относительно данных, контролируемых вашим работодателем.

### Безопасность

Мы применяем соответствующие технические и организационные меры для защиты ваших данных от несанкционированного доступа, изменения, раскрытия или уничтожения. Однако ни один метод передачи через интернет или электронного хранения не является на 100% безопасным, и мы не можем гарантировать абсолютную безопасность.

### Международная обработка данных

Данные могут обрабатываться и храниться на инфраструктуре в разных регионах в зависимости от конфигурации поставщика услуг (например, службы Firebase могут обрабатывать данные в различных географических регионах). Используя приложение, вы признаете, что ваши данные могут быть переданы и обработаны в регионах за пределами вашей страны проживания.

### Изменения в настоящей Политике конфиденциальности

Мы можем время от времени обновлять настоящую Политику конфиденциальности. Мы уведомим вас о существенных изменениях, обновив дату "Последнее обновление" в начале этого документа. Продолжение использования приложения после таких изменений означает принятие обновленной политики.
