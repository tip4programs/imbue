---
title: Bootstrap Elements with Jekyll
layout: default
---

### Why Bootstrap Elements on Jekyll?
Hai... This Jekyll theme using bootstrap prepared with an aim; everybody can build attractive websites with beautiful typography and responsive theme. Since I am not a web designer I have given more preference for those who interested to write blogs, but they do not really know HTML. The following elements will help you to accomplish this task of writing responsive website.

## Embedding Videos
 You can see a share button on the **YouTube** videos. You have to first of all tap on that share button from your smartphone and copy that link of video to your clipboard. The link will look alike https://youtu.be/`zrkcGL5H3MU`. The highlighted part of link is the identity of that video. Ise following simple syntax to embedd that video on your website using the particular `id` of video.

{% include video.html id="zrkcGL5H3MU" %}

## Adding responsive image
 This theme allows you to pull the image to right side and pt your image center with an attractive caption. Also If you pull the image to right side this theme allows you to wrap text around the image.
 
## Alert Boxes

{% include alert.html alert_type="warning" heading=text="GOVERNMENT WARNING:" text="(1) According to the Surgeon General, women should not drink alcoholic beverages during pregnancy because of the risk of birth defects.(2) Consumption of alcoholic beverages impairs your ability to drive a car or operate machinery, and may cause health problems." %}
