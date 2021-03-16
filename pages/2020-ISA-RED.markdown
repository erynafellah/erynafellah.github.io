---
layout: page
title: Isabella Kurung Moden
id: 2020-ISA-RED
colour : yellow
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mG0NQtR3Mfr6Aj55I7AfK9rmky5yvRmdGD8ISlvLLDJqNgx7wH8DkxfmiCbyoEckCRvUDurAz4xOXyI_T9md-suDA8igRue4iwjY8yaGing66F3P1-ETnB5fGO5beLmskyWYUQ6U8uiq8mSjsxK5hR8dSv9rRnLX38JelSRKlocbYnkOOcP8HCWJZ0rRD2N_c?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mjm0xEfU5hRJWFbflKJ-3zkYOJ33F7P5wac9CHoIhonK3cTB_lZnO2kR8wkS1uUzGAh3XAiB1jYz7HCidBmH2k6bvX2zEYhJhTfq5oqmUJds6ekJASSQlB3RuC06CBkgVU1e23gbGTE-2PO7ac56yqD9l_2VBGZHuStTeLN36WJleh1EFQS-aFODXpgV28EvP?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mViZlRbCtkCQvLzVLCOFMnowZiQjnPFCvSdIzgBZeHafjmXTYv-Ts4o9qI_8W0rrp74wpNlnTyvVc2qn126OPwYo9bQu91iSU5b8Q-7Sew18mFWTTIFGgeZTXanoAmjk-s_rMv_U2r7AGKAShuWf6GHRhP3nEIKoqwdMibS_QcZDP-cgmxSdAw7S5cQgjEn5K?width=819&height=1024&cropmode=none
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

  
