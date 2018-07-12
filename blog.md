---
title: blog - lionsite
layout: default
permalink: /blog/
---
<div class="post-header">
    <p>lionsite</p>
    <div class="header-logo is-pulled-right">
        {% img badge.png %}
    </div>
</div>
<div class="content-wrapper columns">
    <div class="column is-7 is-offset-2 item-container">
        {% for post in site.posts %}
            <a href="{{ post.url }}"><span class="title">{{ post.title }}</span></a>
            <hr class="header-separator">
            <div>{{ post.excerpt }}</div>
            <div class="post-separator">{% img blustar.gif %}</div>
        {% endfor %}
    </div>
    <div class="column is-3">
        <h2>Recent posts</h2>
        <ul>
            {% for post in site.posts limit:5 %}
                <li>
                    <a href="{{ post.url }}">{{ post.title}}</a>
                </li>
            {% endfor %}
        </ul>
    </div>
</div>

