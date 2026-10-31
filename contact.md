---
layout: default
title: Contact
---
<article class="text-page">
    <h1>Contact</h1>
    <p><a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
    <p>{% for link in site.links %}<a href="{{ link.url }}" target="_blank" rel="noopener">{{ link.name }}</a>{% unless forloop.last %} · {% endunless %}{% endfor %}</p>
</article>
