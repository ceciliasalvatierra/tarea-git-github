¿Qué es Git y para qué se utiliza?
R. Git es un sistema de control de versiones distribuido y sirve para registrar y rastrear cambios que se realizan en los archivos de algun proyecto
¿Qué diferencia hay entre Git y GitHub?
R. Git es un sistema de control de versiones mientras que GitHub es una plataforma para publicar repositorios
Explica en tus palabras qué es un repositorio.
R.Es un tipo de almacenamiento digital en el que se almacenan archivos, codigos, etc
¿Qué significa hacer un commit en Git?
R. Hacer un commit en Git es el acto de guardar una instantánea de los cambios preparados en tu proyecto y registrarla en el historial de versiones local del repositorio
Investiga y explica brevemente los siguientes comandos de Git:
git config --local user.name "<GitHub user name>"
Configura el nombre de usuario que se usará en los commits de ese repositorio.
git config --local user.email "<GitHub email>"
Configura el correo asociado a los commits
git init
Inicia un nuevo proyecto con Git
git add
El comando git add agrega archivos nuevos o modificados en su directorio de trabajo al área de preparación de Git
git commit
Se utiliza para guardar los cambios
git push
Se utiliza para subir los cambios realizados en tu repositorio local a un repositorio remoto
git clone
Se utiliza para crear una copia local completa de un repositorio Git existente
git init --initial-branch=main
Inicializa el repositorio con la rama principal llamada main
git remote add origin https://github.com/<user-name>/tarea-git-github.git
Conecta tu repositorio local con uno remoto en GitHub, llamado origin
git add .
Añade todos los archivos del proyecto al área de preparación
git commit -m "Initial commit"
Crea un commit con el mensaje "Initial commit"
git push --set-upstream origin main
Envía tu rama principal al repositorio remoto y la establece como predeterminada para futuros push
¿Qué es un archivo README.md y por qué es importante?
R. Es un archivo de texto en formato Markdown (.md) que contiene información básica y relevante sobre el proyecto, como su propósito, cómo instalarlo, cómo usarlo, y quién lo hizo.