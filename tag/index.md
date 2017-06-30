---
layout: default
permalink: /tag
---

{% for post in site.categories.FOO %}
+ [{{ post.title }}]({{ page.url }})
{% endfor %}