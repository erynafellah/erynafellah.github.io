---
layout: page
title: Aidan Baju Melayu Blue
id: 2020-ESH-BLU
colour : Blue
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mtFnlafUMb04b8Q76ybSlvCrGsJyYOZpPjwy5lcjAHxQqQwTqYPDRc0hpBX2n9QzgrPm5sWudMZJHP9JRF8vkZ3mAJRlk48d7zVLujJk2KIgggbtXGlHfdnyxefWM180K0ooHL9pMdpiECysUOAJSkjwbpPVlKGHVvAiSiA7SxTfsiGD2RGZdw2EsQZnoNf7a?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mBhZ_7uhW2a1TURmt3GhGiRcALaMIG4GMhrmJmvtYJnBZXdtXAQyz0n4cAguirygtV6ysJAz32An8XunRgR_bUpxl4tj9mSdzKNi5n-uhp_xJU-zePv8c0spZTleRakbse0WklbK-loXMe6NnVUPHYL0v2P8JvZABd_m7zliH2TP5DedgovroIA0-rr394vc7?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mEtDN791cl_WNhRtdpF8cD6EvMx06x4piJ44vMgJjeRsUbd-QbN9qbi2NYHJSFb27h_aXla1VxofrjN1AaOjP2m7qfy5Udn-QG7RWd_1YhpJT5CL0M5iVLFPr6Z2btk4gwXaOSAFngMvHRdcMw9OTKA21U5xPHaAfb2MTb9zxIRj0W9UcbAZGGOXglLbHPNQJ?width=819&height=1024&cropmode=none
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

  
