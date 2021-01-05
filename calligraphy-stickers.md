---
layout: page
title: Kalligrafi klistermärken
---

## Custom Calligraphy stickers:

Here is a list of our products.


<div>
{% for product in site.data.calproducts %}
    <div class="col-md col-sm-11 portfolio-item effect1">
        <a href="#r{{ forloop.index }}" class="portfolio-link" data-toggle="modal">
            <img src="{{ product.img }}" class="img-fluid grid-img" alt="">
            <div class="portfolio-caption">
                <h4>{{ product.name }}</h4>
                <p class="text-muted">{{ product.cost }}</p>
           </div>
        </a>                  
    </div>
{% endfor %}
</div>