---
layout: post
title: Test Page&#8282;Embedding Videos and Images
date:  2017-06-04 12:50:39
categories: others
tags: Jekyll HTML
---
# Example for Embedding Youtube Video
### First Video
{% include video.html id="zrkcGL5H3MU" %}
### Second Video
{% include video.html id="eI0r_aL4rhg" %}
# Embedding Image With Caption
{% include figure.html image="https://unsplash.it/300/400?image=123" caption="This image has a caption" %}

{% include figure.html image="https://unsplash.it/300/400?image=123" caption="This image has a caption but also alt text" alt="This is the alt text" position="right" %}

{% include figure.html image="https://unsplash.it/800/400?image=123" alt="This image has alt text but no caption" %}
