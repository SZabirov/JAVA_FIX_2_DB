1. Скачать и установить: [PostgreSQL 10](https://www.postgresql.org/download/).
На всякий случай, [инструкция для windows](http://www.postgresqltutorial.com/install-postgresql/)
2. После установки запускаем pgAdmin 4, создаем новую 
базу данных для работы ([инструкция по pgAdmin 4](https://metanit.com/sql/postgresql/1.3.php)). 
3. В новой базе данных напишите необходимые таблицы для
хранения информации о сотрудниках некоторой организации. 
Каждый сотрудник работает в некотором отделе. У каждого
сотрудника есть должность. У каждого отдела есть начальник.
Остальные требования на ваше усмотрение. В таблицах
предусмотрите необходимые на ваш взгляд ограничения.
4. Заполните таблицы данными и напишите несколько запросов
для выборки данных с различными условиями в `WHERE`.
Например, 
    - для получения сотрудников, старше 65 лет;
    - для получения сотрудников, которые не работают в 
    конкретном отделе
    - любой на ваше усмотрение.