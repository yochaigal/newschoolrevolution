## All Posts
 <ul>
   {% for post in site.posts %}
     <li>
       <a href="{{ post.url }}">{{ post.title }}</a>
     </li>
   {% endfor %}
 </ul>

 ## Categories
 {% for category in site.categories %}
   <h3>{{ category[0] }}</h3>
   <ul>
     {% for post in category[1] %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
     {% endfor %}
   </ul>
 {% endfor %}

 ## Tags
 {% for tag in site.tags %}
   <h3>{{ tag[0] }}</h3>
   <ul>
     {% for post in tag[1] %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
     {% endfor %}
   </ul>
 {% endfor %}
