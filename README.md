# Домашнее задание к занятию `15 «Система сбора логов Elastic Stack»` - Пугач Евгений.


---

## `Задание 1`

Вам необходимо поднять в докере и связать между собой:

- elasticsearch (hot и warm ноды);
- logstash;
- kibana;
- filebeat.

В директории help находится манифест docker-compose и конфигурации filebeat/logstash для быстрого  
выполнения этого задания.

Результатом выполнения задания должны быть:

- скриншот docker ps через 5 минут после старта всех контейнеров (их должно быть 5);
- скриншот интерфейса kibana.

### Ответ:

`docker ps`

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2024-02-26_00-27-09.png)
---

`интерфейс kibana`

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2024-03-03_16-14-17.png)

---


## `Задание 2`

Перейдите в меню создания index-patterns в kibana и создайте несколько index-patterns из имеющихся.

### Ответ:

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2024-03-03_16-02-20.png)

Перейдите в меню просмотра логов в kibana (Discover) и самостоятельно изучите, как отображаются логи и  
как производить поиск по логам.

В манифесте директории help также приведенно dummy-приложение, которое генерирует рандомные события  
в stdout-контейнера. Эти логи должны порождать индекс logstash-* в elasticsearch.

### Ответ:

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2024-03-03_15-56-37.png)

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2024-03-03_16-10-21.png)

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2024-03-03_16-11-00.png)

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2024-03-03_16-12-21.png)

---

