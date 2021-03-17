---
layout: page
title: Isabella Kurung Moden Blue
id: 2020-ISA-BLU
colour : Blue
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4m-bzuBfjT-yje7w9aYMC7HLgwBSdaDQt9bu4kEtzs3rP5TWVVxG4wlbMXek5HPOPMegiw-HISB6wcHH6fhuaLq386XbMHZ_5xy-HnO8jCFqWpDsNl8mPCHBN6U20MHOrlTOD1GdQdgzMB3DIxlFPEgA7yD2L9xyOzAlAhLD7PGV37Y-WQdmkXibjlLQyNAUtw?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mbioY2GtgFscnwM5SP05oAQachrbRP5y6VF6LiHcQlmlJoMAg6wfE3e8qjdBQcJvJqTK_YQpkuIduOJJ0hjwe7Q27DHw-XYVzyHnzv7ENsbmrWUOsvu7o3VG5GrqgJlPclieN9-NPywNjwFlvZrLIHWM4jO_iKI7l96nV-ZDRsLDybHjX4WJavmgOzSYL1owh?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mALoAITW6wnkei9XtQ0XsqQE0iZdEbtXm2Eue0oN_4ACbuKu-Dn2_sF_WKvKMtaRM4As4WVHuM3Sz3iZiqtG_UxtTe0sjNUbYGSDzSl2qlCc2g-q_CHgiHPnIewnXk_XN4vfDHB2mC_cPp75p959Ucwj84WBnMw-8EfaJvmll85EJb06yBN8u5xiBw9DMIjZd?width=819&height=1024&cropmode=none
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

  
