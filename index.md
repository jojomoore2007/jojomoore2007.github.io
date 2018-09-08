# Welcome to theCoderSite();!
We want you to have the best experience possible while the development is underway. Try out [this game](https://www.scholastic.com/kids/games/webgames/coderdojo-nanonauts/) to cure your boredom!

You can also view the source code [here,](https://github.com/jojomoore2007/thecodersite/) and view all blog posts here:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
