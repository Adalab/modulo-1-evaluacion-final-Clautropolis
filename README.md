# ¡Vuelta al cole! 🚀

Esta es la página web de una tienda de deportes cuyo objetivo es preparar a los niños con la mejor equipación de cara a la vuelta al cole. 
Con este proyecto buscábamos crear un sitio intuitivo, que fuera fácil de manejar para todos los usuarios, tanto con experiencia tecnológica como sin ella.

El proyecto ha sido configurado para ejecutarse con **Node.js y Vite**. 

## Cómo instalar el proyecto

Para instalar el proyecto deberás clonar este repositorio en tu terminal https://github.com/Adalab/modulo-1-evaluacion-final-Clautropolis.git y llevar a cabo los comandos de npm install seguido de npm start.

```bash
git clone https://github.com/Adalab/modulo-1-evaluacion-final-Clautropolis.git

cd modulo-1-evaluacion-final-Clautropolis

npm install

npm start

```

## Estructura del proyecto 

Ya dentro del proyecto, vemos que ha sido creado mediante partials de HTML que se engloban en un index.html que es lo que se muestra en la pantalla. 
Así mismo, el SCSS se ha creado de la misma manera, trabajando en archivos individuales incluidos todos en la carpeta layout que se agrupan en el main.scss, llamado en el head del index.

Además, en la carpeta core, encontramos el archivo de reset, que regenera todos los estilos que vienen por defecto, y el archivo variables, que marca los nombres de las variables que se repiten a lo largo del proyecto y que nos facilitará el tener que hacer cambios en un futuro. 

### Secciones

Dentro de las secciones con las que cuenta el proyecto, encontramos algunas diferencias.

- Header. El header cuenta con un pequeño menú que se compone únicamente de un icono de hamburguesa en el que se encuentran todas las opciones del menú. Por el momento, nos han pedido que estas opciones permanezcan ocultas y no se muestren visibles. Para ello hemos utilizado la propiedad display: none. Era un requisito del cliente que el menú de la hamburguesa fuera visible en todo momento.

- Primera sección. Ha sido maquetada utilizando la propiedad display: flex. Y se ha utilizado la propiedad background-image para el fondo de la sección, que debe ocupar todo el alto de la pantalla. Además, el botón de la flecha que aparece debe de llevar al usuario a la sección de vuelta al cole que aparece más abajo.

- Segunda sección. La sección que lleva a la tienda debía contar con un botón que diera acceso a ella que cambia de color si pasas el ratón por encima, lo que facilita al usuario a la hora de identificar que es una parte clicable.

- Tercera sección. En esta sección tenemos 3 categorías diferentes que deben ser maquetadas con la propiedad de display: grid. Esta sección es una de las que más cambios representaba a la hora de implementar los media queries para hacer un diseño responsive.

- Footer. Todos los elementos de las listas del footer debían de ser clicables. Al igual que el botón de la flecha hacia arriba, que nos lleva a la primera sección de todas. Esta sección también ha sido maquetada con display: grid, con el objetivo de facilitar su disposición en los cambios de los media queries.

## Tecnología utilizada

Las tecnologías que hemos utilizado en este proyecto son:
- **HTML5**: Para llevar a cabo una estructura indentada correctamente y utilizar las etiquetas semánticas adecuadas para hacer el proyecto accesible.
- **CSS3**: Incluye el uso de las propiedades Flexbox y Grid, utilizando selectores de clase.
- **SASS**: Uso de algunas caracterísitcas como las variables, la anidación y los partials. 
- **BEM**: Uso del sistema BEM para nombrar las clases y facilitar la anidación. Priemro el nombre de la sección de la que encuentra el elemento, seguido de su funcionalidad dentro de la sección y por último con alguna especificidad concreta y única del elemento.
Ejemplo: header__menu--items.
- **Media Queries**: Para hacer que el proyecto sea responsive y se ajuste a las diferentes pantallas utilizadas hoy en día se han implementado varios media queries. Uno cuando wl width de la pantalla supera los 768px y otro cuando supera los 1280px.

Espero que te haya resultado interesante este proyecto. Si tienes alguna pregunta, no dudes en contactar. ¡Muchas gracias!

