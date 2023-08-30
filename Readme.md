Дипломное задание по курсу «JavaScript-программирование для начинающих»
Создание «информационной системы для предварительного бронирования билетов».
Студенту предоставляются следующие компоненты системы:
Верстка
Backend
Задача
Разработать сайт бронирования билетов онлайн
Сущности
Кинозал Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал — прямоугольный, состоит из N*M различных зрительских мест.

Зрительское место Место в кинозале. Зрительские места могут быть VIP и обычные.

Фильм Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.

Сеанс Сеанс — это временной промежуток, в котором в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.

Билет QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс. Билет действителен строго на свой сеанс. Для генерации QR-кода можно использовать QRCreator.js

Роли пользователей системы
Гость — неавторизованный посетитель сайта
Возможности гостя
просмотр расписания
просмотр информации о фильмах
выбор места в кинозале
бронирование билета

Реализация проекта
Адаптирована исходная верстка под планшетные и мобильные устройства. Верстка корректно отображается на устройствах с шириной экрана 320px и более.
Разработана API для взаимодействия с Backend.
Получение списков всех залов, кинофильмов и сеансов
Получение актуальной схемы посадочных мест на выбранный сеанс
Заказ билета
Запрограммирована гостевая часть сайта
Стек технологий

В проекте использовались следующие технологии:
HTML
CSS (включая медиазапросы)
JavaScript
Git
Сторонние библиотеки
QRCreator.js - JavaScript библиотека для создания QR-кодов.

GitHub Pages
Проект доступен на GitHub Pages по следующей ссылке: https://nadiaruss.github.io/js-cp-dipoma/

Задание
Исходный проект задания: https://github.com/VladaIsakova/js-cp-diploma-edited/