# Web Empresarial del Curso de Django

Proyecto revisado y funcionando perfectamente con Python==3.10.2 y Django>=4.0.2

### Instalación con Pipenv usando requirements.txt

```bash
pipenv install -r requirements.txt
```

### Iniciar el proyecto desde el directorio:

```bash
cd webempresa
pipenv run python manage.py runserver
```

### Crear un nuevo superusuario:

```bash
pipenv run python manage.py createsuperuser
```

### Enlaces de interes

https://htmlcolorcodes.com/es/nombres-de-los-colores/

https://htmlreference.io/

https://developer.mozilla.org/en-US/docs/Web/CSS/font-family


#activar venv 
python -m venv env

Set-ExecutionPolicy RemoteSigned -Scope Process
.\env\Scripts\activate


pip install django django-ckeditor Pillow pylint pylint-django pylint-celery 
pip install --upgrade pip

django-admin startproject webpersonal

cd .\webpersonal\
python manage.py runserver

python manage.py migrate


# Crear APPs

python manage.py startapp core


Cargar ficheros estaticos
{% load static %}

{% load static %}
<video controls>
    <source src="{% static 'core/sample3.mp4' %}" type="video/mp4">
    Tu navegador no admite el elemento de video.
</video>


<iframe src="https://player.vimeo.com/video/123456789" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>


