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
 
 {% include figure.html image="https://unsplash.it/300/400?image=123" caption="This image has caption as well as alt text" alt="This image has alt text" %}
 
 Unfortunately pulling image towards left do not allows you to wrap text around the image. `Anybody can contribute that awesomeness to this work`.
 {% include figure.html image="https://unsplash.it/300/400?image=123" caption="This image has a caption but also alt text" alt="This is the alt text" position="right" %}Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur quis quam vitae ipsum vehicula laoreet eget et turpis. Fusce dapibus vel magna in interdum. Sed euismod luctus lectus et fermentum. Sed efficitur tempor dui. Nulla malesuada risus nec mauris condimentum tempor. Phasellus nulla dolor, condimentum ut sollicitudin non, mattis mattis ipsum. Cras pharetra mi eu mauris aliquet, dignissim faucibus sapien lacinia. Cras at mi nisl. Phasellus ex ipsum, mattis vehicula egestas vehicula, pulvinar nec lorem. Phasellus accumsan lobortis magna, eu condimentum felis. Proin blandit est id nulla efficitur scelerisque. In vehicula nisi vel sapien venenatis, accumsan gravida ex fringilla. Mauris ac consectetur nibh.
 
 Vestibulum viverra rutrum quam sit amet egestas. Aliquam venenatis nisi eu rhoncus laoreet. Donec convallis tellus tellus, at pulvinar velit pharetra id. Nullam varius massa eu felis placerat, vitae facilisis nibh laoreet. Maecenas posuere quam at semper cursus. Proin tempor massa non tellus bibendum venenatis. Phasellus diam ex, tempor sed lacus et, dapibus ullamcorper erat. Nam vel nisi at justo interdum faucibus. Etiam nec augue urna. Phasellus at turpis vel elit posuere lacinia. Duis tristique sapien ut lorem imperdiet, vitae efficitur augue varius. Nam porttitor nunc a sapien euismod, eu placerat elit venenatis. Curabitur ac elit faucibus odio auctor ornare vitae nec dui. Aliquam sed erat posuere, fringilla libero auctor, eleifend mauris. Vivamus sed convallis nisi. Integer rhoncus, odio ut ornare tempus, arcu magna pellentesque quam, at dictum velit metus a urna. Phasellus vitae pellentesque neque, ac auctor nulla. Nullam imperdiet vulputate urna ut lobortis. Aenean ac justo justo. Ut ut varius ligula. Fusce varius elit et erat sollicitudin laoreet. Integer iaculis ut felis eget efficitur. Aliquam vitae lorem nec lectus finibus faucibus in non nibh. Pellentesque sapien risus, vestibulum auctor erat vel, ultricies sodales orci. Donec id dignissim ipsum. 
## Alert Boxes

{% include alert.html alert_type="warning" heading="GOVERNMENT WARNING:" text="(1) According to the Surgeon General, women should not drink alcoholic beverages during pregnancy because of the risk of birth defects.<br />(2) Consumption of alcoholic beverages impairs your ability to drive a car or operate machinery, and may cause health problems." %}
