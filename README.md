# Sistemas-operativos
Repositorio para el curso de Sistemas Operativos


| Comando | Descripcion |
| --- | --- |
| `ip addr` |     Da a conocer la ip conectada a la maquina virutal |
| `ping 8.8.8.8` | Da a conocer si una red esta activa |
| `ip addr` |     Da a conocer la ip conectada a la maquina virutal |
| `sudo apt` | ejecuta un archivo  |
| `clear` | limpia el texto de la consola |
| `cd` | cambia de direcotrio |
| `ls` | lista los elementos del direcotrio |
| `dpkg` | selecciona los archivos de directorio|
| `-i` | es un short cut para instalar paquetes |
| `sudo apt update` | actualiza todos los paquetes disponibles |
| `pwd` |  indica donde se encuentra el usuario |
| `chmod` | permite modificar los permisos |
| `ls -l` | permite cambiar la vista del directorio |
| `du -h` | Nos permite conocoer el tamaño del archivo |
| `touch` | permite cambiar la hora de la ultima modificacion |
| `stat` | Despliga la informacion del archivo |
| `file` | muestra el formato del archivo seleccionado |
| `PS -aux` | Muestra los procesos |
| `chown` |permite cambiar el dueño de un archivo |
| `df-h` |permite mostrar el sistema de documentos actuales  |
| `mount` | permite montar un arhcivo en una carpeta especifica |
| `kill -9 $PID` | permite matar un proceso |
| `sudo apt install cmatrix` | Permite simular en la consola la pelicula matriz |
| `cp` | sirve para copiar un archivo o carpeta trabajando en la línea de comandos |
| `mv` | se utiliza para mover archivos y directorios de una ubicación a otra, también es utilizado para renombrar tanto archivos |
| `ls /tmp  grep texto2.txt` |  Este directorio contiene información de los procesos y aplicaciones que se están ejecutando en un momento determinado|
| `rm /tmp/texto2.txt` | se utiliza para borrar archivos |
| `rm prueba -R` | se utiliza para borrar archivos |
| `scp texto.txt` | es un protocolo de transferencia de archivos en red  |
| `sudo apt install openssh-server` | protocolo seguro para la administración remota de servidores, routers, switches y un largo etcétera de equipos |
| `wget` | usado para recuperar archivos y contenidos de una carpeta especifica |
| `git clone` | crea un clone de un repositorio |
| `curl -x GET -L` | útil para verificar URLs y transferir archivo|
| `wc /var/log/syslog` | permite realizar diferentes conteos desde la entrada estándar |
| `wc /var/log/syslog -l` | permite realizar diferentes conteos desde la entrada estándar  |
| `wc /var/log/syslog -w` | permite realizar diferentes conteos desde la entrada estándar  |
| `wc /var/log/syslog -m` | permite realizar diferentes conteos desde la entrada estándar  |
| `wc /var/log/syslog -n 3` | permite realizar diferentes conteos desde la entrada estándar  |
| `ls -l/-R` |  Lista el contenido de un determinado directorio |
| `ls -l /R more` |  Lista el contenido de un determinado directorio |
| `grep` | toma una expresión regular de la línea de comandos, lee la entrada estándar o una lista de archivos, e imprime las líneas que contengan coincidencias para la expresión regular. |
| `grep -r/var/log` | toma una expresión regular de la línea de comandos, lee la entrada estándar o una lista de archivos, e imprime las líneas que contengan coincidencias para la expresión regular.|
| `find/home` |es una herramienta precisa que permite encontrar archivos y directorios |
| `history`  | nos permite ver los ultimos comandos utilizados |
| `reboot` | nos permite reiniciar |
| `shutdown` | nos permite apagar un proceso |
| `pdfseparate` | nos permite serparar un pdf |
| `resutlad_%d.pdf` | nos permite ver un pdf |
| `convert-verbose-denisty` | nos permite convertir un archivo |
| `salida` | salir del terminal |
| `ocrfeeder` |permite mostrar el sistema de documentos actuales  |
| `top` | averiguar el estado de tu servidor |
| `htop` | es un visor de procesos para Linux, similar al comando top, pero más visual. |
| `pstree` | muestra todos los procesos que se están ejecutando actualmente en su sistema conectado. |
| `sudo apt intall gparted` | nos permite crear particiones del disco duro |
| `echo shell` | nos permite ejecutar procesos de shell |
| `cat/etc/shells` | nos permite ver archivos de shell |
| `chsh-s/bin/zsh## change bash to ksh##` | nos permite hacer cambios de shell a bash |
| `./script.sh` | son documentos de shell|
| `bash scripts.sh` | nos permite ejeucatar un proceso de shell |
| `chmod` | nos permite cambiar de direcotrio |
| `sudo apt-get install apt-transport-https ca-certificatescurlgnupg-agentsoftware-properties-common`| Instala paquetes necesarios para usar Docker|
| `curl -fsSL https://download.docker.com/linux/debian/gpg  sudo apt-key add -` | Descarga el GPG oficial de Docker |
| `sudo add-apt-repository deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable` | Agrega el repositorio oficial de Docker |
| `sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose` | Instala docker |
| `sudo usermod -aG docker ${USER}su - ${USER}` | Nos permite utilizar docker sin sudo |
| `sudo systemctl start docker` | Nos permite inicializar el Daemon |
| `sudo systemctl enable docke` | Nos permite inicializar el Daemon |
| `i. docker run -d -p 80:80 -p 3306:3306 tutum/lamp` | nos permite instalar imagenes |
| `docker pull` |  nos permite instalar imagenes  |
| `docker run -i -t ubuntu /bin/echo Prueba contenedor` | probamos las imagenes que instalamos |
| `sudo docker images` | Vemos las imagenes que instalamos |
| `sudo docker run -it ubuntu` | Inicia una instancia en ubuntu|
| `cat/ect/os-relese` | Inicia una instancia en ubuntu|
| `uname-a` | Inicia una instancia en ubuntu|
| `sudo apt install apcalc` | Inicia una instancia en ubuntu|
| `exit` | nos permite salir de la instancia |
| `sudo docker ps -a` | nos permite ver el estado de las imagenes |
| `sudo docker start d9b100f2f636` | nos permite ver el estado de las imagenes|
| `docker commit -m "Paquetes actualizados" -a "Mortasoft" 9a3d54ec6631` | nos permite hacer un commit a las imagen modificada|
| `docker stop container-id` | nos permite detener un contenedor |
| `docker start container-id` | nos permite iniciar un contenedor |
| `sudo docker login -u USUARIODOCKERHUB` | nos permite ingresar a nuestra paginad de docker desde la consola |
| `sudo docker commit b7dc036f2c99` | Nos permite hacer push a la cuenta de DockeHub |
| `sudo docker push docker-registry-username/docker-image-name` | Nos permite hacer push a la cuenta de DockeHub |
| `docker rmi Image Image` |Nos permite eliminar imagnes de dokcer|
| ` docker rm ID ID` | Nos permite eliminar contenedores |
| `docker run --rm image_name` | Nos permite eliminar contenedores despues de que este cerrado |
| ` sudo docker rm $(sudo docker ps -a -f status=exited -q)` | Nos permite eliminar todos los contenedores |
| `dpkg` | es una herramienta para instalar, compilar, eliminar y manipular los paquetes, en sistemas que utilizan el sistema de paquetes DEB.|
| `head` | se utiliza para mostrar informacion |
| `tail` | imprimir los últimos N números o colas (tails) de una entrada. |
| `less` | imprime el contenido de un file o un comnado |
| `more` | te permite mostrar el resultado de la ejecución de un comando en la terminal de a una página a la vez.  |
| `find` | una herramienta precisa que permite encontrar archivos y directorios.  |
| `locate` | nos permite buscar arhivos |
| `updatedb` | nos permite actualizar una base de datos |
| `ping` | nos permite verficar el nivel de conectivdad de la IP |
| `nmap` |  herramienta para la exploración de redes y la auditoría de seguridad |
| `nslookup` | es una herramienta que se utiliza para realizar búsquedas de DNS en Linux. |
| `netstat` | hat imprime conexiones de red, tablas de enrutamiento, estadísticas de interfaz, conexiones de enmascaramiento y membresías de multidifusión. |
| `tar unrar` | nos permite extraer archivos de tipo RAR |
| `dd` | nos permite convertir y copiar documentos |
| `ffmpeg` | lee desde un número arbitrario de "archivos" de entrada (que pueden ser archivos normales, tuberías, flujos de red, dispositivos de captura, etc.), especificado por la opción -i, y escribe en un número arbitrario de "archivos" de salida, que son especificado por una URL de salida simple. |
| `fdupes` | permite encontrar archivos duplicados en un directorio|
| `ocropusocrad` | una comunicación con los objetivos de Linux a través de SSH. Cuando se usa SSH para implementaciones en un servidor Linux, el agente Tentacle no es necesario y no es necesario instalarlo |
| `/etc/passwd` | contiene una lista de las cuentas del sistema, que proporciona a cada cuenta información útil como ID de usuario, ID de grupo, directorio de inicio, shell y más.|
| `/etc/shadow` | guarda las contraseñas de maner incriptada |
| `sudo passwd root` | nos permite cambiar la contraseña |
| `sudo iptables` | es una interfaz de línea de comandos que se utiliza para configurar y mantener tablas para el firewall Netfilter para IPv4, incluido en el kernel de Linux |
