---
title: personajes

---

# Personajes

{% for nota in site.data.notas %}
<table border="1" style="width: 100%;">
  <tr><td>nombre</td><td>notas</td><td>sexo</td></tr>           
      <tr>
        <td>{{ notas.nombre }}</td> 
        <td>{{ notas.notas }}</td> 
        <td>{{ notas.sexo }}</td>
      </tr>
   
</table>
{% endfor %}