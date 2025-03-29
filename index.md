---
layout: home
---

# Witaj w naszym sklepie!

Zobacz nasze produkty:

{% for product in site.products %}
  ### {{ product.title }}
  ![{{ product.title }}]({{ product.image }})
  **Cena:** {{ product.price }}
  - {{ product.description }}
  - [Dodaj do koszyka](#)
{% endfor %}
