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
- Otra suite de oficina fue lanzada por la DOcument Foundation denominado LibreOffice.
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




#### Multimedia




#### Programas para servidores




#### Datos compartidos (Data Sharing)




#### Administración de la red




#### Lenguajes de programación




