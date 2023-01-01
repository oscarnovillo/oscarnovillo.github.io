---
title: members

---

# Members

{% for member in site.members %}
    [ver]({{ member.url }})
  <h2>{{ member.name }} - {{ member.position }}</h2>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}