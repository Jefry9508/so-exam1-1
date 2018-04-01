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

11. Cuando la máquina ya ha iniciado, preguntará que tipo de instalación queremos usar. Escogeremos la opción instalación gráfica por mayor facilidad.

12. Escogemos el idioma, español en nuestro caso y presionamos Continue.

13. Seleccionamos nuestra ubicación (Colombia) y presionamos Continuar.

14. Selccionamos la configuración del teclado. Escogeremos el latinoamericano y presionamos continuar.

15. Después de que termine de cargar todos los componentes necesarios para la instalación nos pedirá un nombre para el sistema. Lo podemos escribir o dejarlo por defecto y presionamos continuar.

16. A continuación nos pide el nombre de dominio. Podemos ignorar esta configuración y presionar Continuar.

17. Seguimos con la configuración de la clave de superusuario. La escribimos y presionamos Continuar.

18. Configuramos un nuevo usuario para tareas que no tengan que ver con superusuario.

19. Llegamos al Particionado de discos. En esta opción escogeremos la que está seleccionada por defecto que es Instalación guiada utilizando todo el disco y presionamos Continuar.

20. Aparece una pantalla con el disco en donde se instalará el sistema base. Presionamos Continuar.

21. Escogemos la opción seleccionada por defecto que es instalar todos los ficheros en una sola partición y presionamos Continuar.

21. Luego aparece una pantalla con la configuración que le hemos dado anteriormente. Presionamos Continuar.

22. Aparece una nueva pantalla en donde nos pregunta si queremos aceptar todos los cambios. Seleccionamos Si y presionamos Continuar.

23. El instalador comienza a instalar el sistema base.

24. Cuando termine de instalar el sistema base, nos preguntará si tenemos otro CD o DVD para el gestor de paquetes. Escogemos la opción No y presionamos Continuar.

25. Nos pedirá la ubicación de algú mirror que permita la descarga del gestor de paquetes. Así que escogeremos Colombia como ubicación y como mirror debian.uniminuto.edu y presionamos Continuar.

26. Nos pide una configuración de proxy si la tenemos, de lo contrario, omitimos esta opción.

27. Nos pregunta si queremos enviar datos de uso a los desarrolladores. Escogemos la opción que deseemos y damos en Continuar.

28. A continuación nos permite elegir software adicional para nuestro sistema operativo como como el entorno de escritorio, servidor web, servidor de impresión, SSH server y algunas interfaces de desarrollo. Escogemos las que necesitemos (en mi caso SSH Server, Servidor Web y entorno de escritorio) y presionamos Continuar. (Dependiendo del software adicional que instalemos puede demorarse un poco más de los normal la instalación).
