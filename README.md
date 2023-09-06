<h1>Configurar un repositorio nuevo desde terminal</h1>
<ol>
    <li>git init</li><!--Inicializa un repositorio vacío en nuestra carpeta-->
    <li>git add</li><!--Agregar archivos nuevos y con cambios a la version actual-->
    <li>git commit -m "dejar mensaje"</li><!--crea una version nueva con los cambios actuales-->
    <li>Ir a github y crear un repositorio vacio</li><!--inicializa un repositorio en github-->
    <li>git add remote origin url-del-github-vacio</li><!--Enlaza el repositorio de nuestra cuenta con el repositorio local-->
    <li>git push -u origin main</li><!--Actualiza la version actual de nuestra carpeta en el repositorio remoto-->
</ol>

<h1>Generar una nueva version y actualizar el repositorio</h1>
<ol>
    <li>git add</li>
    <li>git commit -m "mensaje"</li>
    <li>git push -u origin main</li>
</ol>