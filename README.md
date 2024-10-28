# ПРОЕКТ-ШПАРГАЛКА

### Настройка Git
Файл настройки .gitconfig.
Располагается в домашней директории 
**Windows:**
- Обозначение: `%HOMEPATH%`
- Полный путь: C:\\Users\\username\\
**Linux:**
- Обозначение: ~
- Польный путь: /home/username

Настройки Git могут быть **системные**, **глобальные** и **локальные**(*проектные*).
Все они располагаются в своих конфигурационных файлах.
Ниже пример конфигурации имени и электронного ящика пользователя.
`git config --global user.name "Surname Name"`
`git config --global user.email "your_email"`.

### Bash. Навигация
- pwd (от англ. _**p**rint **w**orking **d**irectory_, «показать рабочую папку») — покажи, в какой я папке;
- ls (от англ. _**l**i**s**t directory contents_, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;
- ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа `.`;
- cd project (от англ. _**c**hange **d**irectory_, «сменить директорию») — перейди в папку *project*;
- cd project/html — перейди в папку *html*, которая находится в папке *project*;
- cd .. — перейди на уровень выше, в родительскую папку;
- cd ~ — перейди в домашнюю директорию (*/Users/Username*);
- cd / — перейди в корневую директорию.
---
### Bash. Работа с файлами и папками
**Создание**
- `touch index.html` (англ. _touch,_ «коснуться») — создай файл `index.html` в текущей папке;
- `touch index.html style.css script.js` — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;
- `mkdir second-project` (от англ. _**m**a**k**e **dir**ectory_, «создать директорию») — создай папку с именем `second-project` в текущей папке.

**Копирование и перемещение**
- `cp file.txt ~/my-dir` (от англ. _**c**o**p**y_, «копировать») — скопируй файл в другое место;
- `mv file.txt ~/my-dir` (от англ. _**m**o**v**e_, «переместить») — перемести файл или папку в другое место.

**Чтение**
- `cat file.txt` (от англ. _con**cat**enate and print_, «объединить и распечатать») — распечатай содержимое текстового файла `file.txt`.

**Удаление**
- `rm about.html` (от англ. _**r**e**m**ove_, «удалить») — удали файл `about.html`;
- `rmdir images` (от англ. _**r**e**m**ove **dir**ectory_, «удалить директорию») — удали папку `images`;
- `rm -r second-project` (от англ. _**r**e**m**ove,_ «удалить» + _**r**ecursive_, «рекурсивный») — удали папку `second-project` и всё, что она содержит.
