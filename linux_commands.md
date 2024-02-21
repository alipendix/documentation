# Comandos de Terminal en Linux 🐧💻

## 1. Comando **`ls`** 📂

El comando **`ls`** se utiliza para listar los archivos y directorios dentro de un directorio. Puedes combinarlo con otros parámetros, como **`-l`**, para ver información detallada.

- **`ls -l`**: Muestra el listado en columnas con detalles.
- **`ls /nombre-directorio`**: Lista el contenido del directorio especificado.

## 2. Comando **`cd`** 🗂️

Con el comando **`cd`** puedes cambiar el directorio actual en la terminal.

- **`cd ..`**: Sube un nivel en la jerarquía de directorios.
- **`cd /nombre-directorio`**: Abre el directorio especificado en la ruta.

## 3. Comando **`pwd`** 📍

El comando **`pwd`** muestra el nombre del directorio actual en la terminal.

## 4. Comando **`cat`** 🐱

El comando **`cat`** se utiliza para ver el contenido de un archivo o crear uno.

- **`cat nombre-archivo.txt`**: Muestra el contenido del archivo.
- **`cat > nombre-archivo.txt`**: Crea un archivo para editar.
- **`cat archivo1 archivo2 > archivo3.txt`**: Copia el contenido de varios archivos a uno nuevo.

## 5. Comando **`mkdir`** 📁

El comando **`mkdir`** se usa para crear directorios desde la línea de comandos.

- **`mkdir Directorio1`**: Crea un directorio con el nombre especificado.
- **`mkdir Directorio1/Directorio2`**: Crea Directorio2 dentro de Directorio1.

## 6. Comando **`rmdir`** 🗑️

El comando **`rmdir`** elimina directorios vacíos.

- **`rmdir Directorio1`**: Elimina Directorio1 si está vacío.
- **`rmdir Directorio1/Directorio2`**: Borra Directorio2.

## 7. Comando **`touch`** ✍️

El comando **`touch`** crea un documento listo para su edición.

- **`touch archivo1.txt`**: Crea un archivo simple.
- **`touch archivo1.txt archivo2.txt archivo3.txt`**: Crea varios archivos.

## 8. Comando **`rm`** 🗑️

El comando **`rm`** se utiliza para borrar archivos.

- **`rm archivo1.txt`**: Elimina el archivo indicado.
- **`rm -r`**: Elimina todos los archivos y subdirectorios.

## 9. Comando **`cp`** 📋

El comando **`cp`** copia archivos.

- **`cp ejemplo.txt /home/directorio1`**: Copia el archivo en directorio1.
- **`cp * home/directorio1`**: Copia todos los archivos al directorio indicado.

## 10. Comando **`sudo`** 🛡️

El comando **`sudo`** otorga privilegios de SuperUsuario para tareas específicas.

- **`sudo apt-get update`**: Actualiza los paquetes del sistema.

## 11. Comando **`top`** 🔄

El comando **`top`** muestra procesos activos y consumo de recursos en tiempo real.

- **`top`**: Muestra el listado de procesos.
- **`top -d 20`**: Refresca cada 20 segundos.

## 12. Comando **`man`** 📚

El comando **`man`** muestra el manual de funciones para un comando específico.

- **`man top`**: Muestra funciones disponibles para **`top`**.

## 13. Comandos **`zip`/`unzip`** 📦

- **`zip nombre-archivo.pdf`**: Comprime el archivo en .zip.
- **`zip Ejemplo.zip archivo1.txt archivo2.pdf`**: Comprime varios archivos en **`Ejemplo.zip`**.
- **`unzip Ejemplo.zip`**: Descomprime el archivo en el directorio actual.

## 14. Comando **`tar`** 🗜️

- **`tar cvf comprimido.tar Directorio1`**: Comprime Directorio1 en **`tar`**.
- **`tar xvf comprimido.tar -C /home/Directorio2`**: Descomprime en Directorio2.

## 15. Comando **`locate`** 🔍

- **`locate archivo1`**: Busca archivos con el texto "archivo1".
- **`locate -r archivo1`**: Búsqueda sin distinguir mayúsculas.

## 16. Comando **`find`** 🔍

- **`find . -name archivo1.txt`**: Busca archivo1.txt en el directorio actual.
- **`find . -type f -iname "*.txt"`**: Encuentra archivos .txt en el directorio.

## 17. Comando **`mv`** 🔄

El comando **`mv`** mueve o renombra archivos.

- **`mv /Directorio1/archivo1.txt /Directorio2/`**: Mueve a Directorio2.
- **`mv /Directorio1/archivo1.txt /Directorio1/archivo2.txt`**: Cambia el nombre.

## 18. Comando **`cp`** 📋

Si quieres copiar en lugar de mover, utiliza el comando **`cp`**.

- **`cp archivo1.txt /Directorio2/`**: Copia a Directorio2.

## 19. Comando **`df`** 📊

El comando **`df`** muestra información sobre el espacio de almacenamiento.

## 20. Comando **`du`** 📏

El comando **`du`** indica el espacio ocupado por archivos o directorios.

- **`du -h /Directorio1`**: Muestra el tamaño en formato humano.
- **`du -a /Directorio1`**: Muestra tamaños de archivos en Directorio1.

## 21. Comando **`chmod`** 🔐

El comando **`chmod`** gestiona permisos de archivos y directorios.

- **`chmod 644 archivo1.txt`**: Establece permisos de lectura y ejecución.

## 22. Comando **`kill`** 🚫

El comando **`kill`** cierra aplicaciones en Linux.

- **`kill -9 52661`**: Cancela el proceso 52661 con la señal SIGKILL.

## 23. Comando **`ping`** 🌐

El comando **`ping`** verifica la conexión a un servidor o sitio web.

## 24. Comando **`grep`** 🔍

El comando **`grep`** busca texto en archivos.

- **`grep -w horario /home/archivo1.txt`**: Busca la palabra 'horario' exacta.

## 25. Comando **`wget`** 🌐

El comando **`wget`** descarga archivos desde URL o FTP.

- **`wget https://url-ejemplo.com/archivo1.txt`**: Descarga archivo1.txt.
- **`wget https://url-ejemplo.com/*.txt`**: Descarga todos los archivos .txt.

