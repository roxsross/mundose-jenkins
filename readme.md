docker build -t nombre_app:etiqueta .
docker images
docker run --name nombre_imagen -e prueba=1234 -e hola=1234 -d -p hostport:port nombre_app:etiqueta 
           -it -p

docker ps

docker create network 