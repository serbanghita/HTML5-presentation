##### API<small>uri</small>
## Websockets

<p>Modalitate de a creea comunicatii persistente, in ambele sensuri intre aplicatia web si server.</p>
<p style="margin-top:20px; font-size:80%;">Trebuie un server ce foloseste protocolul <span class="em2">ws://</span>. Ex.: <a href="http://nodejs.org/">node.js</a></p>

```
var conn = new WebSocket("ws://server.com/chat");
conn.onmessage = function(msg) {
	msg = JSON.parse(msg); // decode JSON into object
}
conn.onclose = function() { }
conn.send('Ce mai faci?');
```

<p style="margin-top:20px; font-size:80%;">Recomandare: folositi la inceput libraria <a href="http://socket.io">Socket.io</a> si servicii externe de server cu suport pentru Websockets.</p>

<p style="margin-top:20px; font-size:80%;">Demo: Joc multiplayer</p>
<p style="font-size:80%;">Compatibilitate: <a href="http://caniuse.com/websockets">caniuse.com/websockets</a></p>