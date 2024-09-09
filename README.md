# SQLQUERYGENERATOR

## descripción

        **sqlQueryGenerator**
        es una aplicaicón web que facilita la creación de consultas **SQL** de manera sencilla e intuitiva. La aplicación soporta múltiples gestores de bases de dabtos, tanto relacionales como norelacioinales, y ofrece una interfaz interactiva y moderna diseñada bajo la filosofia **mobile first.**

## Tecnologías Utilizadas

### Frontend

        **React:** 
        modelo atómico de responsabilidad, diseño accesible y mobile-first.

### Backend

    PHP patron **MVC**.

### CSS Framework

    Bootstrap 5.3.3;

### BBDD Soportadas

        **Relacionales:** MySQL,PHPMyAdmin,MariaDB,SQLite3,Oracle,PostgreSQL.
        **NoSQL:** MongoDB, Cassandra, Redis, ElasticSearch, DynamoDB.
        **Multimodelo:** ArangoDB, CouchBase.
        **Distribuidas:** CockroachDB, TiDB.
        **Grafos:** Noe4j.
        **En la nube:** Amazon RDS, Azure SQL Database, Google Cloud SQL.

## Esctructura de la App

### HEADER

        Logo de la marca a la izquierda. 
        Titulo centrado: **sqlQueryGenerator.**
        Menú hamburguesa con las siguientes opciones:
                Registro
                Login
                Documentación
                Learn
                About
                Contacto

## MAIN

        __Slider de Imágenes:__
        Navegación interactiva entre distintos gestores de bases de datos.
        **Descripción Dinámica:** 
        Texto descriptivo del gestor mostrado en el Slider.

## FOOTER

        Botones a redes sociales(Blog, Wordpress, Github, etc..)
        Simbolo de copyright y nombre del creador en el centro.
        Flecha flotante hacia arriba visible tras el scroll de 150px.

## Instalación

### Prerrequisitos

        Node.js y npm > para gestionar dependencias de React.
        Servidor Apache o Nginx con soporte PHP.
        Base de datos MySQL u otro gestor compatible.

## Pasos para la instalación

    1. Clona el repositorio.
        `git clone https://github.com/twinkm/sqlQueryGenerator.git`
    2. Instala las dependencias del frontend.
        `cd sqlQueryGenerator/frontend`
        `npm install`
    3. Configure el backend.
        Crea una BBDD MySQL.
        Edita el archivo **config.php** en el directorio **backend** para añadir tus credenciales de BBDD.

## Inicia la aplicación

        Frontend:
            `npm start`
        Backend: 
            consfigura tu servidor web para que apunte al directorio backend.

## Uso

        1. accede a la página principal de la aplicación.
        2. Navega por el Slider para ver los diferentes gestores de datos.
        3. Registrese o inicie sesion para acceder a las funcionalidades avanzadas.
        4. Usa el generador SQL para generar consultas de manera interactiva.

## Contribuciones

        **Si deseas contribuir al proyecto, por favor sigue las siguientes pautas:**

        1. Haz fork del repositorio.
        2. Crea una nueva rama:
        `git checkout -b feature/nueva-funcionalidad`.
        3. Realize cambios y haz commit:
        `git commit -am 'Añadir nueva funcionalidad`.
        4. Haz push a la rama:
        `git push origin feauture/nueva-funcionalidad`.
        5. abre pull request.

## Licencia

        Este proyecto está bajo la licencia MIT.

## Contacto

        Creador: David De La Puente Enriquez.
        Correo Electronico: [ddelapuenteenriquez@gmail.com](ddelapuenteenriquez@gmail.com)
        LinkedIn: [linkedin.com/in/daviddelapuente/](https://linkedin.com/in/daviddelapuente/)
        GitHub: [github.com/twinkym](https://github.com/twinkym)

## CAPTURAS DE PANTALLA

![/img/capturas-sql/bbdd-creada-con-sustablas](/img/capturas-sql/bbdd-CREADA-CON-SUS-TABLAS.webp)

## VIDEO DEMOSTRACION

![Video demostración de sentencias SQL explicado a mi compi](https://youtu.be/hO0FF6_6Vc0?si=leK86GB77ZgGXLK3)
