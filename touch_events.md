##### API<small>uri</small>
## Touch Events

<p>Evenimente JavaScript utile pentru interactiunea cu dispozitivele mobile.</p>

```
var elem = document.getElementById('myPage');
elem.addEventListener("touchstart", handleStart, false);
elem.addEventListener("touchend", handleEnd, false);
elem.addEventListener("touchcancel", handleCancel, false);
elem.addEventListener("touchleave", handleEnd, false);
elem.addEventListener("touchmove", handleMove, false);
```

<p style="margin-top:20px; font-size:80%;">Demo: <a href="touch_events.html">local Chrome</a>, <a href="http://goo.gl/Xfjlvi">remote iPad</a></p>