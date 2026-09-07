# Tema 1: La comunidad Linux y una carrera en el mundo de código abierto

## Objetivo 1.2: Principales aplicaciones de código abierto

### Introducción

- Una aplicación es un programa informático.
- Las distribuciones de linux ofrecen muchas aplicaciones: aplicaciones de oficina, navegadores web, reproductores, editores multimedia, etc.
- El usuario debe elegir la aplicación que mejor se adapte a sus necesidades.


#### Paquetes de software

- Las distribuciones de linux ofrecen aplicaciones preinstaladas.
- Una distribución tiene un repositorio de paquetes con una vasta cantidad de aplicaciones disponibles para instalar a través de su gestor de paquetes.
- Debian, Ubuntu y Linux Mint utilizan dpkg, apt-get y apt para instalar paquetes de software DEB
- Red Hat, Fedora, CentOS utilizan rpm, yum y dnf para instalar paquetes de software RPM
- Al momento de instalar el gestor de paquetes de la distribución elegirá los paquetes adecuados, las dependencias necesarias y las actualizaciones futuras.
- Las dependencias son paquetes auxiliares que necesitan los programas.
- Los comandos dpkg y rpm operan archivos de paquetes individuales.
- Tanto apt o apt-get y dnf o yum, funcionan con catálogo de paquetes. Se puede descargar nuevos paquetes y sus dependencias, además comprobar si hay versiones más nuevas de los paquetes instalados.


#### Instalación de paquetes

En distribuciones basadas en paquetes **DEB**
- Buscar un paquete
```
apt search figlet
ó
apt-cache search figlet
```

- Instalar un paquete
```
apt install figlet
ó
apt-get install figlet
```

En distribuciones basadas en paquetes **RPM**
- Buscar un paquete
```
dnf search speaking cow
ó
yum search speaking cow
```

- Instalar un paquete
```
dnf install cowsay
ó
yum install cowsay
```


#### Eliminación de paquetes

En distribuciones basadas en paquetes **DEB**
- Eliminar un paquete
```
apt remove figlet
ó
apt-get remove figlet
```

En distribuciones basadas en paquetes **RPM**
- Eliminar un paquete
```
dnf remove cowsay
ó
yum remove cowsay
```


#### Aplicaciones Office

Las aplicaciones de office se utilizan para editar archivos como textos, presentaciones, hojas de cálculo y otros formatos que se utilizan habitualmente en un entorno de oficina.

- La suite más utilizada en Linux fue la suite OpenOffice.org
- OpenOffice.org era una versión de código abierto de la suite StarOffice
- StarOffice fue lanzada por Sun Microsystems.
- Sun Microsystems fue adquirida por Oracle Corporation
- Oracle Corporation transfirió el proyecto OpenOffice.org a la Fundación Apache y lo renombró a Apache OpenOffice.
- Otra suite de oficina fue lanzada por la Document Foundation denominado LibreOffice.
- El formato de documento preferido es Open Document Format(ODF).
- El uso de archivo ODF garantiza que los documentos se puedan transferir entre sistemas operativos y aplicaciones de diferentes proveedores.
- Las principales aplicaciones que ofrece Apache OpenOffice y LibreOffice son:
  - Writer, editos de texto
  - Calc, Hojas de cálculo
  - Impress, Presentaciones
  - Draw, Dibujo vectorial
  - Math, Fórmulas matemáticas
  - Base, Base de datos  
- LibreOffice y Apache OpenOffice son software de código abierto.
- LibreOffice está lincenciado bajo LGPLv3 y Apache OpenOffice está licenciado bajo Apache License 2.0
- LibreOffice puede incorporar mejoras hechas por Apache OpenOffice.
- Apache OpenOffice no puede incorporar mejoras hechas por LibreOffice.


#### Navegadores web

