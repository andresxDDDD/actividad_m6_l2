Nombre del Módulo Desarrollo de Aplicaciones Web con Python Django
Experiencia de Aprendizaje Actividad N° 2 – Instalación y Creación de un Proyecto Django
Tipo Encargo
Tiempo Estimado «Definir por parte del docente»
Objetivos
• Instalar Django correctamente dentro de un entorno virtual.
• Crear y ejecutar un nuevo proyecto Django desde consola.
• Comprender la estructura inicial de carpetas y archivos que conforman un proyecto Django.

Instrucciones
Crea una carpeta llamada actividad_m6_l2 y dentro de ella un documento llamado proyecto_django.md. En él
deberás registrar todo el proceso de creación y configuración inicial de un proyecto Django llamado mi_sitio.
1. Instalación en entorno virtual
Desde tu terminal, ejecuta los siguientes pasos y explica en cada uno qué está ocurriendo:

Comenta: ¿Qué es pip?
   Es el sistema de gestión de paquetes estándar para Python. Básicamente, es la herramienta que te permite descargar e instalar librerías y dependencias que no vienen incluidas en la instalación básica de Python 


 ¿Qué ventajas ofrece instalar Django dentro de un entorno virtual?

    Un entorno virtual es un espacio aislado  donde se puede instalar versiones específicas de librerías para un proyecto sin afectar a los demás proyectos ni al Python "global" del sistema.

    
2. Crear el proyecto
• Crea el proyecto con el comando:

• Copia la estructura generada por Django y pégala en tu archivo .md 
    .
        ├── README.md
        ├── manage.py
        ├── mi_sitio
        │   ├── __init__.py
        │   ├── asgi.py
        │   ├── settings.py
        │   ├── urls.py
        │   └── wsgi.py
        ├── proyecto_django.md
        └── requirements.txt


explicando para qué sirve cada uno de los siguientes elementos:
• manage.py
• mi_sitio/__init__.py es un archivo que se genera automaticamente, para decir que es un modulo de python 
• mi_sitio/settings.py
• mi_sitio/urls.py
• mi_sitio/asgi.py
• mi_sitio/wsgi.py



3. Ejecutar el servidor
• Corre el servidor de desarrollo con:

• Visita http://127.0.0.1:8000/ y toma una captura de pantalla mostrando que el servidor funciona
correctamente.
4. Crear una aplicación
• Crea una aplicación llamada principal:

• Explica brevemente:
• ¿Qué diferencia hay entre un “proyecto” y una “aplicación” en Django?
• ¿Qué carpetas se generan dentro de la app principal?

5. Configuración del proyecto
• Agrega 'principal' al INSTALLED_APPS de settings.py.
• Crea un archivo urls.py dentro de la app principal y configura el enrutamiento en mi_sitio/urls.py para
que dirija hacia esa app.
Puedes usar una vista sencilla que devuelva HttpResponse("¡Bienvenido a mi sitio!").

Entregables
• Carpeta comprimida (.zip) que contenga:
• El archivo proyecto_django.md con toda la explicación y comandos utilizados
• Una captura de pantalla del servidor funcionando
• (Opcional) El proyecto Django en versión


1. Instalación en entorno virtual
Desde tu terminal, ejecuta los siguientes pasos y explica en cada uno qué está ocurriendo:

    Comenta: ¿Qué es pip? 

       Es el sistema de gestión de paquetes estándar para Python. Básicamente, es la herramienta que te permite descargar e instalar librerías y dependencias que no vienen incluidas en la instalación básica de Python

   ¿Qué ventajas ofrece instalar Django dentro de un entorno virtual?    

        Un entorno virtual es un espacio aislado  donde se puede instalar versiones específicas de librerías para un proyecto sin afectar a los demás proyectos ni al Python "global" del sistema.
