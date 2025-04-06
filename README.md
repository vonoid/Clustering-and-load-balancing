# Домашнее задание к занятию "`Кластеризация и балансировка нагрузки`" - `Заярченко Иван`


### Задание 1

Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

![Round-robin](https://github.com/vonoid/Clustering-and-load-balancing/blob/9ed477da0cf8e285fe45edb4c987da8f062a2e25/img/11.jpg)

![Round-robin](https://github.com/vonoid/Clustering-and-load-balancing/blob/9ed477da0cf8e285fe45edb4c987da8f062a2e25/img/12.jpg)


---

### Задание 2

Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

![Weighted Round Robin](https://github.com/vonoid/Clustering-and-load-balancing/blob/9ed477da0cf8e285fe45edb4c987da8f062a2e25/img/21.jpg)

![Weighted Round Robin](https://github.com/vonoid/Clustering-and-load-balancing/blob/9ed477da0cf8e285fe45edb4c987da8f062a2e25/img/23.jpg)

![Weighted Round Robin](https://github.com/vonoid/Clustering-and-load-balancing/blob/9ed477da0cf8e285fe45edb4c987da8f062a2e25/img/22.jpg)
