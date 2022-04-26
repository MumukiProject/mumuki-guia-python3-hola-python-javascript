¿Descubriste el patrón? :grimacing:

Para que `and` retorne `True` es necesario que ambas condiciones sean verdaderas. Por eso...

``` python
ム 8 < 10 and 8 > 9
```

... retorna `False`, porque 8 es menor a 10 pero no es mayor a 9. Dicho de otra forma, `8 < 10` es `True` pero `8 > 9` es `False`. En cambio al probar...

``` python
ム str.startswith("caracol", "cara") and str.endswith("caracol", "col")
```

... obtenemos `True`, dado que ambas condiciones son verdaderas. En resumen:

```python
ム False and False
False
ム True and False
False
ム False and True
False
ム True and True
True
```


