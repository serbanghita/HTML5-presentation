##### HTML Markup
## Microdata

> schema.org is a collaboration by Google, Microsoft, and Yahoo! to improve the web by creating a
common vocabulary for describing the data on the web. If you add schema.org markup to your HTML pages,
many companies and products—including Google search—will understand the data on your site.

```
<div class="prezentare">
    <span itemscope itemtype="http://schema.org/Event">
        <img itemprop="image" src="/docs/en/events/techhub-logo-h70px.png" />
        <p>
            <meta itemprop="startDate" content="2013-10-29T16:00">In data de Marti 2013-10-29 ora 16:00 o sa am la
            <span itemprop="location" itemscope itemtype="http://schema.org/Place">
                <span itemprop="name">TechHub Bucuresti</span> </span>o prezentare numita "
            <span itemprop="name">HTML5 - De la site-uri mai performante la jocuri web multiplayer</span>".
        </p>
```

[Google Structured Data Testing Tool](http://www.google.com/webmasters/tools/richsnippets) / [Example link](http://www.avangate.com/newsletter/html5-newsletter-test.html)