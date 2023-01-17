# Инструкция по работе с Git

## Что такое GIT?
***GIT*** - это одна из реализаций распределенной системы контроля версий, поддерживающие как локальные, так и удаленные репозитории. Самая популярная реализация GIT - это [GitHub](https://github.com)
## Подготовка репозитория
Репозиторий
## Создание коммитов
Для создания коммита используется команда *git commit*.

### Выполнение коммитов
Для того, чтобы использовать коммит используется команда *git commit*. Для этого в терминале с папкой-репозитория необходимо написать *git commit -m "<сообщение к коммиту>"*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***

### Добавления файла к коммиту
Для добавления файла к коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Журнал изменений
Для просмотра истории коммитов используется команда *git log*. Для этого в терминале с папкой-репозиторием пишем *git log*. В журанале показанном обязательно будут:
* Хэш (номер) коммита
* Дата и время коммита
* Автор коммита
* Текст сообщения к коммиту

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout <хэш коммита>*. Хэш коммита можно взять из истории коммитов, про которую было рассказано в предыдущем пункте.

## Ветки в  GIT
Ветка в Git - это простой перемещаемый указатель на один из таких коммитов. По умолчанию, имя основной ветки в Git - master. Как только вы начнете создавать коммиты, ветка master будет всегла указывать на последний коммит. Каждый раз при создании коммита указатель ветки  master будет передвигаться на следующий коммит автоматически.
## Слияние веток и разрешение конфликтов

## Удаление веток