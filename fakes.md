---
permalink: /fakes/index.html
---

# Fake News

รวมข่าวปลอมที่แชร์กัน

{% for item in site.fakes %}
* [{{ item.title }}]({{ site.baseurl }}{{ item.url }})
{% endfor %}

อย่าลืมอ่าน [FAQ]({{ "/faq/" | relative_url }}) รวมคำถามต่างๆ

[<< Back to homepage]({{ site.baseurl }})