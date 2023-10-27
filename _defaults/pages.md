---
layout: default.liquid

title: Intergint Systems
---
<h1>Hoopty</h1>
## Blog!

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
