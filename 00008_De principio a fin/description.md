Como vimos, `includes` nos puede decir si un string está incluído en otro. Hay dos casos particulares de esta operación: cuando un string comienza, o termina, con otro. 

La sintaxis de estas operaciones es _muyyy_ parecida a lo que venimos haciendo. Por ejemplo la operación que devuelve si un `string` comienza con otro es `unString.startsWith(otroString)`, mientras que la que nos dice si termina con otro es `unString.endsWith(otroString)`. :eyes:

> Probalas en la consola escribiendo:
>
>``` javascript
ム "Fundación e imperio".startsWith("Fundación")
```
>
>``` javascript
ム "Bueno, y sí".endsWith("y sí")
```
>
>``` javascript
ム "Hola, ¿qué tal?".endsWith("Hola")
```