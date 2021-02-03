{% for post in site.posts %}

<h3><a href="{{post.url}}">{{ post.title }}</a><br><h6>{{ post.date }}</h6></h3>
{{post.excerpt}}

{% endfor %}
