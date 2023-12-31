# Proyecto Blog Videojuegos

Este es el repositorio del proyecto Blog Videojuegos, una aplicación web para compartir blogs sobre videojuegos. Permite a los usuarios registrados crear y compartir blogs, así como valorar y comentar los blogs de otros usuarios.

Link al video demostracion 3min: https://drive.google.com/file/d/1DZEIcov_-I8bNDHPQAQ7Z6QUhCgqx7VI/view?usp=sharing

## Características

- Registro de usuarios
- Inicio de sesión y cierre de sesión
- Creación, edición, busqueda y eliminación de blogs(solo el usuario creador)
- Valoración de blogs por parte de los usuarios
- Comentarios en los blogs
- Sistema de mensajeria completo entre usuarios
- Creacion, edicion y eliminacion (admin) de perfiles.
- Página "Acerca de mí" personalizada
- Interfaz de administración para gestionar la aplicación y los datos

## Instalación

1. Clona este repositorio en tu máquina local:

git clone https://github.com/AlejandroBlinky/ProyectoBlogVideojuegos.git

2. Accede al directorio del proyecto:

cd .\BlogVideojuegos\

3. Crea y activa un entorno virtual (opcional pero recomendado):

python -m venv env
source env/bin/activate

4. Instala python y las dependencias del proyecto:
Instala python en microsoft store.

pip install -r requirements.txt


5. Realiza las migraciones de la base de datos:

python manage.py migrate


6. Inicia el servidor de desarrollo:

python manage.py runserver

7. Accede a la aplicación en tu navegador web en la siguiente dirección:

http://localhost:8000/




## Tecnología Utilizada

## Front-End
HTML 
CSS 
Bootstrap 
## Back-End

Python 
Django 

## Casos de Prueba

Este repositorio incluye una carpeta `CasosDePruebas` donde se encuentran documentados diferentes casos de prueba para verificar el funcionamiento de las funcionalidades del proyecto.

