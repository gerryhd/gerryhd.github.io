---
title: Inicio
permalink: /negafur/
layout: nega
---
<div>
{% for post in site.posts %}
{% if post.categories contains 'negafur' %}
    <a href="{{ post.url }}"><span class="post-title">{{ post.title }}</span></a>
    <hr class="header-separator">
    <div class="post-body">{{ post.excerpt }}</div>
    <div class="post-separator">{% img blustar.gif %}</div>
{% endif %}
{% endfor %}
</div>
