# Pasos para crear un Repositorio desde cero

Inicializar el repositorio localmente
1. git init

Preparar archivos para el punto de guardado

Agregar un punto "." para incluir todos los archivos en el próximo punto de guardado.

Listar individualmente los archivos si es que queremos omitir alguno

2. git add . 
2. git add nombre_del_archivo.extension

Generar la versión nueva que incluye los archivos que se han agregado en el previo git add

3. git commit -m "Primer commit, agregando archivos del proyceto."

Crear la rama principal de nuestro repositorio llamada main

4. git branch -M main 

Enlazar el repositorio local con nuestra cuenta de Github. Es importante crear el repositorio en nuestra cuenta de Github.

5. git remote add origin url-del-repositorio-recien-creado-en-nuestra-cuenta-github

Enviar el último commit hacia el espacio en nuestro repositorio

6. git push -u origin main


