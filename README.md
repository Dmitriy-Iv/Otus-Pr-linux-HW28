# **Введение**

В данном домашнем задании нам необходимо настроить репликацию MySQL (Percona).

---
- Для выполнения данного ДЗ, необходимо скачать стенд и запустить его.

```
git clone https://github.com/Dmitriy-Iv/Otus-Pr-linux-HW28.git
cd Otus-Pr-linux-HW28/
vagrant up
```

В результате у нас будут созданы два виртуальных сервера, с установленными Percona-Server и настроенной реплицацией между ними. Настройки произведены согласно методички и использования ansible модулей для работы с MySQL - community.mysql.mysql_xxxxx. 

- Проверка:

![alt text](/screenshots/master.PNG?raw=true "Screenshot1")  

![alt text](/screenshots/slave.PNG?raw=true "Screenshot2")