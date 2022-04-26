 ¿Descubriste las diferencias? :nerd:

Dijimos que `and` solo retorna `True` cuando ambos booleanos son `True`. Por el otro lado, para que `or` sea verdadero alcanza con que al menos uno de los booleanos lo sea. Dicho de otra manera, ambas condiciones deben ser falsas para que retorne `False`. Por ejemplo en...

``` python
ム str.upper("mumuki") == "Mumuki" or "amor" in "romance"
```

... tanto `str.upper("mumuki") == "Mumuki"` como `"amor" in "romance"` devuelven `False`. Si probamos con los booleanos directamente veremos que:

```python
ム False or False
False
ム True or False
True
ム False or True
True
ム True or True
True
```