- El navegador web es la aplicación más importante del sistema operativo para el usuario medio.
- Google Chrome y Mozilla Firefox, son los principales navegadores web en el entorno Linux.
- Chrome es mantenido por Google, se vasa en el navegador de código abierto llamado Chromium.
- Firefox es mantenido por Mozilla, los origenes de Firefox estan ligados a Netscape.
- Netscape el primer navegador web popular en adoptar el modelo de código abierto.
- Mozilla desarrolla Thunderbird.


#### Multimedia

- La aplicaciones de escritorio siguen siendo la mejor opción para la creación de contenido multimedia
- Aplicaciones multimedia más populares par Linux son:
  - Blender, renderizador 3D para crear animaciones.
  - GIMP, editor de imágenes, se puede comparar con Adobe Photoshop.
  - Inkscape, editor de gráficos vectoriales, similar a Corel Draw o Adobe Illustrator. El formato por defecto de Inkscape es SVG.
  - Audacity, un editor de audio, permite filtrar, aplicar efectos y convertir a diferentes formatos de audio.
  - ImageMagick, es una herramienta de línea de comandos para convertir y editar la mayoría de los archivos de tipo imagen.

La aplicación más popular para la reproducción de video es VLC, la reproducción músical local tiene opciones como Audacious, Banshee y Amarok.


#### Programas para servidores

- El ordenador que ejecuta el navegador web se llama cliente y el ordenador remoto se llama servidor.
- Servidor HTTP, servicio de páginas web, los más populares son Apache, Nginx y lighttpd.
- Servidor de base de datos, conjunto organizado de información, almacena contenido de manera formateada, los más populares son MariaDB (originado en MySQL) y PostgreSQL.


#### Datos compartidos (Data Sharing)

- NFS (Network File System) es la forma estándar de compartir sistemas de archivos en redes equipadas únicamente con máquinas Unix/Linux.
- Se puede usar NFS para compartir el árbol de directorios de todo un sistema operativo.
- Se puede usar Samba para compartir archivos entre distintos sistemas operativos que esten conectados a la red. 
- El controlador de dominio, otorga autorización al iniciar sesión en una estación de trabajo.
- El controlador de dominio gestiona el acceso a varios recursos locales y remotos.
- El controlador de dominio es un servicio proporcionado por el Active Directory de Microsoft.
- Las estaciones de trabajo Linux pueden asociarse con un controlador de dominio mediante Samba o un subsistema de autenticación llamado SSSD.
- ownCloud y Nextcloud, soluciones en nube, proporcionan varios métodos de compartir datos basados en web.
- Nextcloud es un fork de ownCloud.
- ownCloud y Nextcloud proporcionan caracteristicas básicas: compartición y sincronización de archivos, espacios de trabajo colaborativos, calendario, contactos y correo.


#### Administración de la red

- DHCP (Dynamic Host Configuration Protocol), es reponsable de asignar una dirección IP al host cuando se conecta.
- DNS (Domain Name System), traduce el nombre de dominio a una dirección IP.


#### Lenguajes de programación

- Lenguajes de compilación, el código fuente se convierte en un archivo binario que puede ser ejecutado por el ordenador.
- Lenguaje interpretado, el programa no necesita ser compiladopreviamente, sino que el intérprete lee el código fuente y ejecuta su instrucción cada vez que se ejecuta el programa, los programas interpretados tienden a ser más lentos que los compilados.
- Algunos lenguajes de porogramación:
  - JavaScript, utilizado en páginas web.
  - C, está relacionado con los sistemas operativos, en particular con Unix, Linux. 
  - Java, los programas escritos en este lenguaje son portátiles.
  - Perl, utilizado para procesar contenido de texto con un fuerte énfasis en las expresiones regulares.
  - Shell, es una interfaz interactiva para ejecutar otros programas, sirve para automatizar tareas complejas.
  - Python, es una buena manera de empezar a aprender programación por su enfoque fácil de usar.
  - PHP, Lenguaje más utilizado en el lado del servidor para generar contenido para la web.
  - Los servidores LAMP proviene de la combinación de una sistema operativo Linux, un servidor Apache HTTP, una base de datos MySQL (o MariaDB) y la programación PHP.


