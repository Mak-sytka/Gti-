# **Приветствую! Вижу ты не просто так сюда зашел?** 😍

----

## **Начало Освоения Git:**
В данной теме мы узнаем: *Что такое Git* | *Для чего он нужен* | *Консольные Команды* | *Основные Принципы Git.*
 
----

### **Основные Понятия:**
1. **Что такое Git?** - *это система, которая позволяет сразу нескольким разработчикам сохранять и отслеживать изменения в файлах проекта.*
2. **Что такое Консольные Команды?** - *это текстовая команда, вводимая пользователем в командной строке или терминале компьютера, которая указывает Git выполнять определённую операцию. Эти команды позволяют управлять версиями файлов, ветками проекта, изменениями, процессом слияния и другими аспектами работы в системе Git.*
3. **Что такое Репозиторий?** - *это Дерево Изменений Проекта.*

----

### **Команды и их значение:**
+ git config --global user.name " Name " - *Задать Имя Пользователя*
+ git config --global user.email " Email " - *Задать Адрес Электронной Почты*
+ git init - *связать Git с проектом*
+ git commit -m " Изменения: ..." - *когда обновления завершены и нужно сохранить новую версию проектах*
+ git push - *заливаем на GitHub обновлённую версию проекта*
+ git status - *всегда поможет проверить, занесены ли новые/изменённые файлы в Commit*
+ git remote add origin git@github.com:{   имя_аккаунта(GITHUB)   } / {   имя_проекта(GITHUB)   } - *связать репозиторий с ПК и GitHub через SSH ключ*
+ git remote -v - *убедиться, что репозиторий на ПК и на GitHub связаны.*
+ cd ..  - *перейди на уровень выше, в родительскую папку*
+ cd ~  - *перейди в домашнюю директорию (/Users/Username)*
+ cd /  -  *перейди в корневую директорию*
+ ls -  *покажи файлы и папки в текущей папке*
+ ls -a  - *покажи также скрытые файлы и папки, названия которых начинаются с символа [.]*
+ cd (name папки)  - *перейди в папку (name)*
+ touch (name файла)  - *создаст файл в текущей папке*
+ mkdir (name папки)  - *создаст папку*
+ cp (name файла) (name куда копировать) - *копируй файл в другое место*
+ mv (name файла) (name куда перенести) - *перемести файл или папку в другое место*
+ cat (name файла) - *прочитай содержимое данного файла*
+ rm (name файла) - *удали файл*
+ rmdir (name папки) - *удали папку*
+ rm -r (name папки) - *удали папку и всё, что она содержит*  
**ВАЖНО: Всё то, что удалил - __нельзя востановить!!!📍__**  
  

----

### **Полезные Возможности:😇**
1. Команды необязательно печатать и выполнять по очереди. Можно указать их списком — разделить двумя амперсандами (&&)
2. У консоли есть собственная память — буфер с несколькими последними командами. По ним можно перемещаться с помощью клавиш со стрелками вверх (↑) и вниз (↓).
3. Чтобы не вводить название файла или папки полностью, можно набрать первые символы имени и дважды нажать Tab. Если файл или папка есть в текущей директории, командная строка допишет путь сама.
Например, вы находитесь в папке dev. Начните вводить cd first и дважды нажмите Tab. Если папка first-project есть внутри dev, командная строка автоматически подставит её имя. Останется только нажать Enter.

----


| ~Git  | Это | Помогает~ |
| ------------- |:------------------:| -----:|
|      | `легко` | *сохранять / изменять / удалять* |
|      | `практично` | *отслеживать изменения* |
|      | `удобно` | *работать командой или в одиночку* | 
