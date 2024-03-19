# Instalación de Git en Windows 🖥️

1. **Descarga Git:**
   - Visita el [sitio web oficial de Git](https://git-scm.com/download/win).
   - Haz clic en el enlace de descarga para la versión más reciente.

2. **Ejecuta el instalador:**
   - Abre el archivo descargado y sigue las instrucciones del instalador.
   - Asegúrate de seleccionar "Usar Git desde el símbolo del sistema" durante la instalación.

3. **Configuración inicial:**
   - Abre la consola de Git Bash desde el menú de inicio.
   - Configura tu nombre de usuario y dirección de correo electrónico:
     ```bash
     git config --global user.name "Tu Nombre"
     git config --global user.email "tu@email.com"
     ```

## Crear una cuenta en GitHub 🌐

1. **Accede a GitHub:**
   - Visita [https://github.com](https://github.com).
   - Haz clic en "Sign up" para crear una nueva cuenta.

2. **Completa el formulario:**
   - Rellena el formulario con tu nombre de usuario, dirección de correo electrónico y contraseña.

3. **Verifica tu correo electrónico:**
   - Abre tu correo electrónico y sigue el enlace de verificación enviado por GitHub.
  
## Crear token de desarrollador en GitHub 🌐

1. Ve a la página de configuración de tu cuenta de GitHub.
2. En el menú de la izquierda, selecciona **"Developer settings"** (Configuración de desarrollador).
3. Haz clic en **"Personal access tokens"** (Tokens de acceso personal).
4. Luego, selecciona **"Generate new token"** (Generar nuevo token).
5. Selecciona los alcances (scopes) necesarios para tu token, por ejemplo, acceso de lectura a repositorios públicos y privados o capacidad para crear gists.
6. Haz clic en **"Generate token"** (Generar token).
7. Una vez generado el token, cópialo y guárdalo en un lugar seguro. 📝 **No lo compartas públicamente ni lo incluyas en tu código fuente.**
8. ¡Listo! Ahora puedes usar este token en tus aplicaciones o integraciones. 🚀

## Comandos básicos de Git ⚙️

1. **Iniciar un nuevo repositorio:**
   - Crea un nuevo directorio: `mkdir nombre-repositorio`
   - Ingresa al directorio: `cd nombre-repositorio`
   - Inicia un nuevo repositorio Git: `git init`

2. **Clonar un repositorio existente:**
   - `git clone url-del-repositorio`

3. **Añadir y confirmar cambios:**
   - Añadir archivos al área de preparación: `git add nombre-archivo`
   - Confirmar cambios: `git commit -m "Mensaje descriptivo"`

4. **Revisar el estado de los cambios:**
   - `git status`

5. **Sincronizar con un repositorio remoto:**
   - Agregar un repositorio remoto: `git remote add origin url-del-repositorio-remoto`
   - Enviar cambios al repositorio remoto: `git push -u origin rama`

6. **Actualizar y fusionar cambios:**
   - Obtener cambios del repositorio remoto: `git pull origin rama`
   - Fusionar cambios de una rama a otra: `git merge nombre-de-la-rama`

7. **Explorar la historia del repositorio:**
   - Ver el historial de confirmaciones: `git log`

8. **Ramificaciones (Branches):**
   - Crear una nueva rama: `git branch nombre-de-la-rama`
   - Cambiar a una rama existente: `git checkout nombre-de-la-rama`

9. **Etiquetas (Tags):**
   - Crear una etiqueta ligera: `git tag nombre-de-la-etiqueta`
   - Crear una etiqueta anotada: `git tag -a nombre-de-la-etiqueta -m "Mensaje descriptivo"`

Este manual básico debería proporcionarte los fundamentos para comenzar con Git en Windows y GitHub. ¡Buena suerte en tus proyectos! 🚀
