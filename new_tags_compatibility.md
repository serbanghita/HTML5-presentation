##### HTML Markup
## Use polyfills

> In web development, a polyfill (or polyfiller) is downloadable code
which provides facilities that __are not__ built-in to a web browser.



```
<!--[if lte IE 8]>
<script type="text/javascript">
    var newTags = ['header', 'section', 'footer'];
    for(var i=0;i<newTags.length;i++){
        document.createElement(newTags[i]);
    }
</script>
<style type="text/css">
    header, section, footer { display:block; }
</style>
<![endif]-->
```

Full list at [Modernizr Wiki](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills).