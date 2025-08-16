# Домашнее задание к занятию «ELK»
Иванов Владислав


### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

---

### Задание 4. Filebeat

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*



### Решение


### Задание 1. Elasticsearch 

Скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch
<img width="666" height="394" alt="image" src="https://github.com/user-attachments/assets/299849fb-73d0-479e-a642-c965ec12c562" />


### Задание 2. Kibana

Скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty
<img width="1835" height="908" alt="image" src="https://github.com/user-attachments/assets/c6904f43-b8bc-44b8-be6c-bd1db2220616" />


### Задание 3. Logstash

Скриншот интерфейса Kibana, на котором видны логи Nginx
<img width="1064" height="426" alt="image" src="https://github.com/user-attachments/assets/24af4ac2-18ed-4cc9-922c-14d9f8b0ef52" />


### Задание 4. Filebeat

Скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat
<img width="1511" height="644" alt="image" src="https://github.com/user-attachments/assets/0e4ea9e5-103d-4e04-b00a-1ccc864684ba" />
<img width="1511" height="653" alt="image" src="https://github.com/user-attachments/assets/7c7db9cb-51c1-4278-9c7d-c1f52485f7cd" />
