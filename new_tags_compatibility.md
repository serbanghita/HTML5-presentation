###### Tag-uri si atribute
## Polyfill

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

<p style="margin-top:20px; font-size:80%;">[Exemplu pagina HTML5](test_doctype.html)</p>