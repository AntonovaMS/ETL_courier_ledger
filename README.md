# ETL_courier_ledger

### Описание проекта
ETL для сервиса доставки еды. Требуется реализовать витрину для расчётов заработной платы курьеров за предыдущий месяц. 

### Навыки и инструменты
* Airflow DAG
* Python : requests ,парсинг json
* SQL : агрегатные функции, подзапросы, джоины, merge

### Общий вывод
ETL-процесс реализован:
- выгрузка данный из API по странично 
- заполнение таблиц staging-слоя данными формата JSON
- инкрементарная загрузка данных из Staging-слоя в слой DDS и заполнение витрины в слое CDM




