# NFS_FURSE_23
Описание/Пошаговая инструкция выполнения домашнего задания:

Для выполнения домашнего задания используйте методичку
Vagrant стенд для NFS https://docs.google.com/document/d/1Xz7dCWSzaM8Q0VzBt78K3emh7zlNX3C-Q27B6UuVexI/edit?usp=sharing

    vagrant up должен поднимать 2 виртуалки: сервер и клиент;
    на сервер должна быть расшарена директория;
    на клиента она должна автоматически монтироваться при старте (fstab или autofs);
    в шаре должна быть папка upload с правами на запись;
    требования для NFS: NFSv3 по UDP, включенный firewall.
