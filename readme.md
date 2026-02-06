mysql> use banking_system;
Database changed
mysql> show tables;
+--------------------------+
| Tables_in_banking_system |
+--------------------------+
| accounts                 |
| user                     |
+--------------------------+
2 rows in set (0.00 sec)

mysql> select * from accounts;
+----------------+-----------+------------------------+-------------+--------------+
| account_number | full_name | email                  | balance     | security_pin |
+----------------+-----------+------------------------+-------------+--------------+
|    12345689789 | Ankit     | ankit23@gmail.com      |    10000.00 | 1234         |
|    22950000001 | Pramit    | pramit22@gmail.com     | 10000000.00 | 2006         |
|    78945612304 | amit      | amit@gmail.com         |    10000.00 | 2468         |
|   898824585621 | Tapan     | tapanpradhan@gmail.com |        0.00 | 1000         |
+----------------+-----------+------------------------+-------------+--------------+
4 rows in set (0.00 sec)

mysql> select * from user;
+-----------+--------------------+----------+
| full_name | email              | password |
+-----------+--------------------+----------+
| pramit    | pramit7@gmail.com  | 1234     |
| swadhin   | swadhin3@gmail.com | 2468     |
+-----------+--------------------+----------+
2 rows in set (0.00 sec)
mysql> select * from accounts;
+----------------+-----------+------------------------+------------+--------------+
| account_number | full_name | email                  | balance    | security_pin |
+----------------+-----------+------------------------+------------+--------------+
|    12345689789 | Ankit     | ankit23@gmail.com      |   10000.00 | 1234         |
|    22950000001 | Pramit    | pramit22@gmail.com     | 9980000.00 | 2006         |
|    78945612304 | amit      | amit@gmail.com         |   10000.00 | 2468         |
|   898824585621 | Tapan     | tapanpradhan@gmail.com |       0.00 | 1000         |
+----------------+-----------+------------------------+------------+--------------+
4 rows in set (0.00 sec)
