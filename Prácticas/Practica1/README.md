# Práctica 1:

En esta entrega se nos pide la instalación de 2 máquinas virtuales con
Ubuntu Server. Para ello hemos descargado la imagen Ubuntu Server 17.10
y la hemos instalado.

Una vez instalada procedemos a instalar un **LAMP** mediante las siguientes
órdenes:

sudo apt-get install apache2 mysql-server mysql-client

Para comprobar el estado de la instalación:

apache2 -v

Como es necesario obtener la ip de las máquinas virtuales instalamos el paquete
**net-tools** y así poder ejecutar ifconfig y obtener la ip.

sudo apt install net-tools

También se nos pide tener instalado ssh y curl, para ello instalamos:

sudo apt install ssh
sudo apt install curl

Para comprobar que cURL funciona, vamos a hacerlo mediante un html ubicado en
/var/www/html llamado **hola.html** con el siguiente contenido:

<html>
<body>
Esto funciona :)
</body>
</html>

Y podemos comprobar en la siguiente imagen que funciona:

![Curl Funcionando en la primera máquina virtual](https://github.com/AlArgente/SWAP1718/blob/master/Pr%C3%A1cticas/Practica1/curlOn.PNG)

![Curl Funcionando en la segunda máquina virtual](https://github.com/AlArgente/SWAP1718/blob/master/Pr%C3%A1cticas/Practica1/curlOn1.PNG)

Y para mostrar que funciona correctamente el ssh conectamos una máquina a otra:

![SSH de una MV a otra](https://github.com/AlArgente/SWAP1718/blob/master/Pr%C3%A1cticas/Practica1/sshOn.PNG)


Práctica realizada por:

[Alberto Argente del Castillo Garrido](https://github.com/AlArgente/SWAP)

[Juan Manuel González-Aurioles Fernández](https://github.com/Juanmagaf/SWAP)
