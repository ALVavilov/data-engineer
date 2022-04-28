1. Качество данных.
Данные в витринах без аномалий, все типы верные.
Были проверенны данные на выбросы с помощью min(), max() по числовым полям и полям с датами.

2. Были созданы представления в счеме analysis.
- analysis.orderitems
- analysis.orders
- analysis.orderstatuses
- analysis.orderstatuslog
- analysis.products 
- analysis.users

3. Создание и заполнение таблицы analysis.dm_rfm_segments
При создание использовалась только одна витрина analysis.orders, т.к. в ней имеются все необходимые поля.

4. Доработка представления.
В связи с тем, что в витрине analysis.orders убрали поле status, потребовалось изменение представления.
Данные для поля status были взяты из таблицы production.orderstatuslog 
