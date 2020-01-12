---
layout: default
---

[Link to posts](./posts).

## All Posts
 <ul>
   {% for post in site.posts %}
     <li>
       <a href="{{ post.url }}">{{ post.title }}</a>
     </li>
   {% endfor %}
 </ul>

<div class="header-bar">
  <h1>new school revolution</h1>
  <h2>describe some stuff here</h2>
  <br/>
  <hr>
  <br/>
</div>
<br/>
<p>Lets fill this with content!</p>

<br/>
<hr/>
<br/>
