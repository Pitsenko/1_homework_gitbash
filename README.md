# 1_homework_gitbash
1) Посмотреть где я ===  **pwd**  
2) Создать папку ===  **mkdir 1homework**  
3) Зайти в папку ===  **cd 1homework**  
4) Создать 3 папки === **mkdir f1 f2 f3**   
5) Зайти в любоую папку === **cd f1**  
6) Создать 5 файлов (3 txt, 2 json) === **touch text1.txt text2.txt text3.txt 1js.json 2js.json**  
7) Создать 3 папки === **mkdir folder_1 folder_2 folder_3**  
8) Вывести список содержимого папки === **ls -l**  
9) Открыть любой txt файл === **vim text1.txt**  
10) Написать туда что-нибудь, любой текст. === **I (write text "hello. how are you?")**   
11) Cохранить и выйти. ===  **press ESQ, :WQ, Enter**  
12) Выйти из папки на уровень выше === **cd ..**  
13) Переместить любые 2 файла, которые вы создали, в любую другую папку === **mv 1j.json 2js.json folder_1**  
14) Скопировать любые 2 файла, которые вы создали, в любую другую папку === **cp folder_1/1js.json text3.txt ../f2/**  
15) Найти файл по имени === **find -name "text3.txt"**  
16) Просмотреть содержимое в реальном времени === **tail -f text1.txt**  
17) Вывести несколько первых строк из текстового файла === **head -n3 text1.txt**  
18) Вывести несколько последних строк из текстового файла === **tail -n3 text1.txt**  
19) Просмотреть содержимое длинного файла === **less text1.txt**  
20) Вывести дату и время === **date**  


=====================================
1) Отправить http запрос на сервер.  ===  curl http://162.55.220.72:5005/terminal-hw-request 
curl "http://162.55.220.72:5005/get_method?name=(OLEG)&age=(35)"

 - Результат запроса **["(OLEG)","(35)"]**  

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13 :

touch iscript.txt  
vim iscript.txt  

#!/bin/bash  
mkdir 1homework_new   
cd 1homework_new  
mkdir p1 p2 p3  
cd p2  
touch js1.json js2.json 11.txt 22.txt 33.txt  
mkdir folder1 folder2 folder3  
ls -la  
mv 11.txt 22.txt folder3  

ESQ :wq   
./iscript.txt  










