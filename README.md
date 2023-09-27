# Hotel Alura - Challenge ONE G5
Éste proyecto se basa en un sistema de reservas para el "Hotel Alura"<br>
 desarrollado con Java, librerias Swing y conexiones JDBC.<br>

## Tecnologías Utilizadas

<ul>
  <li>Java SE</li>
  <li>Swing</li>
  <li>Eclipse IDE</li>
  <li>Plugin WindowBuilder</li>
  <li>MySql Workbench</li>
  <li>JDBC</li>
</ul>

## Diagrama de la Base de Datos

<img src="/entidad-relacion-hotel-alura.png" width="800"/>


## Cómo usar el sistema de reservas

<b>1.</b> Empieza por clonar el repositorio en tu máquina local.


<b>2.</b> Inicia SQLServer o tu servidor de preferencia orientado a MySQL.

<b>3.</b> Ejecuta las consultas SQL para crear el esquema y sus tablas, además añade el usuario admin. (Estarán en el directorio "/scripts_HotelAlura.sql")

<b>4.</b> Abre el proyecto en tu IDE de preferencia y asegurate de tener configuradas sus dependencias BUILD PATH. (Estarán en el directorio "/ESP-hotel-alura/lib")

<b>5.</b> Configura la clase "src/factory/ConnectionFactory.java" con el usuario, contraseña y localhost de tu servidor MySQL.

<b>6.</b> Ejecuta la clase "src/Main.java" e inicia sesión con el usuario "admin" y la contraseña "admin".
