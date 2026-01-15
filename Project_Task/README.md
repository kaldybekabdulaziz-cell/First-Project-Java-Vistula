# Task 2 – REST API with Spring Boot

This project is a REST API created using Spring Boot.
All endpoints were tested using Postman and Swagger UI.

---

## Swagger UI
Swagger UI shows all available API endpoints.

![Swagger UI](images/01.jpg)

---

## Create the Product
A new product is created using Postman.

![Create Product](images/02.jpg)

---

## Get the Product by ID 
A product is successfully retrieved by its ID.

![Get Product](images/03.jpg)

---

## Get the Product by ID
An error message is returned when the product does not exist.

![Product Not Found](images/04.jpg)

---

## Get All the Products
All products are returned as a list.

![Get All Products](images/05.jpg)

---

## Update the Product
An existing product is updated.

![Update Product](images/06.jpg)

---

## Delete the Product
A product is deleted by its ID.

![Delete Product](images/07.jpg)

---

## After the Delete
The product is no longer available after deletion.

![After Delete](images/08.jpg)

---

### Database Verification

The application was tested using the implemented REST endpoints.
To verify that the operations affected the database correctly, the following SQL query was executed in the H2 Console:

```sql
SELECT * FROM PRODUCTS;
```

![Database View](images/09.jpg)
