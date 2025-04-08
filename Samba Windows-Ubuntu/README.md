# 1- Añadir Adaptador Puente (Bridge) en VirtualBox

![alt text](./img/image0.png)

# 2- Instalar Samba

Desde ubuntu instalamos con:

````
sudo apt install samba
````

# 3- Contraseña de Samba

Creamos con:

````
sudo smbpasswd -a nombre_usuario
````

# 4- Conexion entre Ubuntu y Windows

Debemos conocer cual es la IP del adaptador bridge

Desde la interfaz grafica:

![alt text](./img/image-5.png)

![alt text](./img/image-6.png)

**ATENCION** CUIDADO CON LAS IPS DINAMICAS (DHCP)

# 5- Compartir una carpeta

![alt text](./img/image.png)

![alt text](./img/image-1.png)

# 6- Acceder desde Windows

![alt text](./img/image-2.png)

![alt text](./img/image-3.png)

![alt text](./img/image-4.png)

# 7- Acceder desde Ubuntu
````
smb://nombre_del_servidor/nombre_del_recurso_compartido 
````

**En nombre del servidor ponemos la dirección del servidor por red interna**

![alt text](./img/image-7.png)

![alt text](./img/image-8.png)