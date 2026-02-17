---
layout: none
---

<nav class="sidebar">

## Navigation

- [Startseite](index.md)
- [Vorwort](vorwort.md)
- [Einleitung](einleitung.md)
- [Manifest](manifest.md)
- [Grundprinzipien](grundprinzipien.md)
- [Historie](historie.md)
- [Modell](modell.md)
- [Übersicht](uebersicht.md)

---

## Kapitel

{% assign chapters = site.pages | sort: "title" %}
{% for page in chapters %}
  {% if page.title contains "Kapitel" %}
- [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}

---

## Abschluss

- [Schlussseite](Schlussseite.md)

</nav>