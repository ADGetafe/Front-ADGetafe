









![1](https://user-images.githubusercontent.com/106177948/203870518-730d7a8b-4dbf-434e-9489-019de1840610.png)

# Información general 

Página web para la entidad sin ánimo de lucro Asociación de Diabetes de Getafe.



## Hoja de ruta 

Creación de una página web desde el inicio, limpia de fácil acceso con varias secciones, y “fácil de navegar”




# Desarrolladoras 

Alexandra Zambrano

Ainara A. Martinez

Cristina Paucar

Gabriela Gonzalez 

Marcela Blanco

## Tecnologías 

CSS

HTML5

JAVASCRIPT

NODE.js

REACT.js

SASS

## Instalación de React

Requisitos previos instalar `Node.js,` en el Visual Studio Code, a continuación comenzaremos creando un nuevo proyecto con React, con estos comandos 

`npx create-react-app`  y el nombre del proyecto 

Este comando iniciará un proceso de compilación que descargará el código básico junto con varias dependencias.Cuando instaló Node, también instaló una aplicación de administración de paquetes llamada `npm.` 
La aplicación  `npm` instalará paquetes de JavaScript en el proyecto y también llevará un registro de los detalles de este.

Cuando la secuencia de comandos finalice, saldrá un mensaje de operación correcta que indica lo siguiente:  `Success!`

Y a continuación nos dará todas estas posibilidades  para ejecutar : 

`npm star` ( poner en marcha el proyecto)

`npm run build` (empaqueta el proyecto para producción) 

`npm test` (corre los test de prueba)

`npm run eject` (remueve las herramientas, la copia dependencias de compilación, archivos de configuración y scripts en el directorio de la aplicación)

Y luego `Happy hacking!!`

Luego ejecutaremos `npm star` y se abrirá en el navegador el puerto `http://localhost:3000/`, donde se mostrará el logo de React, esto quiere decir que el proyecto funciona correctamente. 

## Instalación y configuración de SASS

Debemos ejecutar el siguiente comando 

`npm install --save-dev node-sass node-sass-chokidar npm-run-all`

Y se agregaran las siguientes dependencias: 

`node-sass`

Este módulo se encarga de compilar los archivos escritos en sass y llevarlos a código css 

`node-sass-chokidar`

Es un wrapper de node-sass con una serie de optimizaciones.

`npm-run-all`

Simplifica el uso de npm scripts, nos permite ejecutar varios scripts de forma paralela.

Luego se tiene que modificar el `package.json`

Cada vez que se cree un archivo nuevo se creará  con la `extensión .scss` el script “watch-css” lo va a compilar y generar un archivo con el mismo nombre y extensión .css en una carpeta llamada /css es decir si creas un archivo llamado `app.scss` se va a compilar a app.css en el mismo directorio donde se  creó y se debe  incluir en los componentes


Continaundo con React, en el directorio del proyecto podremos ver lo siguiente 

`node_modules/` contiene todas las bibliotecas de JavaScript externas que utiliza la aplicación. 

El directorio `Public` contiene algunos archivos de imagen, HTML y JSON. Estos son los directorios root del proyecto.

El directorio` SRC` contiene el código JavaScript React del proyecto. La mayor parte del trabajo se encontrará en este directorio

El archivo `.gitignore` contiene algunos directorios y archivos predeterminados como el control de código fuente. Los elementos ignorados suelen ser directorios o archivos de registro de mayor tamaño que no se necesitará en el control de código fuente.

`README.md` es un archivo markdown que contiene mucha información útil sobre Create React App, como, por ejemplo, un resumen de los comandos y enlaces a la configuración avanzada. 

`package-lock.json` Contiene metadatos sobre el proyecto, como el título, el número de versión y las dependencias. También contiene secuencias de comandos que se pueden usar para ejecutar el proyecto  

`favicon.ico`, `logo192.png` y `logo512.png` son íconos que vienen predeterminados 
 
El archivo `manifest.json` es un conjunto estructurado de metadatos que describe el proyecto. 

El archivo `robots.txt` contiene información para los rastreadores web. Indica a los rastreadores las páginas que tienen permitido o no indexar. 

El archivo `index.html` es el root de la aplicación. Este es el archivo que lee el servidor y el que se visualizará en el navegador. 


Luego para comenzar a trabajar tendremos que hacer una carpeta en el directorio `SRC` y llamarla `“Components”`, en está carpeta agregaremos una carpeta por cada componente de nuestro proyecto. Estos componentes se llamarán iguales pero con extensiones diferentes una `.jsx `y otra `.css`, que es la que tendrá el estilo. 

Si usamos imágenes tendremos que crear una carpeta llamada `ASSETS` e incluirlas ahí. 

Luego de terminar el proyecto tendremos que compilarlo y enviarlo a producción y para eso ejecutamos el comando 

`npm run build`

La compilación del código tomará un tiempo y, cuando se complete, tendremos un directorio nuevo denominado `build/.`

El directorio `build` toma todo el código y lo compila y reduce al menor estado utilizable. Esta reducción hará que el código ocupe menos espacio, pero siga funcionando. Y ya está listo para subir el proyecto al servidor. 




 






















