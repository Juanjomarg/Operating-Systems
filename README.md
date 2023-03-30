# Sistemas Operativos
**Proposito:** Pruebas con comandos Linux

- Juan José Martínez Guerrero
- SOUTA G1
- 30-3-2023

# navegación rápida por Comandos LINUX

-[sudo-su](#sudo-su)
-[man](#man)
-[ls](#ls)
-[mkdir](#mkdir)
-[mkdirhier](#mkdirhier)
-[rmdir](#rmdir)
-[tree](#tree)
-[cat](#cat)
-[cmp](#cmp)
-[cp](#cp)
-[diff](#diff)
-[md5sum](#md5Sum)
-[rm](#rm)
-[split](#split)
-[stat](#stat)
-[uptime](#uptime)
-[lshw](#lshw)
-[pstree](#pstree)
-[arp](#arp)
-[dig](#dig)
-[chattr](#chattr)
-[chmod](#chmod)
-[lsattr](#lsattr)
-[tre-agrep](#tre-agrep)
-[finger](#finger)
-[groups](#groups)
-[w](#w)
-[whoami](#whoami)
-[adduser](#adduser)
-[chsh](#chsh)
-[groupadd](#groupadd)
-[groupmod](#groupmod)
-[passwd](#passwd)
-[usermod](#usermod)
-[rtcwake](#rtcwake)
-[date](#date)
-[df](#df)
-[du](#du)
-[uname](#uname)
-[vmstat](#vmstat)
-[kill](#kill)
-[taskset](#taskset)
-[netstat](#netstat)

# Detalle de comandos

### sudo su 
- **Función:** Cambia a modo Superusuario
- **Uso:** sudo su 
- **Imágen:** ![1](./Screenshots/1.png)
### man 
- **Función:** Abre el manual de uso de un programa o comando determinado.
- **Uso:** man PROGRAMA/COMANDO
- **Imágen:** ![1](./Screenshots/2.png) 
### ls 
- **Función:** Lista información sobre el o los archivos del directorio actual. 
- **Uso:** ls DIRECTORIO 
- **Imágen:** ![1](./Screenshots/3.png)
### mkdir 
- **Función:** Crea un directorio con el nombre dado en el directorio actual.
- **Uso:** mkdir DIRECTORIO 
- **Imágen:** ![1](./Screenshots/4.png) 
### mkdirhier 
- **Función:** Crea la jerarquía de directorios especificada.
- **Uso:** mkdirhier DIRECTORIORAIZ/DIRECTORIOANIDADO 
- **Imágen:** ![1](./Screenshots/5.png) 
### rmdir 
- **Función:** Elimina el directorio vacío
- **Uso:** rmdir DIRECTORIO(vacio)
- **Imágen:** ![1](./Screenshots/6.png) 
### tree 
- **Función:** Muestra la jerarquía del directorio actual.
- **Uso:** tree
- **Imágen:** ![1](./Screenshots/7.png) 
### cat 
- **Función:** Muestra en pantalla los contenidos linea a linea de un archivo.
- **Uso:** cat ARCHIVO
- **Imágen:** ![1](./Screenshots/8.png) 
### cmp 
- **Función:** Compara byte a byte dos archivos.
- **Uso:** cmp ARCHIVOA ARCHIVO B 
- **Imágen:** ![1](./Screenshots/9.png) 
### cp 
- **Función:** Copia un archivo o un directorio de un punto A a un punto B.
- **Uso:** cp ARCHIVO/DIRECTORIO DIRECTORIOALQUECOPIAR 
- **Imágen:** ![1](./Screenshots/10.png) 
### diff 
- **Función:** Compara archivos línea a línea.
- **Uso:** diff ARCHIVOA ARCHIVOB 
- **Imágen:** ![1](./Screenshots/11.png) 
### md5sum 
- **Función:** Permite revisar checksums para prevenir alteraciones indeseadas a archivos.
- **Uso:** md5sum ARCHIVO 
- **Imágen:** ![1](./Screenshots/12.png) 
### rm 
- **Función:** Elimina el archivo o el directorio especificado.
- **Uso:** rm ARCHIVO/DIRECTORIO 
- **Imágen:** ![1](./Screenshots/13.png) 
### split 
- **Función:** Divide un archivo en segmentos más pequeños del tamaño determinado.
- **Uso:** split ARCHIVO 
- **Imágen:** ![1](./Screenshots/14.png) 
### stat 
- **Función:** Brinda estado de archivo o sistema.
- **Uso:** stat ARCHIVO/NADA 
- **Imágen:** ![1](./Screenshots/15.png) 
### uptime 
- **Función:** Muestra el tiempo activo del computador durante la sesión actual.
- **Uso:** uptime 
- **Imágen:** ![1](./Screenshots/16.png) 
### lshw 
- **Función:** Lista todo el hardware del dispositivo.
- **Uso:** lshw 
- **Imágen:** ![1](./Screenshots/17.png) 
### pstree 
- **Función:** Muestra procesos activos como árbol. 
- **Uso:** pstree 
- **Imágen:** ![1](./Screenshots/18.png) 
### arp 
- **Función:** Manipula el caché del protocolo IPv4.
- **Uso:** arp NADA/IP 
- **Imágen:** ![1](./Screenshots/19.png) 
### dig 
- **Función:** Permite pedir solucionar un DNS a un servidor de DNS.
- **Uso:** dig IP 
- **Imágen:** ![1](./Screenshots/20.png) 
### chattr 
- **Función:** Permite cambiar los atributos de un archivo.
- **Uso:** chattr +ATRIBUTO -ATRIBUTO ARCHIVO 
- **Imágen:** ![1](./Screenshots/21.png) 
### chmod 
- **Función:** Permite cambiar los permisos de acceson a un archivo.
- **Uso:** chmod COMBINACIONDEUSUARIOS ARCHIVO 
- **Imágen:** ![1](./Screenshots/22.png) 
### lsattr 
- **Función:** Lista los atributos de un archivo.
- **Uso:** lsattr ARCHIVO 
- **Imágen:** ![1](./Screenshots/23.png) 
### tre-agrep 
- **Función:** Permite buscar texto en un archivo.
- **Uso:** tre-agrep -CANTIDADDEERRORESACEPTADOS ARCHIVO 
- **Imágen:** ![1](./Screenshots/24.png) 
### finger 
- **Función:** Muestra la informacion del usuario actual y sus detalles.
- **Uso:** finger 
- **Imágen:** ![1](./Screenshots/25.png) 
### groups 
- **Función:** Muestra los grupos a los que pertenece un usuario. 
- **Uso:** groups USUARIO 
- **Imágen:** ![1](./Screenshots/26.png) 
### w 
- **Función:** Muestra los usuarios de la maquina y sus procesos.
- **Uso:** w 
- **Imágen:** ![1](./Screenshots/27.png) 
### whoami 
- **Función:** Muestra el nombre de usuario actual.
- **Uso:** whoami 
- **Imágen:** ![1](./Screenshots/28.png) 
### adduser 
- **Función:** Permite crear un usuario.
- **Uso:** adduser --GRUPOS USUARIO 
- **Imágen:** ![1](./Screenshots/29.png) 
### chsh 
- **Función:** Permite cambiar la terminal utilizada.
- **Uso:** chsh TERMINAL 
- **Imágen:** ![1](./Screenshots/30.png) 
### groupadd 
- **Función:** Permite gestionar los grupos en la maquina. 
- **Uso:** group add GRUPO 
- **Imágen:** ![1](./Screenshots/31.png) 
### group mod 
- **Función:** Permite cambiar los permisos de los grupos.
- **Uso:** group mod PERMISOS
- **Imágen:** ![1](./Screenshots/32.png) 
### passwd 
- **Función:** Permite cambiar la contrasena de un usuario.
- **Uso:** passwd USUARIO
- **Imágen:** ![1](./Screenshots/33.png) 
### usermod 
- **Función:** Permite modificar la configuracion de las cuentas.
- **Uso:** usermod USUARIO
- **Imágen:** ![1](./Screenshots/34.png) 
### rtcwake 
- **Función:** Envia el dispositivo a hibernacion hasta que se llega a una hora establecida.
- **Uso:** rtcwake FECHAHORA
- **Imágen:** ![1](./Screenshots/35.png) 
### date 
- **Función:** Muestra la fecha y hora actual del dispositivo.
- **Uso:** date
- **Imágen:** ![1](./Screenshots/36.png) 
### df 
- **Función:** Retorna el usu de disco para los discos.
- **Uso:** df DISCO
- **Imágen:** ![1](./Screenshots/37.png) 
### du 
- **Función:** Retorna el uso de disco de los archivos en el directorio actual.
- **Uso:** du DIRECTORIO 
- **Imágen:** ![1](./Screenshots/38.png) 
### uname 
- **Función:** Muestra informacion del sistema.
- **Uso:** uname
- **Imágen:** ![1](./Screenshots/39.png) 
### vmstat 
- **Función:** Muestra informacion sobre la memoria virtual.
- **Uso:** vmstat
- **Imágen:** ![1](./Screenshots/40.png) 
### kill 
- **Función:** Mata un proceso.
- **Uso:** kill PROCESO
- **Imágen:** ![1](./Screenshots/41.png) 
### taskset 
- **Función:** Establece nucleos especificos a un proceso.
- **Uso:** taskset CODIGOHEXADELOSNUCLEOS
- **Imágen:** ![1](./Screenshots/42.png) 
### netstat 
- **Función:** Muestra informacion sobre la tarjeta de red y su uso.
- **Uso:** netstat
- **Imágen:** ![1](./Screenshots/43.png) 
