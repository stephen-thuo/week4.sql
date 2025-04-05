Question 1:SELECT
    paymentDate,
    SUM(amount) AS total_amount_paid
FROM
    payments
GROUP BY
    paymentDate
ORDER BY
    paymentDate DESC
LIMIT 5;
Question 2:SELECT
    c.customerName,
    c.country,
    AVG(c.creditLimit) AS average_credit_limit
FROM
    customers c
GROUP BY
    c.customerName,
    c.country;
Question 3:SELECT
    od.productCode,
    od.quantityOrdered,
    SUM(od.priceEach * od.quantityOrdered) AS total_price
FROM
    orderdetails od
GROUP BY
    od.productCode,
    od.quantityOrdered;
Question 4:SELECT
    checkNumber,
    MAX(amount) AS highest_payment_amount
FROM
    payments
GROUP BY
    checkNumber;
