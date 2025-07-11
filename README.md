# Aqua-Control

Es un proyecto en una base de datos desarrollado en web, para ello usamos diferentes herramientas como MySQL y visual studio code, la mayor parte del proyecto se desarrolló en visual studio code. Para ejecutarlo en cualquier computadora, se tiene que tener en cuenta las diferentes instalaciones.

1.- Se debe de tener instalado MySQL, de preferencia toda la paquetería, el link de descarga es: https://dev.mysql.com/downloads/installer/, se debe de descargar el que pesa cerca de 400mb.
2.- Ya que se haya descargado, se hace la instalación de MySQL teniendo asegurado que se descarguen todas las extensiones.
3.- Teniendo instalado MySQL, ahora sigue crear la base de datos dedicada para el proyecto llamada "agua_mvp" usando el puerto por default.
4.- Para la base de datos, tenemos que crear las tablas necesarias: consumos y users.
5.- Ahora, pasando a la parte de visual studio, se tiene que abrir una terminal y empezar a ejecutar diferentes comandos de instalación:
	a) Entrar a la carpeta del proyecto (backend) usando cd hasta llegar a la carpeta.
	b) npm init -y
	c) npm install express mysql2 dotenv bcryptjs jsonwebtoken cors
	d) & "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysql.exe" -u root -p (root puede cambiar, todo depende del nombre del usuario que hayan puesto como 	nombre de usuario para la base de datos).
	e) Luego de ese comando, pide la contraseña que hayan puesto en la base de datos.
	f) SOURCE sql\init.sql;
	g) Luego, se regresan a la carpeta raíz del proyecto (backend) y ahí se ejecuta el último comando: node .\src\index.js
6.- Al momento de tener todo instalado y que no haya error en ningún lado, simplemente se abre index.html y se usa la página web.
7.- Para su uso correcto, se recomienda ver el video de YouTube creado por nosotros, el link se encuentra en el documento del proyecto.
