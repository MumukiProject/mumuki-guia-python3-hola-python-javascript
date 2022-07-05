 Como acabamos de ver, en JavaScript existen números, booleanos y strings:

|  Tipo de dato |  Representa             |  Ejemplo |  Operaciones                   |
|---------------|-------------------------|----------|--------------------------------|
|Números        |cantidades               | `4947`   | `+`, `-`, `*`, `/`, `<`, etc .  |
|Booleanos      |valores de verdad        | `true`   | `&&`, <code>&#124;&#124;</code> , etc. |
|Strings        |texto                    | `"¡hola JavaScript!"` | `toUpperCase`, `startsWith`, `length` |


Además, existen operaciones que sirven para todos los _tipos de datos_, por ejemplo:

* `===`: nos dice si dos cosas son iguales;
* `!==`: nos dice si dos cosas son diferentes.

**Es importante usar las operaciones correctas con los tipos de datos correctos**, por ejemplo, no tiene sentido sumar dos booleanos o hacer operaciones booleanas con los números. **Si usas operaciones que no corresponden, cosas muy raras y malas pueden pasar**. :confounded:

> Probá en la consola lo siguiente:
>
>``` javascript
ム 5 + 6
```
>
>``` javascript
ム 5 === "5"
```
>
>``` javascript
ム 8 > 6
```
>
>``` javascript
ム false / true
```
>
>``` javascript
ム 'hola' || 'chau'
```
> ¿Todas estas operaciones tienen sentido?