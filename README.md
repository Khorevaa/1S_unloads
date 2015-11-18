﻿Создание файлов выгрузки информационных баз
---------------------------

`1Script` [OneScript](http://oscript.io/docs) скрипт для создания `*.dt` файлов выгрузки нескольких информационных баз c отключением и блокировкой пользовательских подключений и регламентных заданий (в серверной ИБ).

Параметры выполнения читаются из файла `unloads.json` при его отсутствии создается заготовка файла. 

Обратные слеши `\` в файле конфигурации следует заменять на прямые `/`

Файловая ИБ должна быть свободна от сеансов.

ver. 1.1.0	Реализована работа в синхронном (последовательном) режиме без использования библиотеки [v8runner](http://oscript.io/library/package/v8runner)
