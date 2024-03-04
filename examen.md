---
title: personajes

---

# Personajes

{% for notas in site.data.notas %}
  ## {{ notas.nombre }} - {{ notas.notas }} - {{ notas.sexo }}
{% endfor %}