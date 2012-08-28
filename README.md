Создание проекта готового к работе
=====

Одной коммандой в терминале создаем проект готовый к работе
$ vhc projectname.local
Создаются виртуальный хост с доменом projectname.local доступным из браузера, структура папок и файлы для Netbeans проекта.

установка скрипта

\# cd /var/tmp/
\# git clone https://github.com/web36m/VHC.git
\# sudo cp ./VHC/vhc /usr/bin/
\# rm -r ./VHC
\# chmod +x /usr/bin/vhc
