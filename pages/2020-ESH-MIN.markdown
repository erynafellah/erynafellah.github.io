---
layout: page
title: Aidan Baju Melayu Mint Green
id: 2020-ESH-MIN
colour : Mint Green
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mdQfBtUkSCB62rM7QXJh6npdVjfzJwtSz_DRFuWEh3yozA50EQ2O8bUbohq_pLH1Ki-aXi8iEtAJtO_XVptfPYU5u8za8Vw-ssA65XjHisxXHmxpkiAl-pgx7qAvBWdLtYXeki8Shswj1dt9LMhI18r97NmHOiuVZvkYx90ik8IMGn5hpNMCKRPNhZvzM8g1f?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4m0WMWj5jUX-0q_kj78V1wHBgRNFwDesYPNBqpbVwU87Y97qfZiDn8rOnXOSAR3e3tfsEuCSimiAKUiaOksTD8Cqhuq8WQPikdqsS9qvulrL7Gmz_MqDK9kWaZYM0eusvgZafYBys0t3CDzGDBgQV3WKHVPJ6Oew2Y9hXktL_r2YcGjkRXf3nA0h4_LlNUhMaI?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mUhNdqiFFGK-y084NVut_aE8b1h0mJA6rV5phcq-3I_1CXfl22vAsvfdY0ce4SZ5H-vNuCeH1LswiEuJoUzOtkQ4-IQHUBQbOYkZiojBnwCiSQKL1JbfCPjsRPie8PGtelG18p33PZTDt76b6nOQOkXlUmpgnDt9GZVIoTS6xdH5D7ziPG7mD_Ho0xsTNfz6G?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mSMShs7YVo7Usw1KVegfAwVv7TyHFwdjkYNCWTMFOWXVe7qYf5PUzBxCPhnVjsE3g6qw-8hGM01p7sXF8R6bmIPY3hEX9YHO8_z63sxfOFQeFbdmintDyVXQUYC0il8KPuMVKPVcSgQ_1fQ7y1mbqzWE2tnSqk5lQRZZmzzfl7Qxk2gCm5fu5eVuQHYa0WYv9?width=819&height=1024&cropmode=none
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

  
