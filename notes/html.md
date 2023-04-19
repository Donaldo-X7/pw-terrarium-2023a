# HTML
1.[Introducción](#introducción)

## Introducción
HTML (Hyper Text Transfer Protocol) es un lenguaje utilizado 
para estructurar una página web.

Los elements que componen un HTML se asemejan
a los elementos de un cuerpo humnao.
Estos elementos son cabeza (head) y cuerpo (body).

## Partes del HTML

![Elementos Etiqueta](./images/003imagen.jpg)

!DOCTYPE: Una de las primeras etiquetas que deben colocarse
en el HTML es aquella que indica la versión del lenguaje,
en este caso  para HTML 5 se usa este código:

```html
<!DOCTYPE html>
```

EJEMPLO DE LA CLASE 190423:
let plant1 = document.getElementById("plant1")
plant1.addEventListener("click", ()=>{
    let name = prompt("Hola, ¿Cuál es tu nombre?");
    if(name !== ""){
        alert(`${name} please, SAVE THE PLANET! 🌱`);
    }
});