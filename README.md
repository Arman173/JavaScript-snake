# Notas:

Juego de snake con HTML5, CSS Y JavaScript, la información del puntaje máximo se guarda en el localStorage del navegador.


En la parte del canvas en el index.html, al cambiar el tamaño del canvas, el valor del 
width y height deben ser iguales
```
<canvas id="canvasGame" width="500" height="500"></canvas>
```


Con estas variables se puede cambiar el color de la serpiente y de la manzana
```
// este codigo se encuentra en "script/game.js" en las lineas: 15 y 16

let snakeColor = 'green';
let appleColor = 'red';
```