# Inventory-management-java
This is a Java program for inventory management. It establishes a connection to a MySQL database and provides functionality for both admin and agent users.

For the admin user, it allows adding products to the inventory and viewing the inventory details. The admin can log in with a username and password, and after successful login, they can choose from various options such as adding a product or viewing the existing products.

For the agent user, it allows buying or selling products. The agent can also log in with a username and password and then choose between buying or selling actions. When buying a product, the agent can enter the product details such as ID, name, quantity, and price, which will be added to the inventory. When selling a product, the agent can enter the selling price and quantity to calculate the total.

This program can be used as a starting point for developing a more comprehensive inventory management system. It utilizes JDBC for database connectivity and demonstrates basic CRUD operations (create, read) on the inventory database.
