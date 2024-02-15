---
title: members

---

# Members


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for persona in site.data.personas %}
  ## {{ persona.nombre }} - {{ persona.edad }}
{% endfor %}