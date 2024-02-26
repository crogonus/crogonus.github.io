---
title: personajes

---

# Personajes

{% for personaje in site.data.personajes %}
  ## {{ personajes.nombre }} - {{ personajes.nivel }} - {{ personajes.sexo }}
{% endfor %}