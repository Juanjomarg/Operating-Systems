# Sistemas Operativos
**Proposito:** Pruebas con comandos Linux

- Juan José Martínez Guerrero
- SOUTA G1
- 30-3-2023

# navegación rápida por Comandos LINUX

--[sudo-su](#sudo-su)
--[man](#man)
--[ls](#ls)
--[mkdir](#mkdir)
--[mkdirhier](#mkdirhier)
--[rmdir](#rmdir)
--[tree](#tree)
--[cat](#cat)
--[cmp](#cmp)
--[cp](#cp)
--[diff](#diff)
--[md5sum](#md5Sum)
--[rm](#rm)
--[split](#split)
--[stat](#stat)
--[uptime](#uptime)
--[lshw](#lshw)
--[pstree](#pstree)
--[arp](#arp)
--[dig](#dig)
--[chattr](#chattr)
--[chmod](#chmod)
--[lsattr](#lsattr)
--[tre-agrep](#tre-agrep)
--[finger](#finger)
--[groups](#groups)
--[w](#w)
--[whoami](#whoami)
--[adduser](#adduser)
--[chsh](#chsh)
--[group add](#group-add)
--[gorup mod](#group-mod)
--[passwd](#passwd)
--[usermod](#usermod)
--[rtcwake](#rtcwake)
--[date](#date)
--[df](#df)
--[du](#du)
--[uname](#uname)
--[vmstat](#vmstat)
--[kill](#kill)
--[taskset](#taskset)
--[netstat](#netstat)

# Detalle de comandos

### sudo su 
- **Función:** Cambia a modo Superusuario
- **Uso:**  sudo su 
- **Imágen:** ![1](./Screenshots/1.png)
### man  
- **Función:**Abre el manual de uso de un programa o comando determinado.
man PROGRAMA/COMANDO  
![1](./Screenshots/2.png) 
### ls  
- **Función:** Lista información sobre el o los archivos del directorio actual. 
- **Uso:**  ls DIRECTORIO  ![1](./Screenshots/4.png)
### mkdir  
- **Función:** Crea un directorio con el nombre dado en el directorio actual.
- **Uso:**  mkdir DIRECTORIO  ![1](./Screenshots/4.png) 
### mkdirhier  
- **Función:** Crea la jerarquía de directorios especificada.
- **Uso:**  mkdirhier DIRECTORIORAIZ/DIRECTORIOANIDADO  ![1](./Screenshots/5.png) 
### rmdir  
- **Función:** Elimina el directorio vacío
- **Uso:**  rmdir DIRECTORIO(vacio)  ![1](./Screenshots/1.png) 
### tree  
- **Función:** Muestra la jerarquía del directorio actual.
- **Uso:**  tree  ![1](./Screenshots/1.png) 
### cat  
- **Función:** Muestra en pantalla los contenidos linea a linea de un archivo.
- **Uso:**  cat ARCHIVO  ![1](./Screenshots/1.png) 
### cmp  
- **Función:** Compara byte a byte dos archivos.
- **Uso:**  cmp ARCHIVOA ARCHIVO B  ![1](./Screenshots/1.png) 
### cp  
- **Función:** Copia un archivo o un directorio de un punto A a un punto B.
- **Uso:**  cp ARCHIVO/DIRECTORIO DIRECTORIOALQUECOPIAR  ![1](./Screenshots/1.png) 
### diff  
- **Función:** Compara archivos línea a línea.
- **Uso:**  diff ARCHIVOA ARCHIVOB  ![1](./Screenshots/1.png) 
### md5sum  
- **Función:** Permite revisar checksums para prevenir alteraciones indeseadas a archivos.
- **Uso:**  md5sum ARCHIVO  ![1](./Screenshots/1.png) 
### rm  
- **Función:** Elimina el archivo o el directorio especificado.
- **Uso:**  rm ARCHIVO/DIRECTORIO  ![1](./Screenshots/1.png) 
### split  
- **Función:** Divide un archivo en segmentos más pequeños del tamaño determinado.
- **Uso:**  split ARCHIVO  ![1](./Screenshots/1.png) 
### stat  
- **Función:** Brinda estado de archivo o sistema.
- **Uso:**  stat ARCHIVO/NADA  ![1](./Screenshots/1.png) 
### uptime  
- **Función:** Muestra el tiempo activo del computador durante la sesión actual.
- **Uso:**  uptime  ![1](./Screenshots/1.png) 
### lshw  
- **Función:** Lista todo el hardware del dispositivo.
- **Uso:**  lshw  ![1](./Screenshots/1.png) 
### pstree  
- **Función:** Muestra procesos activos como árbol. 
- **Uso:**  pstree  ![1](./Screenshots/1.png) 
### arp  
- **Función:** Manipula el caché del protocolo IPv4.
- **Uso:**  arp NADA/IP  ![1](./Screenshots/1.png) 
### dig  
- **Función:** Permite pedir solucionar un DNS a un servidor de DNS.
- **Uso:**  dig IP  ![1](./Screenshots/1.png) 
### chattr  
- **Función:** Permite cambiar los atributos de un archivo.
- **Uso:**  chattr +ATRIBUTO -ATRIBUTO ARCHIVO  ![1](./Screenshots/1.png) 
### chmod  
- **Función:** Permite cambiar los permisos de acceson a un archivo.
- **Uso:**  chmod COMBINACIONDEUSUARIOS ARCHIVO  ![1](./Screenshots/1.png) 
### lsattr  
- **Función:** Lista los atributos de un archivo.
- **Uso:**  lsattr ARCHIVO  ![1](./Screenshots/1.png) 
### tre-agrep  
- **Función:** Permite buscar texto en un archivo.
- **Uso:**  tre-agrep -CANTIDADDEERRORESACEPTADOS ARCHIVO  ![1](./Screenshots/1.png) 
### finger  
- **Función:** Muestra la informacion del usuario actual y sus detalles.
- **Uso:**  finger  ![1](./Screenshots/1.png) 
### groups  
- **Función:** Muestra los grupos a los que pertenece un usuario. 
- **Uso:**  groups USUARIO  ![1](./Screenshots/1.png) 
### w  
- **Función:** Muestra los usuarios de la maquina y sus procesos.
- **Uso:**  w  ![1](./Screenshots/1.png) 
### whoami  
- **Función:** Muestra el nombre de usuario actual.
- **Uso:**  whoami  ![1](./Screenshots/1.png) 
### adduser  
- **Función:** Permite crear un usuario.
- **Uso:**  adduser --GRUPOS USUARIO  ![1](./Screenshots/1.png) 
### chsh  
- **Función:** Permite cambiar la terminal utilizada.
- **Uso:**  chsh TERMINAL  ![1](./Screenshots/1.png) 
### group add  
- **Función:** Permite gestionar los grupos en la maquina. 
- **Uso:**  group add GRUPO  ![1](./Screenshots/1.png) 
### group mod  
- **Función:** Permite cambiar los permisos de los grupos.
- **Uso:**  group mod PERMISOS  ![1](./Screenshots/1.png) 
### passwd  
- **Función:** Permite cambiar la contrasena de un usuario.
- **Uso:**  passwd USUARIO  ![1](./Screenshots/1.png) 
### usermod  
- **Función:** Permite modificar la configuracion de las cuentas.
- **Uso:**  usermod USUARIO  ![1](./Screenshots/1.png) 
### rtcwake  
- **Función:** Envia el dispositivo a hibernacion hasta que se llega a una hora establecida.
- **Uso:**  rtcwake FECHAHORA  ![1](./Screenshots/1.png) 
### date  
- **Función:** Muestra la fecha y hora actual del dispositivo.
- **Uso:**  date  ![1](./Screenshots/1.png) 
### df  
- **Función:** Retorna el usu de disco para los discos.
- **Uso:**  df DISCO  ![1](./Screenshots/1.png) 
### du  
- **Función:** Retorna el uso de disco de los archivos en el directorio actual.
- **Uso:**  du DIRECTORIO  ![1](./Screenshots/1.png) 
### uname  
- **Función:** Muestra informacion del sistema.
- **Uso:**  uname  ![1](./Screenshots/1.png) 
### vmstat  
- **Función:** Muestra informacion sobre la memoria virtual.
- **Uso:**  vmstat  ![1](./Screenshots/1.png) 
### kill  
- **Función:** Mata un proceso.
- **Uso:**  kill PROCESO  ![1](./Screenshots/1.png) 
### taskset  
- **Función:** Establece nucleos especificos a un proceso.
- **Uso:**  taskset CODIGOHEXADELOSNUCLEOS ![1](./Screenshots/1.png) 
### netstat  
- **Función:** Muestra informacion sobre la tarjeta de red y su uso.
- **Uso:**  netstat ![1](./Screenshots/1.png) 
