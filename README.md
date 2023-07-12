# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version 3.2.2

* System dependencies

* Configuration básica

* Database creation postgrest

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Regístrate en Heroku: Si aún no tienes una cuenta, ve al sitio web de Heroku (https://www.heroku.com/) y regístrate para obtener una cuenta .

Prepara tu aplicación: Asegúrate de que tu aplicación esté lista para ser desplegada. Esto incluye tener todos los archivos necesarios, dependencias resueltas y un archivo Procfile adecuado para especificar cómo iniciar tu aplicación.

Instala el CLI de Heroku: Descarga e instala el Heroku Command Line Interface (CLI) desde la página de descarga oficial de Heroku (https://devcenter.heroku.com/articles/heroku-cli#download-and-install).

Inicia sesión en Heroku CLI: Abre una terminal o línea de comandos y ejecuta el siguiente comando para iniciar sesión en tu cuenta de Heroku:

Copy code
heroku login
Se abrirá una ventana del navegador para que ingreses tus credenciales de Heroku. Después de iniciar sesión, puedes cerrar la ventana del navegador y volver a la terminal.

Crea una nueva aplicación en Heroku: Dentro de la terminal, navega hasta el directorio raíz de tu aplicación y ejecuta el siguiente comando para crear una nueva aplicación en Heroku:

lua
Copy code
heroku create
Esto creará una nueva aplicación en tu cuenta de Heroku y asignará automáticamente un nombre único a tu aplicación.

Despliega tu aplicación: Una vez que tienes una aplicación creada en Heroku, puedes desplegarla utilizando el siguiente comando:

css
Copy code
git push heroku main
Este comando enviará tu código fuente a Heroku y comenzará el proceso de construcción y despliegue de tu aplicación.

Escala tu aplicación: Después de que tu aplicación se haya desplegado correctamente, puedes escalarla según tus necesidades. Puedes ejecutar el siguiente comando para escalar tu aplicación a una instancia web:

Copy code
heroku ps:scale web=1
Esto garantiza que tu aplicación se ejecute con al menos una instancia en el plan gratuito de Heroku.

Accede a tu aplicación: Después de que tu aplicación se haya desplegado y escalado, puedes abrirla en tu navegador utilizando el siguiente comando:

arduino
Copy code
heroku open
Esto abrirá tu aplicación desplegada en una nueva pestaña del navegador.

Estos son los pasos básicos para hacer un deploy de una aplicación en Heroku. Ten en cuenta que pueden variar dependiendo de las características específicas de tu aplicación y del entorno en el que estés trabajando.

Recuerda consultar la documentación oficial de Heroku (https://devcenter.heroku.com/) para obtener información más detallada sobre el despliegue y administración de aplicaciones en la plataforma.
