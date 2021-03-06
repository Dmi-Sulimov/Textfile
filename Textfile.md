Чтобы внести заголовок первого уровня необходимо поставить знак # и пробел перед вводимым текстом, а после введенного текста внести пробел и знак #
# Инструкция по работе с файлом в Markdown #

Чтобы внести заголовок второго уровня необходимо поставить знак ## и пробел перед вводимым текстом, а после введенного текста внести пробел и знак ##
## Инструкция по работе с файлом в Markdown ##

Чтобы внести заголовок n-ого уровня необходимо поставить знак n раз # и пробел перед вводимым текстом, а после введенного текста внести пробел и знак n раз #

Чтобы текст переместился на вторую строку нужно оставить вторую строку свободной

Это пример

переноса строки 

Для выделения курсивом нужно поставить * перед текстом и после него

*Курсив*

Для обозначения цитат используется знак > больше

>Это пример цитаты

>в которой перед каждой строкой

>ставится знак больше

Для ненумерованного списка нужно вставить знак * и пробел перед текстом

* Это первый элемент ненумерованного списка
* Это второй элемент ненумерованного списка
* Это третий элемент ненумерованного списка

Для нумерованного списка необходимо вставить нумерацию перед текстом
1. Это первый элемент нумерованного списка
2. Это второй элемент нумерованного списка
3. Это третий элемент нумерованного списка

Для вставки изображения необходимо вставить

![Изображение](фотка.jpg "Программирование")

## Инструкция по работе с GIT ##

### Консольные команды ###

> **git init** - создать новый репозиторий

> **git init folder-name** - создать новый проект в указанной директории

### Просмотр изменений ###

> **git status** - показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)

> **git diff** - сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ)

> **git diff --color-words** - сравнить рабочую директорию и индекс, показать отличия в словах (неотслеживаемые файлы ИГНОРИРУЮТСЯ)

> **git diff index.html** - сравнить файл из рабочей директории и индекс

> **git diff HEAD** - сравнить рабочую директорию и коммит, на который указывает HEAD (неотслеживаемые файлы ИГНОРИРУЮТСЯ)

> **git diff --staged** - сравнить индекс и коммит с HEAD

> **git diff master feature** - посмотреть что сделано в ветке feature по сравнению с веткой master

> **git diff --name-only master feature** - посмотреть что сделано в ветке feature по сравнению с веткой master, показать только имена файлов

> **git diff master...feature** - посмотреть что сделано в ветке feature с момента (коммита) расхождения с master

### Добавление изменений в индекс

> **git add .** - добавить в индекс все новые, изменённые, удалённые файлы из текущей директории и её поддиректорий

> **git add text.txt** - добавить в индекс указанный файл (был изменён, был удалён или это новый файл)

> **git add -i** - запустить интерактивную оболочку для добавления в индекс только выбранных файлов

> **git add -p** - показать новые/изменённые файлы по очереди с указанием их изменений и вопросом об отслеживании/индексировании

### Коммиты

> **git commit -m "Name of commit"** - зафиксировать в коммите проиндексированные изменения (закоммитить), добавить сообщение

> **git commit -a -m "Name of commit"** - проиндексировать отслеживаемые файлы (ТОЛЬКО отслеживаемые, но НЕ новые файлы) и закоммитить, добавить сообщение

# Данные изменения для удаленного репозитория #

Обучение на разработчика

Передача на локальный git
