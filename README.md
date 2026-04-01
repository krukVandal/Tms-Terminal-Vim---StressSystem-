<img width="1052" height="409" alt="image" src="https://github.com/user-attachments/assets/bbbd6ced-76ff-4fb0-a20f-b32e2a73ac11" /># Vim Задача 1: 

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

 <img width="1159" height="300" alt="image" src="https://github.com/user-attachments/assets/78883383-9ad6-4361-adb0-f84802053041" />

 4. Логи пользователей:
    
   - `/var/log/auth.log` аутентификация и судо
     
   - `/var/log/lastlog` последние входы
     
   - `/var/log/wtmp` история входов и выходов

 <img width="1158" height="721" alt="image" src="https://github.com/user-attachments/assets/7cdc3e20-c289-483e-9ea5-e213a068363b" />


# ACL:
 
 1. 
   - Создал директорию `/var/www/server-app`

   - Создайл файлы `readme.md` и `app.log`

 2. 
   - Создал директорию `uploads`

   - Создал группы `ftpusers, admins, auditors`

   - Создал пользователя `logger` без входа и директорию домашнюю `/opt/logger`

 <img width="938" height="366" alt="image" src="https://github.com/user-attachments/assets/ab2f1dc6-ff33-4c97-84cd-06bd1c76a901" />

 
 3. С помощью ACL раздал права на директории:

   - Пользователь `www-data` чтение всей директории

   - Группа `ftpusers` запись в `uploads`

   - Группа `admins` полные права

   - Пользователь `logger` полные права к файлу `app.log`

   - Группе `auditors` чтение `app.log`

 <img width="1068" height="764" alt="image" src="https://github.com/user-attachments/assets/1ad16823-2e45-42b6-96ec-26c64283b15d" />

 4. С помощью `umask` изменил состоние до перезагрузки с 022 на 027 и создал папку и файл в соответсвии с заданием.
 
 <img width="1052" height="409" alt="image" src="https://github.com/user-attachments/assets/616a76f4-68cd-45d8-9fda-2b14fcbcf2e2" />

 5.
   - Дал возможность входить в систему `logger` и сделал оболочку

   - Перенаправил окружение в файл `/tmp/logger-envs`

   - Переключение с полной инициализацией окружения и сравнение переменных окружения

 <img width="1104" height="735" alt="image" src="https://github.com/user-attachments/assets/ee778f2c-9354-4f47-9833-9defff7e80c6" />

 6. Создал от имени `logger` директорию `/tmp/logger-dir` из под основного пользователя

 <img width="989" height="407" alt="image" src="https://github.com/user-attachments/assets/3e99dc2f-3cc2-41a8-a8c2-2abc676c37eb" />

# System-Stress:

 1. С помощью top определил `load average`

 <img width="1212" height="333" alt="image" src="https://github.com/user-attachments/assets/1c13804c-3b25-43b7-9218-85ca450e6167" />

 2. Запустил `stress-ng`

 <img width="1206" height="629" alt="image" src="https://github.com/user-attachments/assets/166578c8-deba-4352-8693-4f6d771ed8c6" />

 3. Запустил `dstat` и `mpstat` мониторил нагрузку

 <img width="1184" height="722" alt="image" src="https://github.com/user-attachments/assets/dc9b6237-c0a2-4eb2-98f5-544aa13ab339" />

 4. Отыскал нагрузку с помощью `iostat dx 1`

 <img width="1226" height="395" alt="image" src="https://github.com/user-attachments/assets/88798c13-93df-464f-a87f-f4db74a1e8ec" />

 5. Запустил еще раз `stress-ng` и добавил два снимка из лога с разницей с нагрузкой и без нагрузки в `atop` и приложил скриншот `sar` 
  - `atop -r /var/log/atop/atop_20260401 -b 13:12 -e 13:54`

 <img width="1210" height="679" alt="image" src="https://github.com/user-attachments/assets/ad2f2c59-5d59-4926-917c-90f93cc7a14e" />

 <img width="1211" height="674" alt="image" src="https://github.com/user-attachments/assets/d5dedd00-5a46-4d21-8a0c-d1587155d565" />

 <img width="1210" height="270" alt="image" src="https://github.com/user-attachments/assets/4d0c2ffa-29b0-484e-a8a9-23073584119b" />

 6. Вывел `openssl`
  - `pidstat -G openssl`

 <img width="981" height="154" alt="image" src="https://github.com/user-attachments/assets/f61aba5c-a2d1-49df-8a04-10a874492085" />

 7. Для вывова время выполнения и потребления памяти
  - `/usr/bin/time -f "Real: %e s, User: %U s, Sys: %S s, MaxMem: %M KB" sh -c "sleep 5; ls -R /usr"`

 <img width="510" height="51" alt="image" src="https://github.com/user-attachments/assets/02bf14ee-a74a-4143-b1f8-1d7380171ea9" />

 8. Параметры вывовил по одному через флаг `-o` 

 <img width="625" height="456" alt="image" src="https://github.com/user-attachments/assets/bf97f01f-bec0-4072-a3c3-cd62bde8b74a" />

