# Домашнее задание к занятию 11 «Teamcity»   

---

### Подготовка к выполнению  

1) В Yandex Cloud создайте новый инстанс (4CPU4RAM) на основе образа jetbrains/teamcity-server.
2) Дождитесь запуска teamcity, выполните первоначальную настройку.
3) Создайте ещё один инстанс (2CPU4RAM) на основе образа jetbrains/teamcity-agent. Пропишите к нему переменную окружения SERVER_URL: "http://<teamcity_url>:8111".
4) Авторизуйте агент.
5) Сделайте fork репозитория.
6) Создайте VM (2CPU4RAM) и запустите playbook.

1-4  В Yandex Cloud создайл новые инстансы (4CPU4RAM) на основе образа jetbrains/teamcity-server и jetbrains/teamcity-agent,
выполнил первоначальную настройку, авторизовал агент:

![image.jpg](https://github.com/Byzgaev-I/Teamcity/blob/main/0-VM%20Yandex.png) 

4) Авторизовал агент

![image.jpg](https://github.com/Byzgaev-I/Teamcity/blob/main/1%20-%20agent.png) 

5) Сделал fork [репозитория](https://github.com/Byzgaev-I/example-teamcity).
6) Создал VM (2CPU4RAM) и запустите [playbook](https://github.com/Byzgaev-I/mnt-homeworks/tree/MNT-video/09-ci-05-teamcity/infrastructure)

![image.jpg](https://github.com/Byzgaev-I/Teamcity/blob/main/1%20Playbook.png) 
