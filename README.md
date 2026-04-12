# HabitFlow
Proyecto de HabitFlow con Django 

# Instalacion

# Requisitos previos

- Python 3.14.4 
- Crear entorno virtual:

```bash
python -m venv env
env\Scripts\activate
```
- Instalar las dependencias:

```bash
pip install -r requirements.txt
```

### Pasos

- Correr el servidor 
```bash
python manage.py runserver
```
- Ver en: http://127.0.0.1:8000/

### Extras para desarrollo

- Para crear un usuario que pueda iniciar sesion en el sitio de administrador. Ejecuta:

```bash
python manage.py createsuperuser
```

- Abre tu navegador y ve a "/admin/" 