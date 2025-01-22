📖 Descripción del Proyecto
Este repositorio contiene la solución al Challenge - Foro Alura, desarrollado utilizando Java 17 y Spring Boot para la creación de una API Rest, MySQL para la persistencia de datos, y herramientas como IntelliJ IDEA e Insomnia para pruebas y desarrollo. Este desafío es parte del programa Oracle Next Education (ONE) de Oracle + Alura LATAM.

El objetivo principal del reto fue implementar una API Rest siguiendo las mejores prácticas, validaciones de negocio y un modelo eficiente para gestionar la persistencia de información en una base de datos relacional.

🛠️ Funcionalidades
Nuestra API permite gestionar tópicos en el foro, ofreciendo las siguientes funcionalidades:

Crear un nuevo tópico 📝
Listar todos los tópicos creados 📋
Visualizar un tópico específico 🔍
Actualizar un tópico existente ✏️
Eliminar un tópico ❌
Rutas implementadas según las mejores prácticas del modelo Rest 🔗
Validaciones según reglas de negocio ✅
Base de datos relacional para persistencia 🗄️
🎯 Historia del Proyecto
El Foro Alura es un espacio donde estudiantes, profesores y moderadores interactúan resolviendo dudas y compartiendo conocimientos. Este desafío consiste en replicar la funcionalidad del foro a nivel Back End, implementando una API Rest que maneje la lógica y el almacenamiento de datos de los tópicos y sus relaciones con los usuarios.

Con este proyecto, se busca entender cómo funcionan los procesos internos del foro: desde cómo se almacena y relaciona la información hasta cómo se manejan las respuestas de usuarios.

🚀 Comenzando
Sigue estas instrucciones para obtener una copia funcional del proyecto en tu máquina para desarrollo o pruebas.

📋 Requisitos previos
Instalar Java 17
Descárgalo desde Oracle o tu gestor de paquetes preferido.

Instalar MySQL
Configura una base de datos local con credenciales de acceso.

Instalar Maven
Verifica que esté instalado ejecutando mvn -v en tu terminal.


🔧 Instalación
Configura el archivo application.properties
Ajusta las credenciales de tu base de datos en la configuración.

Ejemplo:

spring.datasource.url=jdbc:mysql://localhost:3306/foro_alura
spring.datasource.username=root
spring.datasource.password=admin
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.format-sql=true
Compila y ejecuta el proyecto


Pruebas de la API
Utiliza herramientas como Insomnia o Postman para probar las rutas de la API.

🛠️ Tecnologías Utilizadas
Java 17: Lenguaje principal.
Spring Boot 3.1.0: Framework para la construcción de APIs Rest.
MySQL: Sistema de gestión de bases de datos.
IntelliJ IDEA: IDE para desarrollo.
Insomnia: Herramienta para pruebas de API.

📬 Contacto
Si tienes preguntas o deseas colaborar, no dudes en contactarme:

LinkedIn
GitHub

Este proyecto representa un gran paso en el desarrollo backend profesional. ¡Espero que lo disfrutes! 🚀
