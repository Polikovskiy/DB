Результатом практического задания будут три SQL-файла с наборами стейтментов, правильно выполняющих указанные ниже действия.
Начиная с пункта 5, следует при работе с данными постоянно проверять select-ами результаты своих трудов. Писать эти селекты (а тем более, результаты их выполнения) в файл не следует.

Реализовать наборы стейтментов для SQLite, MySQL, PostgreSQL. Наборы стейтментов могут слегка отличаться. Некоторые из пунктов невозможно выполнить в некоторых из перечисленных СУБД. В таком случае, их в файле следует пропустить с комментарием "N/A".

1. Создать базу данных shop.
2. Создать юзера shop и дать ему полный доступ к БД shop.
3. Создать юзера viewer и дать ему доступ на чтение БД shop.
4. Создать таблицу для хранения категорий (хранить название).
5. Добавить несколько категорий.
6. Создать таблицу для хранения товаров (название, категория, цена).
7. Внести несколько товаров по цене 1.00
8. Обновить цену первого товара — 3.50
9. Увеличить цену всех товаров на 10%.
10. Удалить товар № 2.
11. Выбрать все товары с сортировкой по названию.
12. Выбрать все товары с сортировкой по убыванию цены.
13. Выбрать 3 самых дорогих товара.
14. Выбрать 3 самых дешевых товара.
15. Выбрать вторую тройку самых дорогих товаров (с 4 по 6).
16. Выбрать наименование самого дорогого товара.
17. Выбрать наименование самого дешевого товара.
18. Выбрать количество всех товаров.
19. Выбрать среднюю цену всех товаров.
20. Создать представление (create view) с отображением 3 самых дорогих товаров.