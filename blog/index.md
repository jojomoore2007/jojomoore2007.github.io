All blog posts are stored here:

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }} - {{ post.date }}</a>
    </li>
  {% endfor %}
</ul>
