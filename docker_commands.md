1. **docker pull** 🚚  
   Descargar una imagen desde Docker Hub.  
   `docker pull nombre_imagen:tag`

2. **docker run** 🏃  
   Crear y ejecutar un contenedor a partir de una imagen.  
   `docker run -d --name mi_contenedor -p 8080:80 nombre_imagen`

3. **docker ps** 📊  
   Listar contenedores en ejecución.  
   `docker ps`

4. **docker ps -a** 📋  
   Listar todos los contenedores (incluso los detenidos).  
   `docker ps -a`

5. **docker stop** ⏹️  
   Detener un contenedor en ejecución.  
   `docker stop mi_contenedor`

6. **docker rm** 🗑️  
   Eliminar un contenedor detenido.  
   `docker rm mi_contenedor`

7. **docker images** 🖼️  
   Listar las imágenes descargadas.  
   `docker images`

8. **docker rmi** 🗑️  
   Eliminar una imagen.  
   `docker rmi nombre_imagen:tag`

9. **docker exec** 🛠️  
   Ejecutar un comando dentro de un contenedor en ejecución.  
   `docker exec -it mi_contenedor comando`

10. **docker logs** 📜  
    Ver los registros de un contenedor.  
    `docker logs mi_contenedor`
