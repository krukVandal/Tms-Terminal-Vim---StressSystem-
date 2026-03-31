# Vim Задача 1: 

   - Создал файл `memo` в директории `temp/practice`
     
   - Для редактирования `i`, для сохранения `:w`, для выхода `:q`, для поиска `/pattern`
     
   - Добавил текст в файл, сохранил и вышел

<img width="750" height="592" alt="image" src="https://github.com/user-attachments/assets/ca520b6a-bdff-4bfc-bec9-3c0ba4f49626" />

# Vim Задача 2: 

  - В первой строке добавил `1-203`
    
  - Изменил `C:\MOUSE на C:\GMOUSE`;
    
  - На последней строке добавил `extention 287` и заменил на `x 287`, затем удалил
    
  - В пятой строка добавил `@REM 22 apr. 1999` и сделал разрыв между строками

<img width="703" height="530" alt="image" src="https://github.com/user-attachments/assets/1ad6cf66-08ee-4b9b-88f4-b1e504f74471" />

# Vim Задача 3:
  1. 
   - Скачал файл в `temp/practice/testcase.c`

   - Включил строки `:set numbers` строк 93
     
   - Изменил слово `WORD` на `IGNORE`
     
   - Изменил слово `Reset` на `set`

<img width="762" height="395" alt="image" src="https://github.com/user-attachments/assets/d302bb8f-7a6b-427e-8b59-5117627e8bb4" />

2. 
 - Изменил слово `input` на `output`
   
 - Перешел в конец файл и удалил две последние строки
   
 - Из начала файла в конец перенес `/*Manifests`
   
 - Записал изменения

<img width="796" height="416" alt="image" src="https://github.com/user-attachments/assets/cb439ad5-2822-4383-9367-dae292bde498" />

3. Скопировал из файла `testcase.c` строки с 16 по 29 в файл `printwords.c`

<img width="562" height="275" alt="image" src="https://github.com/user-attachments/assets/56bfe5a7-b780-4227-902f-9bcf556fdff5" />

# Nginx Задача 4:

 1. Состояние демона

 <img width="864" height="395" alt="image" src="https://github.com/user-attachments/assets/bbd5b7a9-804a-426e-9184-4223f3824c28" />

 2. Через `tail` отслеживал ошибки и доступ для наглядности сделал несколько раз curl чтоб появились логи

 <img width="911" height="723" alt="image" src="https://github.com/user-attachments/assets/72173985-d57b-4112-9f0f-a9907e47a2af" />
    
 3. Через `htop` и фильтры нашёл `nginx`и отслеживал нагрузку

 <img width="911" height="723" alt="image" src="https://github.com/user-attachments/assets/87c847b3-2a5c-4edb-bfbf-e6cad8a99810" />

 4. Логи пользователей:
    
   - `/var/log/auth.log` аутентификация и судо
     
   - `/var/log/lastlog` последние входы
     
   - `/var/log/wtmp` история входов и выходов

 <img width="1158" height="721" alt="image" src="https://github.com/user-attachments/assets/7cdc3e20-c289-483e-9ea5-e213a068363b" />


# ACL:
 
 1. 
   - Создал директорию /var/www/server-app

   - Создайл файлы readme.md и app.log

 2. 
   - Создал директорию uploads

   - Создал группы ftpusers, admins, auditors

   - Создал пользователя logger без входа и $HOME /opt/logger
 
 3. С помощью ACL раздал права на директории:

   - Пользователь www-data чтение всей директории

   - Группа ftpusers запись в uploads

   - Группа admins полные права

   - Пользователь logger полные права к файлу app.log

   - Группе auditors чтение app.log

 4. С помощью umask изменил состоние до перезагрузки с 022 на 027.

 5. 

   - Дал возможность входить в систему logger и сделал оболочку

   - Перенаправил окружение в файл /tmp/logger-envs

   - Переключение с полной инициализации окружения и сравнение переменных окружения

 6. Создал от имени logger директорию /tmp/logger-dir из под основного пользователя


