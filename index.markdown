---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


{% for post in site.post %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}