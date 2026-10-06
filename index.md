---
layout: default
title: QuaseLivro
excerpt: "Literatura, informações e opiniões de qualidade"
---

# Bem-vindo ao QuaseLivro 📚

**Literatura, informações e opiniões do jeito rápido!**

Um espaço dedicado a compartilhar conhecimento, notícias e reflexões sobre temas que importam.

---

## 📰 Posts Recentes

{% if site.posts.size > 0 %}
  {% for post in site.posts limit:5 %}
    ### [{{ post.title }}]({{ post.url }})
    **{{ post.date | date: "%d de %B de %Y" }}**
    
    {{ post.excerpt }}
    
    [Leia mais →]({{ post.url }})
    
    ---
  {% endfor %}
{% else %}
  *Nenhum post publicado ainda. Volte em breve!*
{% endif %}

---

## 👋 Sobre

Sou **Daniel Natalizi** e criei este espaço para compartilhar ideias, artigos e materiais que acredito serem relevantes.

**Temas abordados:**
- 📖 Literatura
- 💡 Opinião e análise
- 📚 Materiais educacionais
- 🌍 Atualidades

---

## 🔗 Conecte-se

- [GitHub](https://github.com/daniel-natalizi)
- [LinkedIn](https://www.linkedin.com/in/daniel-natalizi-76a381b9)
- [Email](mailto:seu-email@example.com)

---

**Última atualização:** {{ "now" | date: "%d de %B de %Y" }}
