# Notas proyecto

## Hacer que un grid al posicionarlo no se brinque al siguiente row.

Recuerda usar:

``` 
    grid-auto-flow: dense;
```

Esto hará que los cuadrantes vacios se llenen pegando toda la cuadricula. 
- *Se utilizó en **bloques** en el grid.*

## colocar borde arriba y abajo de un contenedor sin usar top y bottom.
Ahora tenemos la propiedad lógica: 
```
    border-block: 1px solid v.$blanco;
```
Esto nos dará un borde en la parte superior e inferior. 

## Atajo teclado VS code.

Ctrl + D -> Selecciona las que tiene lo mismo que has remarcado con el cursor. Se va seleccionando hacia abajo.

## Alinear cards.
Hay dos enfoques, una es colocar en el contenedor:
```
align-items: start;
```
esto cortará el card y dejara una más pequeña que otra. 

El otro enfoque es colocarle a la sección que crecerá de manera variable (heading, descripción ó texto) un:
```
min-hight: --rem;
```

dandole así una altura mínima y un máximo de caracteres, y así se colocarán alineadas las cards. 