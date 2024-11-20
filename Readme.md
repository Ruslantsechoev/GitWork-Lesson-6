# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)
## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть *ДОБАВЛЕНЫ* и сообщение к коммиту писать *ОБЯЗАТЕЛЬНО*.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

# Язык разметки Markdown
## Заголовки
Создание заголовков производится путём помещения знака решетки **перед** текстом заголовка. Количество знаков «#» соответствует уровню заголовка. HTML предоставляет 6 уровней заголовков.
## Синтаксис
*Курсив* - выделяется одной звездочкой слева и справа.
**Полужирный** - выделяется двумя звездочками слева и справа.
~~Зачеркнутый текст~~ - выделяется двумя дугами слева и справа.
## Списки
* Элемент маркированного списка
* Элемент 2
* Элемент 3
1. Элемент нумерованного списка
2. Элемент №2 того же списка
9. Элемент №3 списка — элементы нумеруются по порядку, цифра в начале строки не имеет значения
## Цитаты (тег blockquote)
> Данный текст будет заключен в HTML-теги <blockquote></blockquote>
## Ссылки
Пример добавления ссылки [текст ссылки][https://ru.wikipedia.org/wiki/Markdown]
## Изображения
![Изображение](Logo1.jpg)

# Home work 2
## Задание

Продолжить работу с файлом, начатую на Семинаре 1. Создать и слить как минимум 4 ветки. Обязательно создать конфликт и разрешить его. Архив с репозиторием и проделанной работой приложить к уроку.
## Описание решения
Созданы 4 ветки:
* Master - корневая ветка, HEAD);
* MarkDown - ветка с инструкцией по синтаксису;
* HomeWork2 - ветка с описанием домашнего задания;
* Decision - описание решений по домащнему заданию.

Ветки слиты в Master, проведены слияния и конфликт/размрешение конфликта при слиянии.

# Home work 3
## Задание
Дополнить файл с инструкцией по работе с git (второе домашнее задание) и направить pull request в репозиторий преподавателя.

Файл с инструкцией необходимо дополнить информацией о работе с удаленными репозиториями.
В системе подгрузить скриншот отправленного pull request.

## Описание решения
1. Дополнили файл Home work 2 информацией с заданием Home work 3;
2. Создан аккаунт на GitHub.com;
3. Создан локальный репозиторий https://github.com/Malakhovskaya/TutorialHub.git;
4. Отправлен (push) локальный репозиторий в удалённый (на GitHub).
5. Направлен pull request в репозиторий преподавателя.
