## Mi primer web con Python

En este sitio se usara:

*Lenguaje de programación*
- Python (https://www.python.org/)

*Framework web application *
- Flask (https://palletsprojects.com/p/flask/)

*Framework css*
- Bootstrap (https://getbootstrap.com/docs/4.5/getting-started/introduction/)

- Revisar que este instalado Python y Pip, en consola:

python --version
pip --version

Si nos devuelve la version es porque lo tenemos instalado.

- Ahora corremos en la carpeta del proyecto la siguiente linea:

python index.py

si no existe error de sintaxis, nos mostrara la dirección donde correra nuestra web:

 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

Para no estar parando el servicio en cada cambios agregamos la siguiente linea de codigo en index.py (por debajo de app.route):


// if __name__ == '__main__':
    app.run(debug=True) //

- Instalar virtualenv para preparar el proyecto para el entorno virtual https://flask.palletsprojects.com/en/1.1.x/installation/#virtual-environments

Instalando Heroku Cli en mac (https://devcenter.heroku.com/articles/heroku-cli)

- brew tap heroku/brew && brew install heroku

- Se desplega la web en Heroku (https://www.heroku.com/)

- se instala gunicorn desde la carpeta venv/bin (https://gunicorn.org/), el comando es:

pip install gunicorn

