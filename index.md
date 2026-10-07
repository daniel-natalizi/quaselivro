---
layout: default
title: QuaseLivro
excerpt: "Literatura, informações e opiniões de qualidade"
---

# Bem-vindo ao QuaseLivro

**Literatura, informações e opiniões do jeito rápido!**

---

## 📰 Olha só o que temos:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%d/%m/%Y" }}</small>
    </li>
  {% endfor %}
</ul>

---

## 🔗 Conecte-se

- [GitHub](https://github.com/daniel-natalizi)
- [LinkedIn](https://www.linkedin.com/in/daniel-natalizi-76a381b9)
- [Email](mailto: daniel.natalizi@gmail.com)

---

**Última atualização:** {{ "now" | date: "%d de %B de %Y" }}
