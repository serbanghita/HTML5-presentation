##### API<small>uri</small>
## Webworkers

<p style="font-size:80%;">Sunt un fel de cronuri in browser. Rezolva task-uri in background fara sa blocheze interfata. Task-urile nu au acces la DOM si ruleaza "sandboxed".</p>

```
var worker = new Worker('task.js');
worker.onmessage = function(e) {
	console.log(e.data);
};
worker.postMessage('data');
```
<p style="margin-top:20px; font-size:80%;">De retinut: in JavaScript obiectele se paseaza prin referinta dar in interiorul unui worker obiectele sunt copiate. Este important ca dupa ce worker-ul isi termina treaba sa goliti datele din memorie.</p>


<p style="margin-top:20px; font-size:80%;">Demo: <a href="webworkers.html">live</a></p>
<p style="font-size:80%;">Compatibilitate: <a href="http://caniuse.com/webworkers">caniuse.com/webworkers</a></p>