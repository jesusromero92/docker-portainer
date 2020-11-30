# Instalación
**Debemos tener instalado Docker para poder realizar este proyecto**

## Pasos
1.  - Creamos un *volumen* para **NO PERDER LA INFORMACION SI BORRAMOS EL CONTENEDOR**
	
     ![Instalacion 1](https://github.com/jesusromero92/docker-portainer/blob/main/Fotos/instalacion1.png)

2.  - Creamos el contenedor 
    - En segundo plano
    - Mapeando el puerto **9000:9000** y **8000:8000** 
    - Dandole un nombre al contenedor para facilitar su administración
    - Creamos un enlace hacia el socket de docker de nuestra máquina con el 
      contenedor para que desde el contenedor,se pueda administrar nuestro 
      docker anfitrion
    - Administramos el volumen creado para que se cree una carpeta **/data** en el contenedor
    - Introducimos el nombre de la imagen que se trata de --> **portainer/portainer-ce**

	 
     ![Instalacion 2](https://github.com/jesusromero92/docker-portainer/blob/main/Fotos/instalacion2.png)

