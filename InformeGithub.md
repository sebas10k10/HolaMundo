Informe del proceso
Este es proyecto simple donde vamos a subir un archivo de python a github.

Pasos realizados
1.Creamos una carpeta en el escritorio mundo_hola para almacenar nuestros archivos
2.Creamos un docuemnto en python con la frase "Hola mundo"
3.Abrimos Git y subimos los documentos con los sifuientes comandos:
3.1 Abrimos un repositorio en Git con el siguiente comando: 
git init
3.2 Configura Git con nuestro usuario y correo electronico con los siguiente comando: 
git config --global user.name "Sebasthian"
git config --global user.email "sebasclavijo10k@gmail.com"
4.Ahora agregamos los archivos al repositorio en Git con el sguiente comando:
git add .
5.Agregamos el primer comid con el siguiente codigo:
git commit -m "Primer commit: agregar código y reporte"
6.Vinculamos el repositorio remoto de Github con el siguiente codigo:
git remote add origin https://github.com/sebas10k10/HolaMundo.git
Finalmente subimos los archivos con el siguiente comando
git push -u origin master