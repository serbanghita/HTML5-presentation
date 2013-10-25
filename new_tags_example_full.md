##### HTML markup
## New tags (full example)

```html
<body>
  <!-- page header -->
 <header>
  <h1>My Blog</h1>
  <p>Last Modified: <span>2013-10-24</span></p>
  <!-- main nav -->
  <nav>
   <h1>Navigation</h1>
   <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About me</a></li>
    <li><a href="projects.html">My projects</a></li>
   </ul>
  </nav>
 </header>
 <!-- page main content -->
 <main>
  <!-- aside related to articles -->
  <aside>
      <nav>
       <h1>My blogroll</h1>
       <ul>
        <li><a href="http://blog.first.com/">First Blog</a>
          <li><a href="http://blog.second.com/">Second Blog</a>
       </ul>
    </nav>
  </aside>
  <!-- featured article(s) -->
  <article>
    <!-- article's own header -->
   <header>
    <h1>My First Blog Post</h1>
   </header>
   <div>
    <p>Today I went to the beach and had a lot of fun.</p>
    <!-- aside related to the current article body. Eg: quote -->
    <aside>
      <h1>It was warm</h1>
      <p>The weather was exceptional that day!</p>
    </aside>
    ...more content...
   </div>
   <!-- article's own footer -->
   <footer>
    <p>Posted <time datetime="2013-10-23">Thursday</time>.</p>
   </footer>
  </article>
  ...more blog posts...
 </main>
 <!-- page footer -->
 <footer>
  <p>Copyright © <span>2013</span> <span>Serban Ghita</span></p>
  <p><a href="cookies.html">About cookies</a>
     <a href="policy.html">Privacy Policy</a>
     <a href="contact.html">Contact Us</a></p>
 </footer>
</body>
```