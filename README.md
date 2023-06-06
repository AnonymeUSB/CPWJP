<h1>CONCOUR D'ALGhHORITHME</h1>
<hr>
<h2>Task#1</h2><sub>2 points</sub>
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
   <li>Que retournera le script si on modifier la dernière ligne par  `alert(calcul(1, 0, "4"))` ?</li>
</ol>
<hr>
<h2>Task#2</h2><sub>3 points</sub>
<img src="carbon (2).png">
<br>

```javascript
var username = prompt("Nom d'utilisateur :")
var password = prompt("Mot de passe :")

function connnexion(user, pass, true_user, true_pass) {      
  
    if (user === true_user && pass === true_pass) {
        var message = "Connexion reussi"
    }
    else {
        var message = "Connexion invalide"
    }

    return message
}

alert(connexion(username, password, "root"))
```
<ol>
  <li>Lisez ce script. A quoi correspond "root" (dernière ligne) ?</li>
  <li>Ce script contient une erreur. Trouver le bug et résolvez-le.</li>
  <li>Récupérer et stocker dans une variable `char` le 3ème caractère du mot de passe.</li>
</ol>
<h3>Ressources</h3>
<a href="https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/String/slice" ><p>String.prototype.slice()</p></a>
<hr>
<h2>Task#3</h2><sub>3 points</sub>
<img src="carbon (3).png">
<br>
