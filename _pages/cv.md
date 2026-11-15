---
title: "CV"
permalink: /cv/
---

{% assign cv_link = site.data.navigation.main | where: "title", "CV" | first %}
[View my CV]({{ cv_link.url }})
