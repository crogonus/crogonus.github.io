---
title: notas

---

# Notas

{% for nota in site.data.notas %}
  ## {{ notas.nombre }} - {{ notas.notas }} - {{ notas.sexo }}
{% endfor %}