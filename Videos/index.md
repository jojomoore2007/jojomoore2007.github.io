# Videos!

<ul>
{{ % for post in site.categories.Videos % }}
<li><a href="/thecodersite{{ post.url }}" title="{{ post.date }}">{{ post.title }}</a></li>
{{ % endfor % }}
</ul>
