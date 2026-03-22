---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.projects reversed %}
    {% include archive-single-projects.html %}
  {% endfor %}
</tbody>
</table>
