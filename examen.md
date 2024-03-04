---
title: personajes

---

# Personajes

{% for personaje in site.data.personajes %}
    <table border="1" style="width: 100%;">
  <tr><td>nombre</td><td>notas</td><td>sexo</td></tr>           
      <tr>
        <td>{{ notas.nombre }}</td> 
        <td>{{ notas.notas }}</td> 
        <td>{{ notas.sexo }}</td>
      </tr>
   
</table>
  ## {{ personajes.nombre }} - {{ personajes.nivel }} - {{ personajes.sexo }}
{% endfor %}