# Trabajo RabbitMQ

Inicialmente, se debe levantar el contenedor con el servicio de RabbitMQ.

![Diagrama](IMAGE/image.png)

Se comprueba que el contenedor se haya levantado correctamente ingresando a `http://localhost:15672`, usando las credenciales que se encuentran en el archivo `.env`.

![Diagrama](IMAGE/image2.png)

El lenguaje de programacion seleccionado fue JavaScript. Siguiendo las instrucciones, se crearon los archivos `receive.js` y `send.js`.

Primero, se ejecuta el script `receive.js`:

![Diagrama](IMAGE/image3.png)

Luego, en otra terminal, se ejecuta el script `send.js`:

![Diagrama](IMAGE/image4.png)
