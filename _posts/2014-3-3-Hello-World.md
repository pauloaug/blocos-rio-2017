---
layout: post
title: oi
---

{{site.data.eventos.lista.first.name}}

{{site.data.eventos["@context"]}}

{{site.data.eventos.foo}}

{{site.data.eventos.lista[0].location.name}}


<table>
{% tablerow evt in site.data.eventos.lista cols:3 %}
  {{ evt.name }}
{% endtablerow %}
</table>
