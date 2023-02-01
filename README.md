# Proj1_Graficacion

## Cómo visualizar el código (básicamente como yo lo hice jsjsjs):

1. Descargar el código (por zip, clonar el repositorio, o lo que sea)
2. Si se tiene como zip, extraer el contenido del zip en una carpeta.
Nota: Yo usé Visual Studio Code como mi editor de código porque tiene una extensión que permite simular el host del código en localhost sin tener que instalar programas extra (como python, se evita instalar python básicamente) + tiene otras cosas buenas para la edición de html :)
3. Abrir VSCode (Visual Studio Code) y arrastrar la carpeta que tiene el código hacia la ventana de VSCode para abrirlo como proyecto.
    * Si VSCode pregunta por confiar en el proyecto, se debe poner que sí, de lo contrario puede que la página no se ejecute correctamente por los archivos de Javascript.
    * Si te da miedito confiar en los archivos, puedes ver el texto de hasta abajo.
4. Instalar la extensión **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** en VSCode.
5. Abrir el archivo **`webgl_geometry_text.html`** ubicado en `./page/` (o sea el archivo `./page/webgl_geometry_text.html`) desde VSCode.
6. Si se instaló correctamente la extensión Live Server, al tener abierto un archivo html deberá aparecer un ícono como de torre de conexión junto al texto "*Go Live*", si aparece hay que hacer click ahí :) si no aparece algo salió mal :(
7. Al presionar ***Go Live***, deben pasar 2 cosas:
    1. El ícono de la torre de conexión cambiará a un signo como 🚫 junto al texto "*Port : XXXX*" (XXXX sería un puerto asignado por la extensión, en mi caso es 5500), quedando algo como "🚫 Port : 5500".
    2. Se abrirá tu navegador web (Chrome, Edge, Firefox, Opera, Brave, Vivaldi o lo que tengas) en la dirección http://127.0.0.1:5500/page/webgl_geometry_text.html o http://localhost:5500/page/webgl_geometry_text.html, si no abre la página puedes abrirla manualmente e igual debería aparecer el host local corriendo.
    * Si no pasa ninguna de las cosas anteriores, algo salió mal :(
    * Si ambas cosas pasan, todo bien y ya puedes empezar tu proyecto, feliz navidad :)
    

<details>
<summary><bold>Zona para desconfiad@s</bold></summary>

   ### En caso de que no confíes en el repo:

   Por qué no confias? soy buena gente 😠. Soy tan buena gente que te puedo decir que si no quieres descargar el código de aquí, puedes ir al link https://github.com/mrdoob/three.js/ y descargar el código directamente de ahí y simplemente copiar lo mismo que hay aquí, este repositorio simplemente está hecho para ahorrarte la búsqueda de archivos y la selección de lo necesario.

   Lista de lo que debes descargar del repositorio de [three.js](https://github.com/mrdoob/three.js/):
   
   1. [three.js/examples/webgl_geometry_text.html](https://github.com/mrdoob/three.js/blob/dev/examples/webgl_geometry_text.html)
   2. [three.js/examples/jsm/](https://github.com/mrdoob/three.js/tree/dev/examples/jsm)
   3. [three.js/examples/fonts/](https://github.com/mrdoob/three.js/tree/dev/examples/fonts)
   4. [three.js/examples/main.css](https://github.com/mrdoob/three.js/blob/dev/examples/main.css)
   5. [three.js/build/](https://github.com/mrdoob/three.js/tree/dev/build)
   
   Eso es básicamente todo lo necesario para correr la página, es literalmente el mismo código que el de este repositorio (creo que es exactamente igual, no recuerdo si cambié alguna cosa antes de subirlo aquí), así que se comportará igual que si clonaras/descargaras este repositorio, si decides descargar los archivos desde el repositorio de three.js tendrás que asegurarte de acomodarlos en sus ubicaciones correctas, puedes simplemente basarte en las direcciones de archivos que están en la lista (por ejemplo `three.js/examples/jsm`) y acomodarlos en tu computadora de la misma forma.
</details>
