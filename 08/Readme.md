# Домашнее задание к занятию "Работа с БД"

### Цель задания

В результате выполнения этого задания вы научитесь формировать запросы к БД при помощи QSqlQueryModel и QSqlTableModel, а также отображать полученные данные на форме приложения. 

------

### Инструкция к заданию

1. Скачать проект с прекодом.
2. Добавить в CmakeList.txt модуль для работы с БД.
3. Подключить в CmakeList.txt библиотеки из папки PG_Libs к проекту.
4. Заменить на главной форме виджет QTableWidget, на необходимый для выполнения задания.
5. Изменить существующие или добавить новые методы, необходимые для выполнения задания.
6. Допускается добавить данные для подключения в конструктор DbData.

##### Данные для подключения к БД

* Имя хоста:
* Имя БД: *postgres*
* Порт:
* Логин: *netology*
* Пароль:

##### Описание таблицы БД

Для выполнения работы необходимо получить данные из таблицы под названием "film", которая состояит из 14 столбцов:

1. film_id - ИД записи;
2. title - название фильма;
3. description - описание фильма;
4. release_year - год выпуска;
5. language_id - язык фильма, внешний ключ(ВК)
6. original_language_id - оригинальный язык фильма, ВК
7. rental_duration - доступная продолжительность аренды фильма, дней;
8. rental_rate - цена в $ за день;
9. length - продолжительность фильма, мин;
10. replacement_cost - цена замены фильма;
11. rating - возрастной рейтинг фильма;
12. last_update - служебная информация, последнее одновление записи;
13. special_features - дополнительные особенности фильма;
14. fulltext - ключевые слова для поиска фильма.
------

### Задание 1. 

1. Реализовать получение всех фильмов(в фильтре на главной форме выбрано значение "все" ) из БД при помощи объекта класса QSqlTableModel.
2. Реобходимо реализовать получение комедий и ужасов из БД при помощи объекта класса QSqlQueryModel.
3. В таблице на главной форме должны отображаться:
   * Столбцы "Название фильма" и "Описание фильма".
   * Присутствовать заголовки столбцов.
4. При нажатии на кнопку "Очистить" таблица должна очищаться.

------

### Правила приема работы

1. Отправлена ссылка на репозиторий с кодом ДЗ

------

### Критерий зачета

* Реализованы механизмы получения фильмов при помощи объектов класса QSqlTableModel и QSqlQueryModel.
* Программа работает стабильно.
* Выполняются все требования из задания.


