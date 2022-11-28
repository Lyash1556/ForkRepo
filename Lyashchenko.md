# **Краткая инструкция по использованию Git**

## Настройка репозитория

* __Git init__ - команда для создания нового репозитория. Выполняется 1 раз для создания нового репозитория. Также  будет создана новая главная ветка.

* __git config --global user.name__ - команда задает имя автора, которое будет использоваться для всех коммитов, выполненных текущим пользователем.
 
* __git config --global user.email__ - команда задает адрес электронной почты автора, который будет использоваться для всех коммитов, выполненных текущим пользователем.

* __git config --global alias.alias-name git-command__ - позволяет создать горячие клавиши для команд Git.

## Сохранение изменений

* __git add__ - команда добавляет изменение из рабочего каталога в раздел проиндексированных файлов. Она сообщает Git, что вы хотите включить изменения в конкретном файле в следующий коммит.

* __git commit__ - команда делает для проекта снимок текущего состояния изменений, добавленных в раздел проиндексированных файлов. Такие подтвержденные снимки состояния можно рассматривать как «безопасные» версии проекта. Является одной из основных и первостепенных функций.

* __git commit -m "commit message"__ Быстрая команда, которая создает коммит с указанным в двойных кавычках комментарием.

_Эти 2 команды используются чаще всего_

* __git diff__ - представляет собой многоцелевую команду Git, которая инициирует функцию сравнения источников данных Git — коммитов, веток, файлов и т. д.

## Проверка репозитория

* __git status__ - команда отображает состояние рабочего каталога и раздела проиндексированных файлов. С ее помощью можно проверить индексацию изменений и увидеть файлы, которые не отслеживаются Git.

* __git log__ - команда отображает отправленные снимки состояния и позволяет просматривать и фильтровать историю проекта, а также искать в ней конкретные изменения. Показывает историю коммитов.

* __git log --oneline__ позволяет форматировать историю коммитов более компактно.

## Отмена изменений

* __git checkout__ — команда как простой способ «загрузить» любой из сохраненных снимков на компьютер разработчика. Перейти можно как к нужному коммиту так и к нужной ветке.

## Совместная работа над репозиториями

* __git clone__ — команда позволяет склонировать удаленный репозиторий на локальный ПК. В конце команды необходимо ввести ссылку на удаленный репозиторий.

* __git pull__ — команда позволяет  скачать все из текущего репозитория и автоматически сделать merge с нашей версией.

* __git push__ — команда позволяет отправить нашу версию репозитория на внешний репозиторий.