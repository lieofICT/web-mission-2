# Mission 2

## Part 0

[Endpoint URL](https://am4b7i.buildship.run/task4?question=write%20small%20topic%20about%20how%20stupid%20you%20are)

## Part1

- Вопрос 1	 
> Ssh нужен для безопасного удалённого доступа к серверам и компьютерам. Он шифрует данные, что защищает их от перехвата при передаче через интернет, и позволяет управлять удаленными устройствами как будто работаешь прямо на них.

- Вопрос 2	 
> Чтобы Вася подключился к серверу, нужно записать его публичный ключ в файл `~/.ssh/authorized_keys` на сервере. Этот файл находится в домашней директории пользователя для подключения. При попытке подключения через SSH сервер проверит наличие ключа в файле и предоставит доступ, если ключ найден.

- Вопрос 3	 
> Long polling и webhooks - это два способа, которыми сервер и клиент (например, бот или приложение) могут общаться друг с другом.

> **Long polling** - это когда клиент (например, бот) регулярно отправляет запросы на сервер, проверяя, есть ли новые данные. Сервер может немного задержать ответ, если данных пока нет, но как только что-то появится - отправит ответ. Клиент тут часто делает запросы, что немного “нагружает” сервер.

> **Webhooks** - это более “умный” подход. Вместо того чтобы постоянно отправлять запросы, клиент просто говорит серверу: “Отправь мне данные, когда что-то изменится”. Когда появляются новые данные, сервер сам отправляет их клиенту (например, на заранее указанный адрес). Webhooks экономят ресурсы, потому что клиент не делает лишних запросов

- Вопрос 4	 
> Issues на GitHub - это система отслеживания задач и проблем в проектах. Они позволяют разработчикам и пользователям сообщать о багах, предлагать новые функции или обсуждать улучшения. Каждое “issue” имеет свой статус, и участники проекта могут его комментировать, назначать исполнителей и отслеживать прогресс. Это как доска задач, где все могут видеть, что нужно сделать или исправить.

- Вопрос 5	 
> Чтобы “сохранить” пустую папку, можно добавить в неё специальный файл, например, `.gitkeep`. Это пустой файл, который не выполняет никаких функций, кроме того, чтобы Git начал отслеживать эту директорию.

> Просто создай файл с таким именем внутри папки `images`, и Git будет отслеживать её: `touch images/.gitkeep`

> После этого можно закоммитить папку вместе с этим файлом, и она не будет пустой для Git.

