##### Notable APIs
## Canvas

__Taking canvas screenshots & saving them__

```
var imgString = canvas.toDataURL();
$.post("http://test.com/save/screenshot", {data: imgString});
```

<p style="font-size:0.7em;">[Demo](test_screenshot_canvas.html)</p>
<p style="font-size:0.7em;">[Simple example](http://www.rgraph.net/blog/2013/april/an-example-of-the-html5-canvas-todataurl-function.html)</p>