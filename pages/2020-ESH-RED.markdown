---
layout: page
title: Aidan Baju Melayu Red
id: 2020-ESH-RED
colour : Red
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mUuFcSrmAYhclxUf_uQ9bGPJlcUGZQICA69XNMnEuy3cySoa3V6Ck330bDvRm7ChD6GAtMK7tveYWhCu9ZPkqBx6hPdZbQY38Cltl4cH3nU6BacibToGo_jzb4KMBrSsqkkNz-tfYOaVz6V8HeerZ6_8FkeLLzcg-xVImePWvjthAYMNBlgFGa4ywRjwC9Qw1?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mlaSnI6zMHNPQZ9NaOSVt2EvrjbFTJcnHZlor4V68RY50UbNBuLxQ8ujGX-L54YbIl4tvtbSOzYloofbKE5fJEbAOPZB8Ep_cUqHgnLo3G6Ta0o4iH8WRv5bpaWbbn47o4e-rBCJiSf36sWxsUMKhrFvpR96ZH0VkA4KX-sc7aBtNMXATOSsj5o6SAnhEnlxZ?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mGvY-an8sce9FuUpr8BaN7bwzFrOfQ45tl6E6xa7FlgypjzjGYn57Q6gwzmjkcTf54k5hYhlePwII3lkw-dDZqfkIiRKHTfzT2gaK-ySitD1tgr7To81fOrTO3ChdyQOySG-Mqm4xyhGlvvGywurRhDcmKzRU84YZk2ka_QzA6-iB7E2YW14vTZ5K-cTHQ0XV?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mum5n0y-0MbWKdO4sEyqSVXLoLkTnclTdbqCZ6Obcag8-j3IC4qKEDd9nALT7qcX5hjHezy1hRyNtawScZOL7ayd3oJzLbzu_3WMJWINYSlQuscBBm7pBTE-wHFz8Qr1Xx5aYIxL7QBc-M3drGQiVQqHjECEvyRu01Y8f613y12JJjZwDDunb31tD3R2xaWX4?width=819&height=1024&cropmode=none
descriptions:
- desc: Made of cotton fabric with lace
- desc: come with multiple sizes
---
{% if page.discount %}
##  **~~RM {{page.price}}~~ RM {{page.discount}}**
{% else %}
## **RM {{page.price}}**
{% endif %}

{% include carousel.html images=page.images height="100" unit="%" duration="7" %}

## Description
{% for item in page.descriptions %}
- {{item.desc}}
{% endfor %}


## Size:  

| Tables        | Are           | Cool  |
|||-|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

  
