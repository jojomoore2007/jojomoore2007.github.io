All posts, sorted by category:

{% for category in site.categories %}
  <h4>{{ category[0] }}</h4>
  <ul>
    {% for post in category[1] %}
      <li><a href="/thecodersite{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

{% for category in site. %}
  <h4>{{ category[0] }}</h4>
  <ul>
    {% for post in category[1] %}
      <li><a href="/thecodersite{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
