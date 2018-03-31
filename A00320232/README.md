# Sistemas Operacionales - Parcial 1  

**Nombre:** Jefry Cardona Chilito
**Código:** A00320232  
**Correo:** jefry.cardona@correo.icesi.edu.co  
**Profesor:** Daniel Barragan  
**Url repositorio:** https://github.com/Jefry9508/so-exam1-1  

## Descarga y comprobación de imagen Debian 9

La imagen del sistema operativo Debian 9 se descargó de la pagina oficial, cuyo link se presenta a continuación. (https://www.debian.org/distrib/netinst).

La página da distintos tipos de imagenes para diferentes arquitecturas. En el caso nuestro, escogeremos la amd64.

Cuando la descarga terminó, se prosiguió a realizar una validación de la imagen. Para esto se buscó los checksums que pone a disposición el repositorio de Debian siguiendo el enlace que se presenta a continuación. (https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/).

![](capturas/checksums.png)

Para nuestro caso, usaremos la primera opción que es el checksum MD5SUMS que al seleccionarnos nos redirige a la pagina que tiene los valores para las tres imagenes que ofrece para descargar Debian 9.

![](capturas/md5sums.png)

Se usó el primer valor que aparece en la imagen de arriba, ya que es correspondiente al iso que se descargó.

Para realizar la comprobación de la imagen, se utilizó la herramienta [MD5_and_SHA_Checksum_Utility](http://descargar.cnet.com/MD5-SHA-Checksum-Utility/3000-2092_4-10911445.html) que nos permite realizar el checksum de un archivo y compararlo con el que el usuario le pase por parámetro.

![](capturas/comprobacion.png)


## Instalación del sistema operativo Debian 9 versión servidor
