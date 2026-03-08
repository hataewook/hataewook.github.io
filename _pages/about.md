---
permalink: /
title: "Taewook Ha"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in the [UVR Lab](https://uvrlab.org/) at Korea Advanced Institute of Science & Technology (KAIST), advised by Prof. [Woontack Woo](https://www.linkedin.com/in/wtwoo/). 

Reseach Interest. 

Educations. 

# Publications

{% include base_path %}

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.publications reversed %}
    {% include archive-single-publications.html %}
  {% endfor %}
</tbody>
</table>