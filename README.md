# lab5-nfs

Установка стенда

Используйте этот Vagrantfile
Что сделано?

    команда vagrant up поднимает 2 виртуалки: сервер и клиент
    на сервере создана и расшарена директория
    одна из поддиректорий upload создана с правами на запись
    выполнены требования для NFS: NFSv3 по UDP, включенный firewall

Cпособ достижения

Фактически все вышеупомянутые действия выполняются скриптом,
содержащим команды для сервера и клиента
