# WebPersonal

Proyecto de portafolio personal desarrollado con Django.

## Descripción
Este proyecto es una página web personal para mostrar información sobre Beatriz Solana, incluyendo una portada, sección de "Acerca de", portafolio de proyectos y formulario de contacto. Utiliza Django como framework principal y Bootstrap para el diseño responsivo.

## Características
- Página de inicio con presentación personal
- Sección "Acerca de"
- Portafolio de proyectos con imágenes
- Formulario de contacto
- Diseño responsivo basado en Bootstrap
- Uso de archivos estáticos y plantillas personalizadas

## Estructura del Proyecto
```
webpersonal/
├── core/
│   ├── static/
│   │   └── core/
│   │       ├── css/
│   │       ├── img/
│   │       ├── js/
│   │       └── vendor/
│   ├── templates/
│   │   └── core/
│   │       ├── about.html
│   │       ├── base.html
│   │       ├── contact.html
│   │       └── home.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   └── migrations/
├── portfolio/
│   ├── templates/
│   │   └── portfolio/
│   │       └── portfolio.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   └── migrations/
├── media/
│   └── projects/
├── webpersonal/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── manage.py
```

## Instalación
1. Clona el repositorio:
   ```pwsh
   git clone <url-del-repositorio>
   cd webpersonal
   ```
2. Crea un entorno virtual e instálalo:
   ```pwsh
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   pip install django
   ```
3. Realiza las migraciones:
   ```pwsh
   python manage.py migrate
   ```
4. Ejecuta el servidor de desarrollo:
   ```pwsh
   python manage.py runserver
   ```
5. Accede a la web en [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Uso
- Modifica las plantillas en `core/templates/core/` y `portfolio/templates/portfolio/` para personalizar el contenido.
- Agrega tus proyectos en la app `portfolio`.
- Personaliza los archivos estáticos (CSS, JS, imágenes) en `core/static/core/`.

## Autor
Beatriz Solana

## Licencia
Este proyecto es de uso personal y educativo.
