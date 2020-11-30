# PR 1.3 - Apache i virtual hosts
## Informe
* Primeramente, después de instalar el servicio de apache2, tendremos que ir al directorio de las página web que es "/var/www" y después tendremos que crear la carpeta donde se alojarán todos los archivos de esa virtualhost o página web.

![Primera imagen](https://i.imgur.com/D7SxwJ3.png)

* Una vez que hayamos creado todo como se puede ver en la imagen de arriba, nos situaremos en el directorio de configuración de sitios que es "/etc/apache2/sites-available". Allí tendremos que realizar un archivo txt con una extensión de ".conf". En este archivo añadiremos líneas de "normas" sobre como actuará este virtual host. Nuestro archivo es **edusnchezj.ga.conf**.

![Segunda imagen](https://i.imgur.com/ElX8288.png)

* En la imagen podrás ver las diferentes reglas que hemos asignado a nuestra VirtualHost. Una vez que hayamos terminado, guarda el documento y una vez que realizemos esto tendremos que ejecutar dos comandos: **a2ensite edusnchezj.ga.conf** Una vez que se haya ejecutado este comando, deberás de reiniciar apache2.

![Tercera imagen](https://i.imgur.com/nioLAcF.png)

* Recuerda, que deberás de tener un dominio reservado para que funcione y los usuarios puedan acceder a este dominio públicamente. En la siguiente imagen se muestra que podemos entrar en este dominio.

![Cuarta imagen](https://i.imgur.com/hD6gitb.png)