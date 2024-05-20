# WebAPI_QuinonezJackson
DIRECTORIOS

src-main-java:En este directorio, encontrarás las clases Java del proyecto, las cuales están estructuradas en paquetes. Cada paquete está representado por un subdirectorio dentro de este directorio principal. Por ejemplo, si una clase pertenece al paquete com.tuuniversidad.apirest.libro, la encontrarás dentro del subdirectorio com/tuuniversidad/apirest/libro.

resources:En este directorio, se encuentran guardados los recursos estáticos del proyecto, los cuales abarcan una variedad de elementos como archivos de configuración, imágenes utilizadas en la interfaz, así como archivos HTML que definen la estructura y contenido de las páginas web.

target:Dentro de este directorio, se encuentran almacenados los archivos que han sido transformados a un formato ejecutable, los cuales son el resultado del proceso de compilación del proyecto.

![image](https://github.com/iamjackson7/WebAPI_Qui-onezJackson/assets/99736392/06b21aed-60cc-4270-b6be-5487a9ca0fb4)

FUNCIONALIDADES

Puedes obtener información sobre un libro específico mediante el punto final GET /books/{book_id}, donde {book_id} representa el identificador único del libro que deseas consultar. Esta ruta te permite acceder a los detalles de un libro particular según su ID.

Puedes crear un libro nuevo utilizando el punto final POST /books. Esta ruta te ofrece la posibilidad de añadir nuevos libros a la base de datos simulada, permitiéndote ingresar información sobre un libro y almacenarla para su posterior consulta.

SOLICITUD

COntrolador: Encargado de gestionar las peticiones HTTP y dirigirlas hacia los servicios correspondientes.

Repositorio:Describe funciones para interactuar con bases de datos ficticias de libros y ofrece implementaciones que contienen datos precargados para propósitos de prueba.

![image](https://github.com/iamjackson7/WebAPI_Qui-onezJackson/assets/99736392/802ba95a-ea99-42dc-a89b-0ef2d2665dba)
![image](https://github.com/iamjackson7/WebAPI_Qui-onezJackson/assets/99736392/83f883da-3211-4bd6-b89f-9bf1eb55ba3a)
![image](https://github.com/iamjackson7/WebAPI_Qui-onezJackson/assets/99736392/9cd2a7a4-a58e-4ae0-b89c-11cf9dc89cae)

EJECUCIÓN

La aplicación se encuentra configurada para ejecutarse en el puerto 8082, según lo especificado en el archivo application.properties. Para iniciarla como una aplicación Spring Boot convencional, simplemente ejecuta la clase principal LibroApplication. Además, me aseguro que todas las dependencias estén correctamente configuradas y que los servicios necesarios estén en funcionamiento antes de iniciar la aplicación para garantizar un inicio sin problemas.

![image](https://github.com/iamjackson7/WebAPI_Qui-onezJackson/assets/99736392/25fff41b-ee42-4737-bc4a-92fe990b4a14)
![image](https://github.com/iamjackson7/WebAPI_Qui-onezJackson/assets/99736392/c310d98d-2026-43c4-bf3d-d0d13f7f84e0)


