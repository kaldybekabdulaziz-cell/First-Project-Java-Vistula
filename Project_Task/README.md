# Task 2 – REST API with Spring Boot

This project is a REST API created using Spring Boot.
All endpoints were tested using Postman and Swagger UI.

---

## Swagger UI
Swagger UI shows all available API endpoints.

![Swagger UI](01.jpg)

---

## Create the Product
A new product is created using Postman.

![Create Product](02.jpg)

---

## Get the Product by ID 
A product is successfully retrieved by its ID.

![Get Product](03.jpg)

---

## Get the Product by ID
An error message is returned when the product does not exist.

![Product Not Found](04.jpg)

---

## Get All the Products
All products are returned as a list.

![Get All Products](05.jpg)

---

## Update the Product
An existing product is updated.

![Update Product](06.jpg)

---

## Delete the Product
A product is deleted by its ID.

![Delete Product](07.jpg)

---

## After the Delete
The product is no longer available after deletion.

![After Delete](08.jpg)

---

### Database Verification

The application was tested using the implemented REST endpoints.
To verify that the operations affected the database correctly, the following SQL query was executed in the H2 Console:

```sql
SELECT * FROM PRODUCTS;
```

![Database View](09.jpg)
