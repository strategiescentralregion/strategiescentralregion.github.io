---
layout: default
title: test
author: andrew
---

{% for file in site.static_files %}
##{{ file.path | slice: 6, 14 }} 

{{ file.extname }}
{% endfor %}