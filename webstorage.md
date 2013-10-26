##### API<small>uri</small>
## WebStorage

<p>Permite stocarea permanenta in browser a unor <br>
	informatii de tip <span class="em2">cheie:valoare</span> sub forma de <span>string</span>.</p>

<p style="font-size:80%;">Spatiu stocare: Chrome, Firefox, Opera - 5mb; IE - 10mb, BlackBerry 10 - 25mb</p>
<p style="font-size:80%;">Spatiu stocare cookie: 4kb</p>

```
window.localStorage
// Set
localStorage.setItem('name', 'Serban Ghita');
localStorage.setItem('position', JSON.stringify({x: 10, y: 10}));
// Get
localStorage.getItem('name');
JSON.parse(window.localStorage.getItem('position'));
// Delete
localStorage.removeItem('name');
```

<p style="margin-top:20px; font-size:80%;">Demo: <a href="http://www.avangate.com/lp/html5-techhub-bucharest-2013.html">live</a> in browser</p>
<p style="font-size:80%;">Compatibilitate: <a href="http://caniuse.com/localstorage">caniuse.com/localstorage</a></p>