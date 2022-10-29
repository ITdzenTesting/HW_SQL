# SQL

ТАБЛИЦЫ:

I Таблица Customers (КЛИЕНТЫ):
1. CustomerID
2. CustomerName
3. ContactName
4. Address
5. City
6. PostalCode
7. Country

II Таблица Categories (КАТЕГОРИИ):
1. CategoryID
2. CategoryName
3. Description

III Таблица Employees (СОТРУДНИКИ):
1. EmployeeID
2. LastName
3. FirstName
4. BirthDate
5. Photo
6. Notes

IV Таблица OrderDetails (ДЕТАЛИ ЗАКАЗОВ):
1. OrderDetailID
2. OrderID
3. ProductID
4. Quantity

V Таблица Orders (ЗАКАЗЫ):
1. OrderID
2. CustomerID
3. EmployeeID
4. OrderDate
5. ShipperID

VI Таблица Products (ТОВАРЫ):
1. ProductID
2. ProductName
3. SupplierID
4. CategoryID
5. Unit
6. Price

VII Таблица Shippers (ГРУЗООТПРАВИТЕЛИ):
1. ShipperID
2. ShipperName
3. Phone

VIII Таблица Suppliers (ПОСТАВЩИКИ):
1. SupplierID
2. SupplierName
3. ContactName
4. Address
5. City
6. PostalCode
7. Country
8. Phone

Проверить работу sql запросов по таблицам можно на сайте https://www.w3schools.com/sql/default.asp

ЗАДАНИЕ:

Создать .sql файл в котором под каждой командой напишите sql запрос, который выполнит команду.

.sql файл выгружайте на гит и скидывайте ссылки на проверку.

1) Вывести всех клиентов в таблице

2) Вывести только Id клиентов

3) Вывести контактные имена и телефоны поставщиков

4) Вывести только страны поставщиков

5) Вывести имя и почтовый код поставщиков

6) Вывести имя, фамилию и дни рождения сотрудников

7) Вывести клиентов, где в имени есть "Que"

8) Вывести клиентов, где в имени в конце есть "en"

9) Вывести клиентов, где в имени есть буква "w"

10) Вывести заказы, которые были сделаны 1996-12-12

11) Вывести клиента, у которого id равен 87

12) Вывести клиента, у которого id равен 78

13) Вывести клиентов, у которых id больше 80

14) Вывести клиентов, у которых id меньше 80

15) Вывести клиентов, у которых id меньше 20 или больше 70

16) Вывести клиентов, у которых id меньше либо равно 25

17) Вывести клиентов, у которых id больше либо равно 45

18) Вывести клиентов, у которых id больше 70, но меньше 90

19) Вывести клиентов, у которых id между 60 и 91

20) Вывести минимальный id 

21) Вывести максимальный id

22) Вывести количество клиентов
