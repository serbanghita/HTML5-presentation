##### API<small>uri</small>
## Canvas 2D

Cum sa faci capturi ale ecranului si sa le salvezi.

```
var imgString = canvas.toDataURL();
$.post("http://test.com/save/screenshot", {data: imgString});
```

<p style="font-size:80%; margin-top:20px;">Demo: [local](test_screenshot_canvas.html), [remote](http://www.rgraph.net/blog/2013/april/an-example-of-the-html5-canvas-todataurl-function.html)</p>