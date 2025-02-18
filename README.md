Pasos para poder ejecutar el contenedor:
1. Para construir la imagen localmente, usa el siguiente comando:
   docker build -t fcl2005/ubuntu_vnc_code .
2. Para iniciar un contenedor basado en esta imagen:
   docker run -d -p 5901:5901 -p 22:22 --name fcl_contenedor ubuntu_vnc_code .
3. 
