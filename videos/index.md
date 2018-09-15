# Videos!

<ul>
{{ % for post in site.categories.videos % }}
<li><a href="/thecodersite/videos{{ post.url }}" title="{{ post.date }}">{{ post.title }}</a></li>
{{ % endfor % }}
</ul>
