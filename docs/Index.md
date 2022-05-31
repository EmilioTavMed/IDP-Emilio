# Documentacion
**Práctica**: Despliegue de un servicio de monitorización
Instalar y configurar uno de los siguientes servicios de monitorización (uno de los siguientes asignado por el profesor: Icinga, Nagios, Zabbix) en una MV con Ubuntu y monitorizar lo siguiente:

Creamos una máquina virtual en Linux y para asignar el servicio de monitorización Icinga debemos de:



![Captura](IMG/1.png)

Actualizar la máquina.

![Captura](IMG/2.png)

Descargue e instale la clave del repositorio Icinga2.

![Captura](IMG/3.png)

Utilice el siguiente comando para descubrir su nombre de código Ubuntu linux.

![Captura](IMG/4.png)

Instalamos el Icinga

![Captura](IMG/5.png)

Instale los plugins de monitoreo estándar del Icinga2.


Habilitamos el Icinga2

![Captura](IMG/6.png)

Instalamos el paquete icinga2-ido-mysql.

![Captura](IMG/7.png)


Habilitar la función ido-mysql del Icinga 2.

![Captura](IMG/8.png)


Debemos escoger el no en la configuración “dbconfig-common”

![Captura](IMG/9.png)

Habilitar la característica ido-mysql.

![Captura](IMG/10.png)

Reiniciar Icinga2 e Instalamos el servicio de base de datos 
MySQL.

![Captura](IMG/11.png)

Acceder al servidor de bases de datos 

![Captura](IMG/12.png)

Creamos la base de datos y un usuario

![Captura](IMG/13.png)

Le damos todos los privilegios

![Captura](IMG/14.png)

Con el nano modificamos el archivo de configuración ido

![Captura](IMG/15.png)

**Como instalar la web de icinga2**

![Captura](IMG/16.png)

![Captura](IMG/17.png)

![Captura](IMG/18.png)

Instalamos la página web

![Captura](IMG/19.png)

Lanzamos el comando para poder lanzar el token

![Captura](IMG/18.png)

![Captura](IMG/20.png)

Ingresamos el token

![Captura](IMG/21.png)

Realizamos las configuraciones pertinentes:

![Captura](IMG/27.png)

![Captura](IMG/22.png)

Como podemos ver en esta captura todos los pasos anteriores están correctamente

Configuramos la base de datos:

![Captura](IMG/23.png)

![Captura](IMG/24.png)

![Captura](IMG/25.png)

Configuracion de la cuenta de administración

![Captura](IMG/26.png)

Donde se modifica la monitorización

![Captura](IMG/28.png)

![Captura](IMG/29.png)

Luego te pide la ubicacion donde se enviaran los comandos

![Captura](IMG/30.png)

![Captura](IMG/31.png)

Y ya tendriamos lista la configuracion, iniciamos sesion con el usuario admin (en nuestro caso el administrador)

![Captura](IMG/32.png)

![Captura](IMG/34.png)

## Los recursos de hardware (CPU, RAM, disco duro) de otra máquina virtual (Windows/Linux).

![Captura](IMG/35.png)

Añadimos nuestra otra máquina con su dirección IP en el fichero hosts.conf

![Captura](IMG/36.png)

Añadimos en el services.conf el servicio que vamos a utilizar

![Captura](IMG/37.png)

E instalamos tanto en nustra máquina donde tenemos la página web como en la otra máquina ssh ya que sino la conexión a la otra máquina no funcionará 

![Captura](IMG/38.png) 

Como podemos observar la máquina se conectó correctamente

Ahora bien para poder obtener la CPU y la RAM

![Captura](IMG/39.png)
Añadimos en el fichero hosts.conf tanto la RAM como la CPU

![Captura](IMG/40.png)
Aquí tenemos la comprobación de la CPU
## Algún servicio de red (SAMBA/SMB, FTP, SSH, HTTP, ...).



## La página web del instituto.

**Nota** 
Se deberá configurar algún mecanismo que notifique al administrador del sistema en caso de caída o fallo de algún sistema/recurso monitorizado.

