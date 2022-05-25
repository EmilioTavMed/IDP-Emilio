# Documentacion
**Práctica**: Despliegue de un servicio de monitorización
Instalar y configurar uno de los siguientes servicios de monitorización (uno de los siguientes asignado por el profesor: Icinga, Nagios, Zabbix) en una MV con Ubuntu y monitorizar lo siguiente:

Creamos una máquina virtual en Linux y para asignar el servicio de monitorización Icinga debemos de:

[Captura](/IMG/1.png)

Actualizar la máquina.

[Captura](/IMG/2.png)

Descargue e instale la clave del repositorio Icinga2.

[Captura](/IMG/3.png)

Utilice el siguiente comando para descubrir su nombre de código Ubuntu linux.

[Captura](/IMG/4.png)

Instalamos el Icinga

[Captura](/IMG/5.png)

Instale los plugins de monitoreo estándar del Icinga2.


Habilitamos el Icinga2

[Captura](/IMG/6.png)

Instalamos el paquete icinga2-ido-mysql.

[Captura](/IMG/7.png)


Habilitar la función ido-mysql del Icinga 2.

[Captura](/IMG/8.png)


Y debemos escoger el no en la configuración “dbconfig-common”

[Captura](/IMG/9.png)

Habilitar la característica ido-mysql.

[Captura](/IMG/10.png)

Reiniciar Icinga2 e Instalamos el servicio de base de datos 
MySQL.

[Captura](/IMG/11.png)

Acceder al servidor de bases de datos 

[Captura](/IMG/12.png)

creamos la base de datos y un usuario

[Captura](/IMG/13.png)

le damos todos los privilegios

[Captura](/IMG/14.png)

y con el nano modificamos el archivo de configuración ido

[Captura](/IMG/15.png)

Como instalar la web de icinga2

[Captura](/IMG/16.png)

e instalamos la página web

[Captura](/IMG/17.png)

Lanzamos el comando para poder lanzar el token

[Captura](/IMG/18.png)

ingresamos el token

[Captura](/IMG/19.png)

realizamos las configuraciones pertinentes

[Captura](/IMG/20.png)

[Captura](/IMG/21.png)

[Captura](/IMG/22.png)

[Captura](/IMG/23.png)

[Captura](/IMG/24.png)

[Captura](/IMG/25.png)

[Captura](/IMG/26.png)

[Captura](/IMG/27.png)

[Captura](/IMG/28.png)

[Captura](/IMG/29.png)

[Captura](/IMG/30.png)

[Captura](/IMG/31.png)

[Captura](/IMG/32.png)


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