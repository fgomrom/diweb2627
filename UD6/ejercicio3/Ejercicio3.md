|Elemento|	Color|	Tamaño|
|--------|-------|--------|
|Título	Verde|	30 px|
|Primer| párrafo|	Naranja|	18 px
|Segundo| párrafo|	Rojo|	18 px

Explicación:
- El título recibe el color azul de la hoja externa y el verde de la interna. Como ambas reglas tienen la misma especificidad y la misma importancia, prevalece la interna.
- El tamaño del título procede de la hoja externa porque la regla interna no redefine esa propiedad.
- El primer párrafo recibe el color y el tamaño de la hoja interna.
- El segundo párrafo recibe el color rojo de su estilo en línea y el tamaño de la hoja interna.
Al eliminar los estilos internos:
- El título será azul.
- El primer párrafo será negro.
- El segundo párrafo seguirá siendo rojo.
- El segundo párrafo tendrá el tamaño predeterminado del navegador.