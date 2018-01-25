---
title: Bootstrap Elements with Jekyll
layout:default
---

### Why Bootstrap Elements on Jekyll?
Hai this Jekyll theme using bootstrap prepared with an aim; everybody can build attractive websites with beautiful typography and responsive theme. Since I am not a web designer I have given more preference for those who intereated to write blogs, but they have not really knows HTML. The following elements will help you to accomplish this task.

## Embedding Videos
 You can see a share button on the **YouTube** videos. You have to first of all tap on that share button from your smartphone and copy that link of video to your clipboard. The link will look alike https://youtu.be/`zrkcGL5H3MU`. The highlighted part of link is the identity of that video. Ise following simple syntax to embedd that video on your website using the particular `id` of video.
```markdown
{% include video.html id="zrkcGL5H3MU" %}
```
The above code will embedd following YouTubevideo on your website responsively
{% include video.html id="zrkcGL5H3MU" %}

## Embedding Images
