---
layout: category
title: Laid-Back Camp△ The Movie
epsname: Film Kemah Santai△
coverPhoto: https://cdn.lewd.host/ggkBBh0p.png
---

Sinopsis: Berniat meramaikan kembali tempat wisata yang ditinggalkan, Rin dan kawan-kawan berencana membangun perkemahan di tempat tersebut, namun ... selebihnya silakan nonton sendiri ketimbang kena spoiler nih sinopsis.

Soloyolo: Noromi

Unduh

---
  <ul>
  BD
    {% for post in site.categories['Film Kemah Santai△ BD'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}<br>
  WEB
    {% for post in site.categories['Film Kemah Santai△'] %}
  <li><a class="white pinkhover" href="{{ site.baseurl }}{{ post.url }}">{% if post.eps %}E{{ post.eps }} - {{ post.epsname }}{% else %}Paketan - {{ page.epsname }}{% endif %}</a></li>
  {% endfor %}
  </ul>