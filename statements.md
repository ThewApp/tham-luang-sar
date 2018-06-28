---
permalink: /statements/index.html
---

# Official statements

รวมแถลงข่าว สถานการณ์โดยทางการ

{% for item in site.statements %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }})
{% endfor %}

[<< Back to homepage]({{ site.baseurl }})