{% for post in site.posts %}

<hgroup>
	<h3><a href="{{post.url}}">{{ post.title }}</a></h3>
	<h6>{{post.date}}</h6>
</hgroup>

{{post.excerpt}}

{% endfor %}
