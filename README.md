# itmo_web_2

### Part 0

[Скринкаст](https://ugolmariia.notion.site/web_2-c198563d5e53428a9194d3313fa176cc?pvs=4)

### Part 1
**Вопрос 1.** Зачем нужен ssh? Ответ на пару предложений

- ssh используется для безопасного удаленного доступа к компьютерам через незащищенную сеть. Подключение требуется, например, для отправки файлов, просмотра логов

**Вопрос 2.** Предположим, у вас есть прямой доступ к серверу(терминалу) под управлением ubuntu. У вас есть коллега Вася, который хочет получить доступ к этому серверу. Он генерирует пару ssh ключей с помощью команды ssh-keygen и дает вам свой публичный ключ. В какой файл на сервере нужно записать ключ, чтобы Вася смог подключиться к терминалу сервера?

- Публичный ключ Васи нужно добавить в файл **~/.ssh/authorized_keys**

**Вопрос 3.**  Тут вопрос про АПИ. Разберитесь, что такое long polling и webhooks, опишите сами в нескольких предложениях, как они работают.

- Long polling - это метод обмена данными между сервером и клиентом, при котором клиент отправляет запрос на сервер и сервер не моментально отвечает, а задерживает ответ до появления новой информации или истечения таймаута.
- Webhooks - это механизм, при котором сервер отправляет HTTP POST запросы к указанному URL для уведомления о событиях, таких как обновление данных или изменение состояния.

https://grammy.dev/guide/deployment-types

**Вопрос 4.** Найдите информацию, что такое issues на гитхабе и для чего нужны. Также вставьте ссылки на пару примеров issues в популярных open source проектах.

- Issues на GitHub - это место, где пользователи могут создавать отчеты об ошибках, предложения по улучшению или другие комментарии к проекту. Это помогает разработчикам отслеживать проблемы и взаимодействовать с сообществом.
- Примеры:
      - [bootstrap](https://github.com/twbs/bootstrap/issues)
      - [Tensorflow](https://github.com/tensorflow/tensorflow/issues)

**Вопрос 5.** Ваш проект используется пустую папку images, но гит не поддерживает отслеживание пустых директорий. Что делать?

- Гит не отслеживает пустые директории, поэтому нужно вручную добавить в них временный файл, например, .gitkeep, чтобы они были в репозитории. Это позволит сохранить структуру папок в Git, не добавляя ненужных файлов.

