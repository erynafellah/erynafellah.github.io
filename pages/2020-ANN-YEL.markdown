---
layout: page
title: Anna Kurung Kedah Yellow
id: 2020-ANN-YEL
colour: yellow
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mCE9ljWJF8L8SKzGBnumaoW2PV0ybZoIurrtiKM-szQZ7sdbRdJAj_GGwhXiQ4eDqh0MxTOF2O2VQLSlBacFXmNkYFPpzRf08uq0w5y-SiHEEWnIu3RM89uhRlXrjt08vK2JN3nAyL0Bn_f-8Ws8hNzZc3jAenhUZWMFQLmlLnHCJECOJPUSuq6h4_b2VDS2H?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mKeJT-qKvG3oobxnLdf18fooOIlW_tIfW76ZM-_d_6DDjvYhxhB-05m3oqABT_MZo-_VbrUZIM5s65zY26kslXgab2IOxYgB62RaQ0w_OoeD7Xuh5XjATN2b4ENuCOOQWxhPrbq4DGS-TGlJFqtYjlI-bcdCNRxeybcOwAZsU0RRxozhXS5kQHfbSPHg7UOPr?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4m2rKKqo6Hgi8CqqfHkR9pkuuqVKoy6vBl7BJNjlAskilbl3OghHqX2DQgSJqYJ5uSV8mNBjLLS1tc811_lbtkLEm7oCoBGN4atZZgEKnrVUy0SzUNgwDRNLzxVPiNr_a0d_Ufnhapq1y-FlZvPnqXJNn6ep1YkFhxq1jMb6U6gRsqA0yDf21FStaeM23YNAAC?width=819&height=1024&cropmode=none
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

  
