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

1. Al iniciar Oracle VM VirtualBox, en la parte superior izquierda presionamos en el botón que dice Nueva. Esto abrirá una nueva ventana.

2. En esta nueva ventana colocaremos el nombre de nuestra máquina virtual, el tipo de sistema operativo y su versión. Presionamos next.

3. Elegimos la cantidad de memoria RAM que deseamos para nuestra máquina. Por defecto se configura en 1Gb, así que la dejaremos así y presionamos next.

4. Ahora configuraremos el disco duro virtual de la máquina. Nos brinda 3 opciones: No agregar un disco duro virtual, crear un disco duro virtual o usar un archivo de disco duro virtual existente. Por defecto esta seleccionada la segunda opción, así que usaremos esa y presionamos next.

5. Eligiremos el tipo de archivo de disco duro virtual. Nos presenta 3 opciones: VDI(VirtualBox Disk Image), VHD(Virtual Hard Disk) y VMDK(Virtal Machine Disk). Normalmente se configura con la primera opción así escogeremos esa y presionamos next.

6. Configuramos el tipo de almacenamiento en disco. Nos presenta dos opciones: reservado dinamicamente y tamaño fijo. Usaremos la opción de reservado dinamicamente y presionamos next.

7. Asignaremos capacidad de almacenamiento al disco duro virtual. Por defecto se asigna 8Gb, así que lo dejaremos así y presionamos crear.

8. Ahora vamos de nuevo a la parte superior izquierda y presionamos en Configuración. Se nos abrirá una nueva ventana con todas las opciones de configuración de la máquina virtual antes de arrancarla.

9. Nos dirigimos a la barra de opciones vertical y presionamos en donde dice Almacenamiento.

10. Allí presionamos sobre la imagen de un disco que dice vacío. Esto nos abrirá unas opciones al lado derecho en donde podremos montar la imagen del sistema operativo Debian 9. Presionamos Aceptar e iniciamos la máquina virtual.

11. 
