
# Challenge ONE | Java | Back-end | Foro Alura

Este proyecto es una API en Java utilizando Spring Boot para un foro de discusión llamado "Foro Alura". La API permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en tópicos y otras entidades relacionadas.

## Funcionalidades

### Registro de un nuevo tópico

La API cuenta con un endpoint para el registro de nuevos tópicos. Se aceptan solicitudes POST en la URI /topicos. Los datos del tópico, como el título, mensaje, autor y curso, deben enviarse en el cuerpo de la solicitud en formato JSON. La API aplica las siguientes reglas de negocio:

- Todos los campos son obligatorios.
- No se permiten registros duplicados con el mismo título y mensaje.

### Lista de tópicos

La API cuenta con un endpoint para obtener la lista de todos los tópicos. Se aceptan solicitudes GET en la URI /topicos. Los datos de cada tópico, incluyendo el título, mensaje, fecha de creación, estado, autor y curso, se devuelven en el cuerpo de la respuesta en formato JSON.

### Detalle de un tópico

La API cuenta con un endpoint para obtener el detalle de un tópico específico. Se aceptan solicitudes GET en la URI /topicos/{id}, donde {id} representa el identificador único del tópico. Los datos del tópico, como el título, mensaje, fecha de creación, estado, autor y curso, se devuelven en el cuerpo de la respuesta en formato JSON.

### Eliminación de un tópico

La API cuenta con un endpoint para eliminar un tópico. Se aceptan solicitudes DELETE en la URI /topicos/{id}, donde {id} representa el identificador único del tópico a eliminar.

Además de estas funcionalidades principales, para completar el foro, sería necesario contar con otros endpoints para crear, listar, actualizar y eliminar otras entidades, como usuarios y respuestas.

## Tecnologías utilizadas

- Java: Lenguaje de programación principal utilizado en el desarrollo de la API REST.
- Spring Boot: Framework de desarrollo de aplicaciones Java que simplifica la creación de aplicaciones basadas en Spring.
- Controladores (Controllers): Se utilizan para manejar las solicitudes HTTP y definir los puntos finales de la API.
- Repositorios (Repositories): Se utilizan para interactuar con la base de datos y realizar operaciones CRUD en los modelos de datos.
- Base de datos: Se utiliza una base de datos (por ejemplo, MySQL, PostgreSQL) para almacenar la información de los tópicos, usuarios, respuestas, etc.


## Demo

https://github.com/MatiasJB95/ForoAlura/assets/115195236/45b4880f-3803-4d81-995d-20f9be51f5ef

## Configuración y ejecución

Para configurar y ejecutar la aplicación:

1. Clona el repositorio en tu máquina local.
2. Configura la base de datos según la base de datos de tu elección.
3. Actualiza la configuración de la base de datos en el archivo de configuración de la aplicación (`application.properties` o `application.yml`).
4. Ejecuta la aplicación utilizando tu IDE preferido o mediante la línea de comandos.
5. Realiza las solicitudes HTTP correspondientes utilizando herramientas como Postman o cURL.



## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matiasjb95/)

https://app.aluracursos.com/emprega-one/profile/matiasss95



![cms_files_10224_1673890737Prancheta_9](https://github.com/MatiasJB95/ForoAlura/assets/115195236/87aecb87-091d-401d-9230-6fefba7880d0)


