nombre: Julian Portillo
codigo: 0192787
programa: Ingenieria de Sistemas

explicacion general:
se evalua uso de la terminal para la creacion de repositorios, documentos, y edicion de texto;
git para el control de versiones, organizar, modificar y publicar el proyecto


creacion del repo:
se debia crear un repo virtual publico en github vacio con un nombre designado quiz-unidad1-nombre
para realizarlo entre a github en el navegador inicie sesion, busque repositorios, crear repositorio,
asigne nombre y lo puse publico, copie la clave https correspondiente y mi token personal para https.
herramientas usadas fueron firefox, github, tokens de github.

construccion del proyecto:
luego de haber creado el repositorio en github se debe crear el repositorio en la pc, esto se logra
sabiendo donde estamos, usando pwd, luego ls para analizar que archivos y carpetas tenemos, ya
sabiendo esto mediante el comando mkdir creamos el directorio principal que debe tener el mismo nombre del repo de github.
adentro de este directorio se crean los primeros archivos mediante touch: datos-estudiante.txt y readme.md.
y se crean sub ramas en el directorio mediante mkdir las cuales son: documentos y practica.
dentro de documentos se crea el archivo reflexion.txt mediante nano para edicion instantanea.
dentro de practica se crea el archivo nota.txt mediante touch debido a que aun no se edita.
se le agrega contenido a datos-estudiante.txt mediante nano.

administracion desde terminal:
primero mediante pwd me ubique, mediante ls analice archivos y carpetas, compruebo si existen elementos ocultos,
ingreso a la carpeta practica mediante cd y con nano mas la ruta del archivo nota.txt lo edito, mediante cd ..
regreso a la carpeta principal.
dentro de la rama documentos se crea el documento objetivos.txt mediante nano para editarlo de una.
y por final compruebo todo mediante ls.

control de versiones:
se prepara el proyecto para usar git mediante git init, lo conectamos con la clave https y mediante git status verificamos que 
archivos estan siendo detectados, mediante git add . preparamos estos archivos para registrar la primera version, para esta primera
version usamos git commit -m "descripcion", se vuelve a comprobar que todo se comiteo mediante git status.

cambio de proyecto e historial:
se realiza una segunda modificacion al proyecto modificando el archivo reflexion.txt mediante nano, usamo git status para confirmar modificaciones
agregamos estos cambios mediante git add, hace un segundo git commit -m "mensaje descriptivo", consultamos el historial del proyecto mediante git log
y se comprueban las dos versiones cargadas.

publicacion a github:
ya teniendo todo preparado usamos el comando git push -u origin main para cargar todo a github como repositorio remoto.
