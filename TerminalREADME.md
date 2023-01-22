# Terminal-Linux (GitBash) commands
1) Посмотреть где я   **pwd**
2) Создать папку    **mkdir Nadya**
3) Зайти в папку **cd Nady**a
4) Создать 3 папки **mkdir F1 F2 F3**
5) Зайти в любоую папку **cd F1**
6) Создать 5 файлов (3 txt, 2 json)  **touch 1.txt 2.txt 3.txt 4.json 5.json**  
8) Вывести список содержимого папки **ls ls -la**
9) Открыть любой txt файл **vim 1.txt**  
10) Написать туда что-нибудь, любой текст. **для начала редактирования латинская i, написать любой тескт**
11) Сохранить и выйти.  **esc: wq**
12) Выйти из папки на уровень выше **cd ..**
13) Переместить любые 2 файла, которые вы создали, в любую другую папку. **mv F1/1.json F1/1.txt F2**
14) Скопировать любые 2 файла, которые вы создали, в любую другую папку. **cp F1/1.json F1/1.txt F2**
15) Найти файл по имени **find F2/1.txt**
16) Просмотреть содержимое в реальном времени (команда grep) изучите как она работает. **tail -f  1.json**
17) Вывести несколько первых строк из текстового файла **head -2 1.txt**
18) Вывести несколько последних строк из текстового файла **tail -2 1.txt**
19) Просмотреть содержимое длинного файла (команда less) изучите как она работает. **less 1.txt**
20) Вывести дату и время **date "+DATE: %D TIME: %T"**

Задание *
1) Отправить http запрос на сервер.
http://162.55.220.72:5006/terminal-hw-request
**curl название сервера**
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

1. Создать файл: **touch auto.sh**
2. Внести изменения: **vim auto.sh**
3. Нажать клавишу **"i" ввести текст**
4.**#!/bin/sh** 
5. **cd Nadya/**
6. **mkdir a_1 a_2 a_3**
7. **cd a_1/**
8. **touch 1.txt 2.txt 3.txt 4.json 5.json**
9. **mkdir b_1 b_2 b_3**
10. **ls -la**
11. **mv 1.txt 2.txt F1/**
12. Cохранить и выйти: **"esc" ":wq"**
13. Выполняем скрипт: **sh auto.sh ./auto**