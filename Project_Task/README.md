# Task 2 – REST API with Spring Boot

This project is a REST API created using Spring Boot.
All endpoints were tested using Postman and Swagger UI.

---

## Swagger UI
Swagger UI shows all available API endpoints.

!(01.jpg)

---

## Create the Product
A new product is created using Postman.

!(02.jpg)

---

## Get the Product by ID 
A product is successfully retrieved by its ID.

!(03.jpg)

---

## Get the Product by ID
An error message is returned when the product does not exist.

!(04.jpg)

---

## Get All the Products
All products are returned as a list.

!(05.jpg)

---

## Update the Product
An existing product is updated.

![Update Product](06.jpg)

---

## Delete the Product
A product is deleted by its ID.

!(07.jpg)

---

## After the Delete
The product is no longer available after deletion.

!(08.jpg)

---

### Database Verification

The application was tested using the implemented REST endpoints.
To verify that the operations affected the database correctly, the following SQL query was executed in the H2 Console:

```sql
SELECT * FROM PRODUCTS;
```

!(09.jpg)
