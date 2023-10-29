# spm-docker-bootcamp-m14
version docker del wrapper de una aplicación web java (openjdk) para administrar contraseñas

# ejecución y prueba
De forma manual bajando los archivos de este repositorio y ejecutar en el entorno de docker el comando "docker build . -t <nombre_imagen>" y luego "docker run -d --name <nombre_contenedor> -p <puerto_host>:<puerto_imagen> <nombre_imagen>".
#
De forma automatica bajando el archivo "compose.yaml" y ejecutar en el entorno de docker el comando "docker-compose up -d".
