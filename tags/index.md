---
layout: page
title: Tag Index
excerpt: "An archive of posts sorted by tag."
search_omit: true
---

{% capture site_tags %}{% for tag in site.tags %}{{ tag | first }}{% unless forloop.last %},{% endunless %}{% endfor %}{% endcapture %}
{% assign tags_list = site_tags | split:',' | sort %}

<ul class="list-unstyled">
  {% for item in (0..site.tags.size) %}{% unless forloop.last %}
    {% capture this_word %}{{ tags_list[item] | strip_newlines }}{% endcapture %}
    <li><a class="btn btn-info" role= "button" href="#{{ this_word }}">{{ this_word }}{{ site.tags[this_word].size }}</a></li>
  {% endunless %}{% endfor %}
</ul>

{% for item in (0..site.tags.size) %}{% unless forloop.last %}
  {% capture this_word %}{{ tags_list[item] | strip_newlines }}{% endcapture %}
  <h2 id="{{ this_word }}">{{ this_word }}</h2>
  <ul class="list-unstyled">
  {% for post in site.tags[this_word] %}{% if post.title != null %}
    <li><a href="{{ post.url |prepend:site.baseurl }}">{{ post.title }}<div class="pull-right"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></div></a></li>
  {% endif %}{% endfor %}
  </ul>
{% endunless %}{% endfor %}
