 ¿Descubriste las diferencias? :nerd:

Dijimos que `&&` solo retorna `true` cuando ambos booleanos son `true`. Por el otro lado, para que `||` sea verdadero alcanza con que al menos uno de los booleanos lo sea. Dicho de otra manera, ambas condiciones deben ser falsas para que retorne `false`. Por ejemplo en...

``` javascript
ム str.upper("mumuki") == "Mumuki" or "amor" in "romance"
```

... tanto `str.upper("mumuki") == "Mumuki"` como `"amor" in "romance"` devuelven `False`. Si probamos con los booleanos directamente veremos que:

```javascript
ム False or False
False
ム True or False
True
ム False or True
True
ム True or True
True
```


