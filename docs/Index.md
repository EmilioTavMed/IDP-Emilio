# Documentacion
Práctica: Despliegue de un servicio de monitorización
Instalar y configurar uno de los siguientes servicios de monitorización (uno de los siguientes asignado por el profesor: Icinga, Nagios, Zabbix) en una MV con Ubuntu y monitorizar lo siguiente:

Creamos una máquina virtual en Linux y para asignar el servicio de monitorización Icinga debemos de: 


Actualizar la máquina.


Descargue e instale la clave del repositorio Icinga2.


Utilice el siguiente comando para descubrir su nombre de código Ubuntu linux.


Instalamos el Icinga


Habilitamos el Icinga2


Instalamos el paquete icinga2-ido-mysql.


Habilitar la función ido-mysql del Icinga 2.


Y debemos escoger el no en la configuración “dbconfig-common”


Habilitar la característica ido-mysql.


Reiniciar Icinga2 e Instalamos el servicio de base de datos 
MySQL.


Acceder al servidor de bases de datos 


creamos la base de datos y un usuario


le damos todos los privilegios


y con el nano modificamos el archivo de configuración ido


Como instalar la web de icinga2



e instalamos la página web



ingresamos el token


realizamos las configuraciones pertinentes













## Los recursos de hardware (CPU, RAM, disco duro) de otra máquina virtual (Windows/Linux).


## Algún servicio de red (SAMBA/SMB, FTP, SSH, HTTP, ...).


## La página web del instituto.


Se deberá configurar algún mecanismo que notifique al administrador del sistema en caso de caída o fallo de algún sistema/recurso monitorizado.

## Conclusión

Total que al final los comandos para subir cambios:

```bash
git add .
git commit -m "description"
git push
```