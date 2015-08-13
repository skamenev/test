
## Инструкция по установке legislation v0.1.0
* Создать виртуальный хост для домена `http://legislation{.*}.bunet.biz`
* Скопировать содержимое каталога `www` в корневой каталог сайта
* Отредактировать в файле {корневой_каталог_сайта}/.env, параметры доступа к API "закон", где: 
 


 
        LEGISLATION_CLIENT_ID=login
        LEGISLATION_PASSWORD=password 

    * на площадке alpha: 

            server:login: test_law4
            password: df949DD9s04

    * на площадке beta:
 
            login: test_law5
            password: df84573hsdhJD

    * на площадке rc:

            login: test_law6
            password: Jjdfj7848Kkdkf

    * на площадке production:

            login: test_law3
            password: 23Kdksl234lsdf

* Выполнить скрипт `{корневой_каталог_сайта}/legperm.sh`, при необходимости заменив переменную «lpath=» на выбраный путь инсталляции сервиса legislation.
