# listenerTCP
Небольшая программа для отладки рабочего проекта. 

Есть рабочий проект fileToTCP, который читает файлы логов из указанного каталога и отправляет в принимающий канал по 
TCP. Данный проект будет модифицироваться, он должен читать файл, определять поля из структуры json. Прочитанные данные 
нужно дополнительно отправлять в Jaeger. 
В дальнейшем проект будет переименован, например, transporterLogs.