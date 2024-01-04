# Proyecto Integrado Django - ToDoApp

Este es el repositorio para la aplicación ToDoApp, una aplicación web construida con Django que permite a los usuarios gestionar sus tareas diarias de forma eficiente.

## Configuración del entorno

Para configurar y ejecutar el proyecto en tu entorno local, sigue estos pasos:

### Prerrequisitos

- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Virtualenv (opcional, pero recomendado)

### Instalación

1. Clona el repositorio en tu máquina local:
git clone https://github.com/impacevanend/dint.git
cd [nombre del repositorio]


2. Crea y activa un entorno virtual (opcional):
python -m venv mi_entorno
source mi_entorno/bin/activate # En Windows usa mi_entorno\Scripts\activate
3. Instala las dependencias del proyecto:
pip install -r requirements.txt

### Ejecución

Una vez configurado el entorno y las variables, puedes ejecutar el servidor de desarrollo de Django:

Por supuesto, aquí tienes un ejemplo de un archivo README.md completo para tu aplicación Django que incluye instrucciones para la configuración y la ejecución del proyecto:

markdown
Copy code
# ToDoApp - Aplicación de Lista de Tareas

ToDoApp es una aplicación web desarrollada con Django que permite a los usuarios crear, editar y eliminar tareas pendientes. Es una herramienta sencilla pero poderosa para aumentar la productividad personal y la gestión del tiempo.

## Configuración del Entorno de Desarrollo

### Prerrequisitos

Asegúrate de tener instalado Python 3.8 o superior y pip. Se recomienda también el uso de virtualenv para crear un entorno aislado para las dependencias del proyecto.

### Instalación

1. **Clona el repositorio:**

git clone [URL del repositorio]
cd [nombre del repositorio]

markdown
Copy code

2. **Crea y activa un entorno virtual:**

En macOS y Linux:

python3 -m venv mi_entorno
source mi_entorno/bin/activate

yaml
Copy code

En Windows:

python -m venv mi_entorno
.\mi_entorno\Scripts\activate

markdown
Copy code

3. **Instala las dependencias del proyecto:**

pip install -r requirements.txt

bash
Copy code

### Configuración

Antes de ejecutar la aplicación, necesitarás configurar las variables de entorno necesarias. Puedes hacerlo creando un archivo `.env` en la raíz del proyecto con el siguiente contenido (ajusta los valores según sea necesario):

DEBUG=on
SECRET_KEY=tu_clave_secreta_aquí
DATABASE_URL=sqlite:///db.sqlite3

shell
Copy code

### Ejecución

Una vez configurado el entorno y las variables, puedes ejecutar el servidor de desarrollo de Django:

python manage.py runserver

Esto iniciará el servidor de desarrollo en [http://localhost:8000](http://localhost:8000) donde podrás ver y interactuar con tu aplicación.

### Administración

Para acceder al panel de administración de Django, primero debes crear un superusuario:
python manage.py createsuperuser

Sigue las instrucciones en pantalla para crear el superusuario. Luego, visita [http://localhost:8000/admin](http://localhost:8000/admin) y usa las credenciales del superusuario para acceder.


¡Gracias por utilizar ToDoApp!
