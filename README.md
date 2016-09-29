# mysqljavaconnectivity
It performs CRUD operations on MYSQL using java JDBC driver.


1
Steps Required using JDBC:
Import the packages:
Requires that you include the packages containing the
JDBC classes needed for database programming .Most
often,using imporjava:sql:* will suffice.

2
Register the JDBC driver:
Requires that you initialize a driver so you can open a
communication channel with the database.

3
Open a connection:
Requires using the DriverManager:getConnection() method
to create a Connection object, which represents a phys-
ical connection with database server. To create a new
database, you need not to g ive any database name while
preparing database URL as mentioned in the below ex-
ample.

4
Execute a query:
Requires using an object of type Statement for building
and submitting an SQL statement to the database.

5
Clean up the environment:
Requires explicitly closing all database resources versus
relying on the JVM’s garbage collection.
