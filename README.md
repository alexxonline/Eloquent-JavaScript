# Eloquent JavaScript en español

En este repositorio está el código fuente de la versión en español del libro
Eloquent JavaScript. Pueden consultar sobre el libro original (en inglés).
en (https://eloquentjavascript.net).

El libro original va por su tercera edición y aún no hay ninguna versión en español terminada.
Empecé este repositorio porque en las versiones en español que andan por ahí no me gustó el tono 
de la traducción.

Al igual que el libro original, el feedback es bienvenido a través de los issues y pull request de GitHub.

## Cómo compilar

    npm install
    make html

Para compilar el PDF:

    apt-get install texlive texlive-xetex fonts-inconsolata fonts-symbola texlive-lang-chinese inkscape
    make book.pdf
    
## Como contribuir

El libro original es un libro que tiene mucho texto así que sería mejor contar
con ayuda para hacer una traducción que sea mejor para todos. Como se dijo antes
se pueden hacer issues y pull request. 

Probablemente el proceso para contribuir se elabore de forma mas detallada más
adelante pero por lo pronto. 

- Se pueden comentar errores y sugerencias a través de los Issues.
- Si alguien desea contribuir puede hacer un pull request en este caso para aceptar 
un pull request entre otras cosas se va a evaluar que:
    - El libro compile en todos sus formatos incluyendo PDF.
    - La traducción no tenga tono robótico como si hubiese sido hecha por un traductor automático.
    - La traducción no contenga errores de ortografía.
    - La traducción respete el significado y tono del libro original.
    
## Licencia

Al igual que el libro original tanto los fuentes como versiones compiladas tienen la licencia
[Creative Commons attribution-noncommercial license](https://creativecommons.org/licenses/by-nc/3.0/)
y el código del libro la [licencia MIT](https://opensource.org/licenses/MIT).
