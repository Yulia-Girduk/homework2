# Инструкция для работы с Git и удалёнными репозиториями
***
## Что такое Git?

**_Git_** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
***
* Подготовка репозитория
**Git init**

     Для создание репозитория необходимо выполнить команду **git init** в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

* Создание коммитов
**Git add**

    Для добавления измений в коммит используется команда **git add**. Чтобы использовать команду **git add** напишите **git add _<имя файла>_**

* Просмотр состояния репозитория
**Git status**

    Для того, чтобы посмотреть состояние репозитория используется команда **git status**. Для этого необходимо в папке с репозиторием написать **git status**, и Вы увидите были ли измения в файлах, или их не было.

* Создание коммитов
**Git commit**

    Для того, чтобы создать коммит(сохранение) необходимо выполнить команду **git commit**. Выполняется она так: **git commit -m _"<сообщение к коммиту>_**. 

    Все файлы для коммита должны быть 
    1. ДОБАВЛЕНЫ, 
    2. ОБЯЗАТЕЛЬНО писать сообщение к коммиту.

* Перемещение между сохранениями
**Git checkout**

    Для того, чтобы перемещаться между коммитами, используется команда **git checkout**. Используется она в папке с пепозиторием следующим образом: **git checkout _<номер коммита>_**

* Журнал изменений
**Git log**

    Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда **git log**. Для этого достаточно выполнить команду **git log** в папке с репозиторием

## Ветки в Git
* Создание ветки
**Git branch**

    Для того, чтобы создать ветку, используется команда **git branch**. Делается это следующим образом в папке с репозиторием: **git branch _<название новой ветки>_**

* Слияние веток
**Git merge**
    
    Для того чтобы дабавить ветку в текущую ветку используется команда **git merge**

* Удаление веток
**Git branch -d**

    Для удаления ветки ввести команду **"git branch -d _'name branch'"_**
