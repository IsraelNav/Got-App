### Reconstruccion de Node_Modules #####
Para reconstruir todos los paquetes y dependencias del proyecto
debemos ejecutar en la consola el comando npm i una vez posicionado en la carpeta raiz del proyecto

#### GOT APP #####
Got App, es una aplicacion la cual se ha construido para poder visualizar personajes de la serie
Game of Thrones, donde podremos ver el nombre y la imagen de los personajes, ademas de un detalle
de estos, para asi poder conocer mas informacion sobre los distintos personajes de la serie

#### Funcionamiento de la App #####
Una vez reconstruidos los paquetes con npm i, ejecutamos el comando npm start para levantar la aplicacion
una vez iniciada la aplicacion nos encontraremos con la pagina principal (HomePage),
donde se visualizara un mensaje de bienvenida.

Luego en la parte superior izquierda tendremos 2 links, Home / Characters
 
Home: Para volver a la pagina principal (HomePage)
Characters: Para poder visualizar todos los personajes de la serie

Si seleccionamos Characters podremos visualizar una tarjeta con el nombre, la imagen y un boton
de cada personaje, 

El boton te lleva a la ruta /characters/ById/:id, para poder visualizar el detalle de cada personaje de la serie
donde podras encontrar informacion adicional de este
