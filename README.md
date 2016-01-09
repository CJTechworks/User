# User

1. Create database customer_db.
2. Create the following table inside the db

CREATE TABLE Customer(
   CUSTOMER_ID   INT NOT NULL AUTO_INCREMENT,
   NAME VARCHAR(150) NOT NULL,
   ADDRESS1 VARCHAR(150),
   ADDRESS2 VARCHAR(150),
   ZIP_CODE VARCHAR(10),
   CITY VARCHAR(100),
   COUNTRY VARCHAR(100),
   PRIMARY KEY (CUSTOMER_ID)
)

3.Update  Servlet-context.xml with my sql specific  properties

4. Create Customer -- > Run CreateCustomerTest.java
5. List Customer  -- > http://localhost:8080/mySpringWeb/accounts
6. Update Customer --> Run UpdateCustomerTest.java
7. Delete Customer -- >Run DeleteCustomerTest.java
8. Get a particular Customer -- > http://localhost:8080/mySpringWeb/accounts/7
