---
title: notas

---

# Notas

{% for notas in site.data.notas %}
  ## {{ notas.nombre }} - {{ notas.notas }} - {{ notas.sexo }}
{% endfor %}