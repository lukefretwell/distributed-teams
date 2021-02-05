---
layout: press
title: Press
description: Distributed Teams author John O'Duinn in the press.
permalink: /press/

---
<div class="container">
    <div class="row">
        <div class="col-md-12">
            <h2>Video</h2>
                {% for item in site.press.docs %}
                    {% if item.category contains 'video' %}
                        <a href="{{ item.url }}" class="stretched-link">{{ page.title }}</a>
                        {{ item.source }}
                    {% endif %}
                {% endfor %}
            <h2>Audio</h2>
                {% for item in site.press.docs %}
                    {% if item.category contains 'audio' %}
                        <a href="{{ item.url }}" class="stretched-link">{{ page.title }}</a>
                        {{ item.source }}
                    {% endif %}
                {% endfor %}
            <h2>Written articles</h2>
                {% for item in site.press.docs %}
                    {% if item.category contains 'written' %}
                        <a href="{{ item.url }}" class="stretched-link">{{ page.title }}</a>
                        {{ item.source }}
                    {% endif %}
                {% endfor %}
            <h2>Featured in</h2>
                {% for item in site.press.docs %}
                    {% if item.category contains 'video' %}
                        <a href="{{ item.url }}" class="stretched-link">{{ page.title }}</a>
                        {{ item.source }}
                    {% endif %}
                {% endfor %}
        </div>
    </div>
</div>

## Also featured on:
* [PM Library: 10 Best Books on the Future of Work](https://thepmlibrary.com/collections/10-best-books-on-the-future-of-work/)
* [PM Library: 10 Books on how to Effectively Manage a Remote Team](https://medium.com/the-pm-library/10-books-on-how-to-effectively-manage-a-remote-team-b49b6fa14436)
* [Build Remote: 70 Remote Work Books for your Home Office Shelf (1st place!)](https://buildremote.co/products/books/work-from-home-books/)
