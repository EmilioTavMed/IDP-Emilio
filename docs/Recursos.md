
# Los recursos de hardware (CPU, RAM, disco duro) de otra máquina virtual (Windows/Linux).

![Captura](IMG/35.png)

- Añadimos nuestra otra máquina con su dirección IP en el fichero hosts.conf

![Captura](IMG/36.png)

- Añadimos en el services.conf el servicio que vamos a utilizar

![Captura](IMG/37.png)

- E instalamos tanto en nustra máquina donde tenemos la página web como en la otra máquina ssh ya que sino la conexión a la otra máquina no funcionará 

![Captura](IMG/38.png) 

Como podemos observar la máquina se conectó correctamente

- Ahora bien para poder obtener la **CPU** y la **RAM**

![Captura](IMG/39.png)

- Añadimos en el **fichero hosts.conf** tanto la RAM como la CPU

![Captura](IMG/40.png)

Aquí tenemos la comprobación de la CPU
## Algún servicio de red (SAMBA/SMB, FTP, SSH, HTTP, ...).



## La página web del instituto.

**Nota** 
Se deberá configurar algún mecanismo que notifique al administrador del sistema en caso de caída o fallo de algún sistema/recurso monitorizado.

