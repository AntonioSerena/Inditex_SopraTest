# Sopra test for Inditex: Spring Boot H2  

* Java 17
* Spring Boot 3.1
* JPA H2 database console:  http://localhost:8080/h2-console
* JUnit Jupiter API tests
* Maven 3.3.1
* Podrian utilizarse librerias tipo Lombok para un caso no tan sencillo 

# POSTMAN
0. GET http://localhost:8080/api
1. GET http://localhost:8080/api/allPrices
2. GET http://localhost:8080/api/price, Body:  
   {
   "applicationDate" : "2020-06-15T10:00:00",
   "productId": "35455",
   "brandId": 1
   }
