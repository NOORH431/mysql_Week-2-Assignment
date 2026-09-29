# mysql_Week-2-Assignment
q1.
USE sales;
SELECT checkNumber,
       paymentDate,
       amount
FROM payments;

q2.
SELECT orderDate, requiredDate, status 
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;

q3.
SELECT firstName, lastName, email 
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;

q4.
SELECT * 
FROM offices;

q5.
SELECT productName, quantityInStock 
FROM products
ORDER BY buyPrice ASC;
LIMIT 5;
