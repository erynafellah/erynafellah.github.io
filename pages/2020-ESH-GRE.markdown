---
layout: page
title: Aidan Baju Melayu Green
id: 2020-ESH-GRE
colour : Green
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mhmgYROfCHZhu4l0ijOa9meoq-rXPa2EFgXcmBo_fNE0_pBtkIxnEK5UDg_mPGvF923tTqivUrSElJppB2nFwJM8UvqUPq4_ooBmcnVTcJG5S8WvSA0ZUKsLZCdGwccRO--HS_ozwidhcIKVKirAvQkZCbP0FtBczrWGikAzMslSHBbiyEnsuGs1bryxxOsn6?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mBhqE62zh25uBDgchKDTdJ8vzHjv9DCw1DFEFRuH4BjbTxHBPSqSR7kIXmXGFboiyIG8vbBibwZOZN0AS_9pzqX-17Nw-Jz4AUpfkRRgi1BcklB0Y8tjxmHYlfk5SxdUZzDqNl3w_mmal0wwF6w28WRdvBIajuKf86MgzOXu9bbF_Y1aYlqB_9iEc_gc3Wea-?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mw0EATvoTjxLUTPLFfcc3hhl9oCnVzCmrKAmdkCaDfucwqR7HTxzzfwbwpV99X70qWQl3W8cobqwFt81LbLnyhSzV2cjxCkJs2zq626vTBCPsp4oCjYurtSf6yDDO41LNlwEPKmFi7Bky-51okmvd1KFMo8cvI3BZmZF8yr8pwkivbu9tq44K8hKq_6aGNZoz?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mZ7EKWZxGxIZIG0yw9NFsLu4AVecuu3_0-R9f_n94L0EiXSEZwJNkKh5GA2WO0AsWdhX_V_ShT8fq8UOn_l356TCtCI0ZdhNzytlGiRN16JooucwNXToPhS27TyBH6MsosXfL4yzne0PoW-wQ0p3TChe1_iyPlWlINE_xCQZ3X9ldPOZLZXN_J9GNk-Qya7Kg?width=819&height=1024&cropmode=none
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

  
