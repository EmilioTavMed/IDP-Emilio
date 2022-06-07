# Documentacion
**Práctica: Despliegue de un servicio de monitorización**
Instalar y configurar uno de los siguientes servicios de monitorización (uno de los siguientes asignado por el profesor: Icinga, Nagios, Zabbix) en una MV con Ubuntu y monitorizar lo siguiente:

Creamos una máquina virtual en Linux y para asignar el servicio de monitorización Icinga debemos de:

![Captura](IMG/1.png)

- Actualizar la máquina.

![Captura](IMG/2.png)

- Descargue e instale la clave del repositorio Icinga2.

![Captura](IMG/3.png)

- Utilice el siguiente comando para descubrir su nombre de código Ubuntu linux.

![Captura](IMG/4.png)

- Instalamos el **Icinga**

![Captura](IMG/5.png)

- Instalamos los plugins de monitoreo estándar del Icinga2 y habilitamos el **Icinga2**

![Captura](IMG/6.png)

- Instalamos el paquete icinga2-ido-mysql.

![Captura](IMG/7.png)


- Habilitar la función ido-mysql del Icinga 2.

![Captura](IMG/8.png)


- Debemos escoger el no en la configuración “dbconfig-common”

![Captura](IMG/9.png)

- Habilitar la característica ido-mysql.

![Captura](IMG/10.png)

- Reiniciar Icinga2 e Instalamos el servicio de base de datos 
MySQL.

![Captura](IMG/11.png)

- Acceder al servidor de bases de datos 

![Captura](IMG/12.png)

- Creamos la base de datos y un usuario

![Captura](IMG/13.png)

- Le damos todos los privilegios

![Captura](IMG/14.png)

- Con el nano modificamos el archivo de configuración ido

![Captura](IMG/15.png)

**Aclaración**:  *Mi guía continua en estos enlaces*

[Como configurar la base de datos Icinga Web 2](configurar-Icinga-web.md)

[Monitorización del equipo](Recursos.md)
