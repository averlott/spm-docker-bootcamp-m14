# spm-docker-bootcamp-m14
version docker del wrapper de una aplicación web java (openjdk) para administrar contraseñas

# construcción y prueba
De forma manual bajando los archivos de este repositorio y ejecutar en el entorno de docker el comando "docker build . -t <nombre_imagen>" y luego "docker run -d --name <nombre_contenedor> -p <puerto_host>:<puerto_imagen> <nombre_imagen>".

De forma automática bajando el archivo "compose.yaml" y ejecutar en el entorno de docker el comando "docker-compose up -d".

En ambos casos para poder probarlo ejecutar el comando "curl localhost:<puerto_host>" o bien setear un puente con ssh para poder ejecutarlo via browser.
