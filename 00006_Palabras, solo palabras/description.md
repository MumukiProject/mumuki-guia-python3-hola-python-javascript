Ya conocimos a los números y a los booleanos de Python, ¡pero eso no es todo!

Muchas veces queremos escribir programas que trabajen con texto :page_facing_up:: queremos saber cuántas palabras hay en un libro, o convertir minúsculas a mayúsculas, o saber en qué parte de un texto está otro.

Para este tipo de problemas tenemos los _strings_, también llamados _cadenas de caracteres_:

* `"En 15 minutos estoy"`
* `'El hierro nos ayuda a jugar'`
* `"¡Hola Miguel!"`

Como se observa, todos los strings están encerrados entre comillas simples o dobles. ¡Da igual usar unas u otras! Pero sé consistente: por ejemplo, si abriste comilla doble, tenés que cerrar comilla doble. Además, un string puede estar formado por (casi) cualquier carácter: letras, números, símbolos, espacios, etc.

¿Y qué podemos hacer con los strings? Por ejemplo, compararlos, como a cualquier otro valor:

```python
ム "hola" == "Hola"
False

ム "todo el mundo" == "todo el mundo"
True
```

y también concatenarlos, es decir, obtener un string a partir de la unión de otros. :chains:

> Probá en la consola lo siguiente:
>
``` python
ム "guarda" + "polvos"
ム "Hola, " + "¿cómo estás?"
ム "Dame " + str(5)
ム 'Mari' + 'posa'
```