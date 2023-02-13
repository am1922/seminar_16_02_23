# Frist file GIT

## Text selection

To make text italicize, mark it on both sides with asterisks -
*Italics.*

To make text to be bold, mark it on both sides with double asterisks -
**Bold**

## Lists

To make text unnumbered list, mart text at start asteriks with space
* list 1
* list 2
* list 3

To make numbered list, just tap number with dot and space
1. numbered list
2. numbered list
3. numbered list

# GIT instractions

## Basic commands

* **git --version**

Команда показывает текущуую версию git которая установлена на ваш компьютер.

* **git status**

Команда отображает состояние рабочего каталога и раздела проиндексированных файлов

* **git log**

Команда перечисляет коммиты, сделанные в репозитории в обратном к хронологическому порядке — последние коммиты находятся вверху.

* **git init**

Инициализация/создание репозитория.

* **git add <имя_файла>**

Добавим конкретный файл проекта в наш будующий commit.

* **git commit -m "<комментарий>"**

Создаем commit. Обязательно указываем комментарий.
И не забываем про кавычки.

* **git commit-am "<коментарий>"**

Лайфхак который объединяет в себе две команды **git add** и **git commit -m "<комментарий>"**.

* **git checkout**

С помощью этой команды мы перемещаемся между нашими commit.

* **git checkout master**

Возвращает нас к последниму коммиту

* **git diff**

Используется для вычисления разницы между любыми двумя git деревьями.