# Proyecto Django con API RESTful - DRF Simple CRUD

## Descripción del Proyecto

Este proyecto es una aplicación web desarrollada con **Django** y **Django Rest Framework (DRF)**, que implementa una API CRUD (Crear, Leer, Actualizar, Eliminar) para gestionar proyectos. Los usuarios pueden realizar las siguientes operaciones sobre los proyectos:

- **Crear** nuevos proyectos especificando un título, descripción y la tecnología utilizada.
- **Obtener** una lista completa de los proyectos almacenados.
- **Actualizar** los detalles de un proyecto existente.
- **Eliminar** un proyecto específico.

La aplicación se conecta a un repositorio en GitHub y luego a una base de datos **PostgreSQL** para el almacenamiento de los proyectos. Está configurada para su despliegue en la plataforma **Render**. Además, se incluyen configuraciones para servir archivos estáticos en producción a través de **Whitenoise**.

### Arquitectura
- **Backend**: Django + Django Rest Framework (DRF)
- **Base de datos**: PostgreSQL
- **Despliegue**: Render
- **Archivos estáticos**: Servidos con Whitenoise

### Endpoints de la API:
- `GET /api/projects/` - Obtener todos los proyectos.
- `GET /api/projects/{id}/` - Obtener un proyecto específico.
- `POST /api/projects/` - Crear un nuevo proyecto.
- `PUT /api/projects/{id}/` - Actualizar los datos de un proyecto.
- `DELETE /api/projects/{id}/` - Eliminar un proyecto.

---

## Tecnologías Utilizadas

- **Django**: Framework web basado en Python para la creación de aplicaciones web.
- **Django Rest Framework (DRF)**: Biblioteca para construir APIs RESTful robustas y escalables.
- **PostgreSQL**: Base de datos relacional usada para almacenar información persistente.
- **Render**: Plataforma en la nube para el despliegue y hosting de aplicaciones web.
- **Whitenoise**: Middleware para servir archivos estáticos eficientemente en producción.
- **dj-database-url**: Utilizado para configurar la base de datos de forma sencilla usando una URL.

---

## Instrucciones para Ejecutar el Proyecto Localmente

Sigue estos pasos para ejecutar el proyecto en tu entorno local.
-ir al cmd (terminal) y ejecutar el siguiente comando **cd desktop, cd DRF**
-se abrira visual studio code y cuando carge seleccionar **si confio en los autores**
-ejecutar el siguiente comando en la terminal de visual studio code para crear los modelos en la base de datos **python manage.py makemigrations**
-despues ejecutar este codigo para enviar los datos del proyecto hacia los modelos creados **python manage.py migrate**
-ahora para cargar el link del proyecto en la terminal se debe indicar el siguiente comando **python manage.py runserver**

link de render: (https://drfsimple-y3at.onrender.com)

