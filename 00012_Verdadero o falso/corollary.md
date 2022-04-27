 ¿Descubriste las diferencias? :nerd:

Dijimos que `&&` solo retorna `true` cuando ambos booleanos son `true`. Por el otro lado, para que `||` sea verdadero alcanza con que al menos uno de los booleanos lo sea. Dicho de otra manera, ambas condiciones deben ser falsas para que retorne `false`. Por ejemplo en...

``` javascript
ム "mumuki".toUpperCase() === "Mumuki" || "romance".includes("amor")
```

... tanto `"mumuki".toUpperCase() === "Mumuki" || "romance".includes("amor")` devuelven `false`. Si probamos con los booleanos directamente veremos que:

```javascript
ム false || false
false
ム true || false
true
ム false || true
true
ム true || true
true
```


