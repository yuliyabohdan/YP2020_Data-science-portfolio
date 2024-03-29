## Описание проекта

Вы аналитик российской авиакомпании F9, выполняющей внутренние пассажирские перевозки. Важно понять предпочтения пользователей, покупающих билеты на разные направления.

Вам предстоит изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие культурные фестивали.

#### Аналитика средствами Python

У вас есть файлы, в которых содержатся результаты запросов (полученные с помощью SQL).

query_1.csv — результат первого запроса. В нём содержится такая информация:
model — **модель самолета;
flights_amount — количество рейсов для каждой модели самолетов model в сентябре 2018 года.
query_3.csv — результат третьего запроса. В нём содержится такая информация:
city — город;
average_flights — среднее количество рейсов, прибывающих в город (city) за день в сентябре 2018 года.

Для этих двух наборов данных нужно:
выбрать топ-10 городов по количеству рейсов;
построить графики: модели самолётов и количество рейсов, города и количество рейсов, топ-10 городов и количество рейсов;
сделать выводы по каждому из графиков, пояснить результат.

#### Проверка гипотезы средствами Python

query_last.csv — результат последнего запроса. В нём следующая информация:

week_number — **номер недели;
ticket_amount — количество проданных билетов за неделю;
festival_week — есть ли на этой неделе фестиваль;
festival_name — название фестиваля.

Проверьте гипотезу: «Средний спрос на билеты во время фестивалей не отличается от среднего спроса на билеты в обычное время».

Поясните:

Как вы формулировали нулевую и альтернативную гипотезы;
Какой критерий использовали для проверки гипотез и почему.

Используемые библиотеки: pandas, matplotlib, scipy, numpy.
