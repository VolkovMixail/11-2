# Домашнее задание к занятию «Кеширование Redis/memcached»

---

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*
#### Кеширование — это механизм повышения производительности любого типа приложений. Технически кеширование — это процесс хранения и доступа к данным из кеша. Но подождите, что такое кеш? Кеш — это программный или аппаратный компонент, предназначенный для хранения данных, будущие запросы на которые могли бы обслуживаться быстрее.
---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

![](https://github.com/VolkovMixail/11-2/blob/main/imj/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-05-08%20%D0%B2%2008.33.07.png)
---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

![](https://github.com/VolkovMixail/11-2/blob/main/imj/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-05-08%20%D0%B2%2009.02.52.png)
---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

![](https://github.com/VolkovMixail/11-2/blob/main/imj/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-05-08%20%D0%B2%2009.15.51.png)

