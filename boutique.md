---
title: "Boutique"
order: 2
in_menu: true
blog_index: true
---
{% for post in site.posts %}
<article class="blog-item">
  <h2>
    <a href="{{post.url | relative_url}}"> {{ post.title }} </a>
  </h2>

  <a href="{{post.url | relative_url}}"> Voir l'article ➞ </a>
</article>
<hr />
{% endfor %} 