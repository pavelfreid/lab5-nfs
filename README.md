# lab5-nfs

Создание стенда

С помощью этого [vagrantfile](https://github.com/pavelfreid/lab5-nfs/blob/main/Vagrantfile) запускаем создание стенда из двух виртуалок nfss и nfsc

В результате работы вагрантf получаем две виртуалки: сервер и клиент
В вагрантфайле имеются ссылки на [скрипта настройки сервера](https://github.com/pavelfreid/lab5-nfs/blob/main/nfss_script.sh) и [скрипта настройки клиента](https://github.com/pavelfreid/lab5-nfs/blob/main/nfsc_script.sh)


С помощью скриптов на сервере расшарена директория (/srv/share), одна из поддиректорий (/srv/share/upload) создана с правами на запись, выполнены требования для NFS: NFSv3 по UDP, включенный firewall

Cпособ достижения

Фактически все вышеупомянутые действия выполняются скриптом,
содержащим команды для сервера и клиента
