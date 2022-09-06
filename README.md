# JPA
API Documentation
A. Create Product
POST http://localhost:8080/api/products/
Body 
    { 
    "name":"Betadine",
    "medicinetype" :"bebas",
    "price" : 1000,
    "stocks" : 23
    }
B. Get All Products
GET http://localhost:8080/api/products/

C. Get A Product
GET http://localhost:8080/api/products/{id}

D. Delete all Product
DELETE http://localhost:8080/api/products/
    
E. Delete a Product
DELETE http://localhost:8080/api/products/{id}
