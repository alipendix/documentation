# Comandos Docker 🐳

Estos son algunos de los comandos más habituales que puedes necesitar a la hora de trabajar con Docker.

1. **docker pull** 🚚  
   Descargar una imagen desde Docker Hub.
   ```bash
   docker pull nombre_imagen:tag
   ```

3. **docker run** 🏃  
   Crear y ejecutar un contenedor a partir de una imagen.  
   ```bash
   docker run -d --name mi_contenedor -p 8080:80 nombre_imagen
   ```

4. **docker ps** 📊  
   Listar contenedores en ejecución.  
   ```bash
   docker ps`
   ```
   
6. **docker ps -a** 📋  
   Listar todos los contenedores (incluso los detenidos).  
   ```bash
   docker ps -a
   ```

7. **docker stop** ⏹️  
   Detener un contenedor en ejecución.  
   ```bash
   docker stop mi_contenedor
   ```

9. **docker rm** 🗑️  
   Eliminar un contenedor detenido.  
   ```bash
   docker rm mi_contenedor
   ```
11. **docker images** 🖼️  
   Listar las imágenes descargadas.  
   ```bash
   docker images
   ```

13. **docker rmi** 🗑️  
   Eliminar una imagen.  
   ```bash
   docker rmi nombre_imagen:tag
   ```

14. **docker exec** 🛠️  
   Ejecutar un comando dentro de un contenedor en ejecución.  
 
   ```bash
   docker exec -it mi_contenedor comando
   ```

15. **docker logs** 📜  
   Ver los registros de un contenedor.  
   
   ```bash
   docker logs mi_contenedor
   ```

16. **docker acceder un contendor con permisos para instalar** 📜  
   Este comando permite acceder a un contenedor con permisos suficientes para instalar o actualizar.
   
   ```bash
   docker exec -u 0 -it mi_contenedor /bin/bash
   podman exec -u 0 -it mi_contenedor /bin/bash
   ```
