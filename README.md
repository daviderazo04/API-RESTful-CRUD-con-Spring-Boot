# API RESTful CRUD de Productos con Spring Boot

Aplicación para gestionar productos mediante operaciones CRUD (Create, Read, Update, Delete) usando Spring Boot, MySQL y JPA.

## Descripción

API diseñada para gestionar un catálogo de productos con funcionalidades CRUD, permitiendo la creación, visualización, edición y eliminación de productos.

## Endpoints

| **Método**  | **URL**                   | **Descripción**                |
|-------------|---------------------------|---------------------------------|
| **GET**     | <ins>/api/products</ins>       | Obtener todos los productos     |
| **GET**     | <ins>/api/products/{id}</ins>  | Obtener producto por ID         |
| **POST**    | <ins>/api/products</ins>       | Crear un nuevo producto         |
| **PUT**     | <ins>/api/products/{id}</ins>  | Actualizar un producto          |
| **DELETE**  | <ins>/api/products/{id}</ins>  | Eliminar un producto            | 

> [!TIP]  
> Te invito a ver este video corto del funcionamiento de la API

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/db_jpa_crud
spring.datasource.username=root
spring.datasource.password=sasa1234
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect
spring.jpa.show-sql=true
