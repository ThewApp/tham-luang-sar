---
permalink: /faq/index.html
---

# FAQ

{% for item in site.faq %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }})
{% endfor %}

อย่าลืมอ่าน [ข่าวปลอม]({{ "/fakes/" | relative_url }}) รวมข่าวลวงข่าวเท็จต่างๆ

[<< Back to homepage]({{ site.baseurl }})