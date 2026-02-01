# Presentación del Proyecto
## **Autor:** María José Castrillón Gutiérrez
*Soy estudiante de segundo semestre de Producción Audiovisual Interactiva. Me interesa la automatización de procesos audiovisuales y la logística de la producción audiovisual de eventos en vivo.* 
## Descripción
Este es el repositorio para la Tarea 1 del curso de Programación Orientada a Objetos. El objetivo es demostrar el flujo de trabajo básico con Git y GitHub.
## Pasos Realizados
1. **Creación del repositorio local:** 
El **init** se usa cuando no existe el repositorio remoto o está vacío, pero en este caso el primer paso fue **clonar** el reposito creado por el profesor en GitHub Classroom de la siguente manera: `git clone https://github.com/PUJ-POO-20252/crear-documento-markdown-mjcastrillon.git`.
Esto crea una carpeta llamada "crear-documento-markdown-mjcastrillon.git" con todos los archivos que ya existan en el repositorio remoto. *Durante este paso tuve problemas porque en vez de clonar el repositorio lo inicializé y luego creé el archivo `presentacion.md`, entonces los dos repositorios estaban divergidos o desincronizados porque en el repositorio remoto ya existía el archivo `README.md` y yo inicializé el repositorio local con `git init` y cuando intentaba hacer `git push` salía el siguiente error: `fatal: refusing to merge unrelated histories`, por esta razón me tocó usar `git pull origin main --allow-unrelated-histories` para unir los dos commits existentes (`presentacion.md` en el local y `README.md` en el remoto), esto lo encontré en internet y así ya pude tener el archivo `README.md` en el repositorio local para poder hacer `git push` del archivo `presentacion.md`.*
2. **Creación de este archivo:** `presentacion.md`.
Creé este archivo y edité el contenido de `README.md` desde Visual Studio Code usando la sintaxis de MarkDown.
3. **Conexión con GitHub:**
