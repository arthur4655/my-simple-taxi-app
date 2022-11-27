# 🚕Simple-taxi-app🚕
<h2>📣 Project description 📣</h2>
It's simple web-application that supports CRUD operations and registration with authorization.
This project follows SOLID and also build according to N-tier architecture patterns.
Here we have 4 layers: GUI, business layer, persistence layer, database layer

## <h2>📝Features</h2>
* Registration as a driver
* Authentication as a driver
* Authenticated driver can perform CRUD operations over manufacturers/cars/drivers
* Supports display of all cars that belong to current driver
* Displays all manufacturers/drivers/cars
* Logout option

## <h2>📚Project structure</h2>
<p>💠The GUI layer is represented by jsp pages</p>
<p>💠Controllers are main components of business layer and responsible for working with HTTP methods</p>
<p>💠DAO classes represent persistence layer and responsible for CRUD operations with database entities</p>

## <h2>🌐Technologies</h2>
* JDK 11
* Maven 4.0
* Java Servlet API 4.0.1
* JDBC
* Jakarta Server Pages
* MySQL 8.0.22
* TomCat 9.0.68

## <h2>🚀Instructions for launching the project</h2>
<h4>To run this project locally, follow these steps:</h4>

1️⃣ You should install TomCat version 9 and MySQL

2️⃣  Clone this project from GitHub

3️⃣  Run query from init_db to create local database schema

4️⃣  Configure ConnectionUtil class in util package

5️⃣  Configure TomCat for this project and run it
