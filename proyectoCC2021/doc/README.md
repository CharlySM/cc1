Se va a explicar los pasos seguidos para la creación del repositorio del proyecto.

# 1. Descarga de Git
  Se ha instalado git en un sistema operativo linux y se usan los comandos de git desde consola linux.

# 2. Creación de par de claves y subida de clave pública a GitHub.
  * Pimero creamos la clave pública como se indica en la documentación de [github](https://docs.github.com/es/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
  * Después creamos la clave pública en github accediendo a settings -> ssh and GPG keys -> new ssh key.

  ![Ir a settingss](https://github.com/CharlySM/cc1/blob/features/hito0/proyectoCC2021/doc/img/goSettings.PNG "Ir a settings")

  ![Ir a SSH and GPG keys](https://github.com/CharlySM/cc1/blob/features/hito0/proyectoCC2021/doc/img/goSSH.PNG "Ir a SSH and GPG keys")

  * Copiamos la clave pública creada en linux y acceptamos.

  ![Clave creada](https://github.com/CharlySM/cc1/blob/features/hito0/proyectoCC2021/doc/img/keyCreada.PNG "Clave creada")

# 3. Configuración correcta del nombre y correo electrónico para que aparezca en los commits.
  Agregamos la dirección de correo electrónico para que aparezca en commits como se indica en la dcumentación de [github](https://docs.github.com/es/github/setting-up-and-managing-your-github-user-account/managing-email-preferences/setting-your-commit-email-address)
  Mostramos el correo para que aparezca en los commits.

  ![Correo apareciendo en commits](https://github.com/CharlySM/cc1/blob/features/hito0/proyectoCC2021/doc/img/correo.PNG "Correo apareciendo en commits")

# 4. Edición del perfil de GitHub para que aparezca una imagen en vez del avatar por omisión, nombre completo y ciudad, así como universidad.
  Esta parte se realizó en la asignatura de Infraestructura virtual del grado de ingeniería informática de la Univesidad de Granada.

# 5. Incrementar la seguridad de nuestra cuenta en GitHub activando el segundo factor de autenticación.
  * Primero vamos a Settings -> Account Security -> Enable Two factor authentication

  ![Página factor autenticacion dos pasos](https://github.com/CharlySM/cc1/blob/features/hito0/proyectoCC2021/doc/img/autentication.PNG "Página factor autenticacion dos pasos")

  Lo activamos por app o por sms.

  * Activación.

  ![Activacion autentificacion dos pasos](https://github.com/CharlySM/cc1/blob/features/hito0/proyectoCC2021/doc/img/activacion.PNG "Activacion autentificacion dos pasos")

# Creación del repositorio y configuración de git
Para crear el repositorio se ha creado la carpeta de proyecto en local añadiendo los ficheros se necesitaban.

Para el [issue 1](https://github.com/CharlySM/cc1/issues/5) del hito 0, se añadió un fichero readme.md en la carpeta del proyecto.

Para añadir la documentación se ha añadido dentro de la carpeta el proyecto una carpeta llamada doc y dentro de doc, se ha añadido un fichero readme.md (este mismo fichero) donde se explica la configuración de git y la creación de la carpeta del proyecto. Esto se ha hecho en el [issue 2](https://github.com/CharlySM/cc1/issues/7) del hito 0.

Se ha incluido el fichero de licencia dentro de la carpeta del proyecto, aunque este fichero ya estaba en la [carpeta del repositorio cc1](https://github.com/CharlySM/cc1). Esto se ha hecho para el [issue 3](https://github.com/CharlySM/cc1/issues/10) del hito 0.

Se ha añadido también el fichero [.gitignore](https://github.com/CharlySM/cc1/blob/main/proyectoCC2021/.gitignore) actualmente esta vacío pero se espera que a lo largo del desarrollo de la asignatura se empiece a añadir ficheros que se excluyan en el .gitignore.

Despues de la creación del fichero se subió a git usando el comando ```git push origin features/hito0``` siendo features/hito0 la rama donde se esta subiendo lo realizado el hito 0. Después cuando se terminó el hito 0 en la rama mencionada se hizo un pull request a la rama main del repositorio
