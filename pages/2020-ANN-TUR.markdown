---
layout: page
title: Anna Kurung Kedah Turqoise
id: 2020-ANN-TUR
colour: Turqoise
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mZsn0HBXY2Q9FLiAumVToAdj73hu0nGdRU1d6TXozxxRll-Wx1dVSQZtJ0c01IeAi9xrie3YjXCOtqGOb8cnbGS9TFddR9Hhlh2q8laTIQf4sQrCefI3Lyn6C0LB9lWgPoto6hrlbtNFcqb5wm9S7TDtacBVQ55UzCU7DOwUg0E7feJZYQo2PiamoG5QXbd3W?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4ma09vf8PIE759hVjLfpAlXCWmx9mD5_ck1sh4pNcX_R8sHh02B7N9KgFS_Rn2BOD9qZEL0ZKrvl7jC4cFdNaxJnXKEIpLuGhdrVcWxf6C8NojMmBYNEHzhDbL2qrhnG5i9dyOU7OusiPSBoPxmvgGyfvIiUnotyBpXtbTlVkqvjZO47-elBmp64KotJ5Yy1OC?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4m-T5v83T7KWyWfd1u0yx6sHGWVmkNwxkBlGloM7_X29Uk6is6Ymrzc_Mi5wv4j5poBfzDnJv4ufXakdTQwlmhxUw7pHs-FH5k3PyK_rZ-DLzFmNJ5UdEueViQUKc1r6HAzbcGUcTi5N5EEIeNJopOB8VKuxzHG2VtFlbLVCI2djT9fQ6XOcIPzlep1a2C-Lk6?width=819&height=1024&cropmode=none
descriptions:
- desc: Design fabric
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

  
