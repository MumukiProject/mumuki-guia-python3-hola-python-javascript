¿Descubriste el patrón? :grimacing:

Para que `&&` retorne `true` es necesario que ambas condiciones sean verdaderas. Por eso...

``` javascript
ム 8 < 10 && 8 > 9
```

... retorna `false`, porque 8 es menor a 10 pero no es mayor a 9. Dicho de otra forma, `8 < 10` es `true` pero `8 > 9` es `false`. En cambio al probar...

``` javascript
ム "caracol".startsWith("cara") && “caracol”.endsWith("col")
```

... obtenemos `true`, dado que ambas condiciones son verdaderas. En resumen:

```javascript
ム false && false
false
ム true && false
false
ム false && true
false
ム true && true
true
```


