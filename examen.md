---
title: personajes

---

# Personajes

{% for personaje in site.data.notas %}
  ## {{ notas.nombre }} - {{ notas.notas }} - {{ notas.sexo }}
{% endfor %}