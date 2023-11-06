# GIT Básico
## se utiliza como portada de los documentos, imagenes 
1. crear .gitignore y README.MD
2. Iniciar: git init
3. configurar: git config [--global] user.name minombre
git config [--global] user.email miemail
git config --global core.autocrlf true (si es windows) input(mac o linux)
git config --global core.editor "code --wait" //aquí le decimos que todos mis proyectos serán editados con visual estudio
git config --global -e para saber la configuracion
4. git status, nos dice la informacion de nuestro proyecto
5. git add, pasamos al stage, segundo estado. git add (los archivos que queremos cambiar de estado)
otra opcion para añadirlo es git add .
6. Lo pasamos al commit (version 1)
git commit -m "el mensaje que queremos que acompañe a esta version que subimos" (-m de mensaje)
version 2: hacer el add y commit a la vez
git commit -a -m 