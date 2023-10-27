# examenDAM

# Explicación de los pasos

1. Primero entro al repositorio que quiero clonar. Hago fork y se crea un repositorio remoto. Despues hago clone de este nuevo repositorio remoto.
    - "git clone 'enlace'" -> Comando para clonar el repositorio a mi ordenador

2. Añado el programa creado y creo una nueva clase que quiero ignorar.

3. Añado la nueva clase a .gitignore desde IntellIJ, dándole click derecho y añadir a git ignore.

4. Creo el jar ejecutable yendo a File-Project Structure. Creo un nuevo artefacto JAR y le cambio el lenguaje de JAVA a la versión 8 para que funcione en todos los ordenadores.

5. Vamos build y hacemos build artifacts y se crea una nueva carpeta out donde se encuentra el archivo jar.

6. Comprobamos si funciona en la consola con el comando:
    - java -jar 'nombreDelProyecto'.jar

7. Modificio el Readme con los pasos y ejecuto los comandos:
    - git add .. -> Comando para añadir los archivo modificados que quiero subir a mi repositorio remoto
    - git commit -m "mensaje" -> Comando para añadir el mensaje que va fijado al cambio que hice, tiene que ser un mensaje corto y descriptivo de los cambios
    - git push -u origin main -> Comando para subir los cambios junto al commit a mi repositorio remoto.
Escribo mi cuenta y mi token
