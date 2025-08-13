1. We created two tables — Customers and Orders.


2. Customers table stores customer id, name, and city.


3. Orders table stores order id, customer id, product, and amount.


4. We inserted sample data into both tables, including one order with a customer id that does not exist in Customers.


5. INNER JOIN shows only the rows where a customer has a matching order.


6. LEFT JOIN shows all customers, and their orders if available. Customers without orders show NULL in the order columns.


7. RIGHT JOIN shows all orders, and their customers if available. Orders without customers show NULL in the customer columns.


8. FULL OUTER JOIN shows all customers and all orders, matching where possible. If there is no match, the missing side shows NULL.


9. MySQL does not support FULL OUTER JOIN directly — we use a UNION of LEFT JOIN and RIGHT JOIN to get the same result.
