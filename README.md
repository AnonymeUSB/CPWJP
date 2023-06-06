<h1>CONCOUR D'ALGhHORITHME</h1>
<hr>
<h2>Task#1</h2>
<img src="carbon.png">
<br>

```javascript

function calcul(var1, var2, var3) {
  if (var3 == "1"){
   	 var result = var1 + var2
  }
  else if (var3 == "2") {
     var result = var1 - var2
  }
  else if (var3 == "3") {
     var result = var1 * var2
  }
  else if (var3 == "4") {
     var result = var1 / var2
  }
  
  return result
}

alert(calcul(3, 7, "3"))
```
<ol>
  <li>Lisez ce code. Que retournera la fonction alert() ?</li>
   <li>Que retournera le script si on modifier la dernière ligne par  ```alert(calcul(1, 0, "4"))```</li>
</ol>
