# Amigosecreto
reto de challenge de amigo secreto para reforzar logica de programación
### Practicando lógica de programación: Challenge Amigo secreto
Practicar la lógica de programación, incluyendo conceptos como variables, arreglos, condicionales e interacciones con el usuario (alert, prompt), que es esencial en desarrollo de software.

Comprender estos conceptos nos facilita el aprendizaje de lenguajes y tecnologías,para crear soluciones inovadoras,dentro del campo de la programación.

1.Muestra una alerta con el mensaje "Debes colocar el nombre de un amigo".
```javascript
alert('Debes colocar el nombre de un amigo');
```

2.Colocamos un campo de texto .
```javascript
const inputAmigo = "amigo";
```

3.Creamos un arreglo llamado listaAmigos.
```javascript
const listaAmigos = [];
```

4.Imprimimos en la pagina una ulListaAmigos, con la que incrementa de acuerdo a los que el usuario quiera colocar.
```javascript
const ulListaAmigos=document.getElementById("listaAmigos")
```

5.Agregamos un boton de Añadir el cual va agregando el nombre de los amigos secretos y utiliza la funcion de agregarAmigo.
```javascript
function agregarAmigo();
```

6. Al final llamamos a la funcion de SortearAmigo con el botton Sortear amigo
```javascript
function sortearAmigo();
```

10.Ahora, muestra en la pagina el nombre del amigo sorteado, seleccionando aleatoriamente entre cada uno de los nombre que se añidieron.
```javascript
ulResultado.innerHTML=`<li>El Amigo Secreto sorteado es: ${amigoSecreto}</li>`;
```
