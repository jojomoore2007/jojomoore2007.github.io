A list of all updates, along with when they were released, is shown below.

<ul>
  {% for post in site.categories.Updates %}
    <li>
      <a href="https://jojomoore2007.github.io/thecodersite{{ post.url }}">{{ post.title }} - {{ post.date }}</a>
    </li>
  {% endfor %}
</ul>
