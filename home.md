---
title: home
permalink: /
---

## Welcome to {{site.title}} {{page.title}} 
<ul>
{% for page in site.pages %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
{% endfor %}
</ul>
 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


### Quien desarrolla

Hoyoverse es una empresa china que ha desarrollado diversos juegos, puedes ver imagenes de los mismos en el apartado de Juegos


[Link](https://www.hoyoverse.com/es-es/)![Image]({{ site.url }}/assets/img/HoYoverse-Logo.png)



### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
