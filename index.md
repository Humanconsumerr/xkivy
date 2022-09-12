---
layout: default
---
[Link to another page](./another-page.html).

<div align="center">

{% include_relative README.md %}
(im an arch user btw)
</div>

{% include carousel.html height="250" unit="px" duration="4" %}

{% slider 700 captions %}
    ![alt text 1](image1.jpg)
    [![alt text 2](image2.jpg)](/page/url)
    [![alt text 3](image3.jpg)](http://example.com)
 {% endslider %}
