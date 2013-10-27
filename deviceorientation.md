##### API<small>uri</small>
## Device orientation &amp; motion

```
window.addEventListener('deviceorientation', function(e) {
  console.log('deviceorientation', e.alpha, e.beta, e.gamma);
}, false);
```

```
window.addEventListener('devicemotion', function(e){
	console.log('devicemotion', e.acceleration, e.accelerationIncludingGravity);
}, false);
```

```
window.addEventListener('orientationchange', function() {
	console.log('orientationchange', window.orientation);
}, false);
```

```
window.addEventListener("resize", function() {
	console.log('resize: ', window.outerWidth, window.outerHeight);
}, false);
```

<p style="margin-top:20px; font-size:80%;">Demo: <a href="deviceorientation.html">local Chrome</a>, <a href="http://goo.gl/pBRrCU">remote iPad</a></p>
<p style="font-size:80%;">Demo: <a href="http://goo.gl/2kdUXN">HTML5Rocks.com</a></p>