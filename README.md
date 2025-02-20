Pasos para poder ejecutar el contenedor:
1. Para construir la imagen localmente, usa el siguiente comando:
   docker build -t fcl2005/ubuntu_vnc_code .
2. Para iniciar un contenedor basado en esta imagen:
   docker run -d -p 5901:5901 -p 22:22 --name fcl_contenedor ubuntu_vnc_code .
3. Para acceder al cliente VNC, como Remmina, hay que realizar la conexion VCN a:
   localhost:5091
   Las credenciales son usuario=alumno y contraseña=alumno
   
Esta es la URL del dockerhub que almacena la imagen:
https://hub.docker.com/r/fcl2005/ubuntu_vnc_code/tags
