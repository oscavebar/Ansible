### Configurar un playbook en Ansible.
1. Creamos un repositorio para nuestro playbook
2. Hacemos un fichero llamado hosts donde guardamos el host con la ip.


![hosts](/imagenes/hosts.png)

3. Ahora tenemos que generar nuestras claves en nuestro equipo y acto seguido enviarlo a nuestro servidor con lo siguientes comandos.

![keygen](/imagenes/keygen.png)
![clave](/imagenes/clave.png)

4. Para la configuración del playbook, creamos un fichero yml y en mi caso especifico las siguientes opciones para desplegar un servicio nginx.

![configuracion](/imagenes/playbook.png)
