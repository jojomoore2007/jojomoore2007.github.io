{% for post in site.posts %}

### [{{ post.title }}]({{post.url}})
<small>{{post.date}}</small>
{{post.excerpt}}

{% endfor %}
