En esta practica vamos a crear un servidor web construyendoi una imagen de nginx con docker
<br><br>
Pasos para realizar la practica:
<br><br>
1) Clonar el siguiente repositorio https://github.com/elvyscruz/hola-docker
<br><br>
2) Modifcar la pagina index.html, incluir su nombre, etc)
<br><br>
3) Construir la imagen de la aplicacion ( docker build -t miapp:0.1 . )
<br><br>
4) Ejecutar el servidor web con docker ( docker run -d --name miapp -p 3000:80 miapp:0.1 )
<br><br>
5) Crear repositorio git, subirlo a github y postear url publico en el foro
