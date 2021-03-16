---
layout: page
title: Anna Kurung Kedah Green
id: 2020-ANN-GRE
colour: Green
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mtzQePuHB6BO10wRLJJSFTmLWIfcG88vyBeWw4mvj-tem41vxiR5qtWjyLky0Vxf6VJOT02FadrrKv1zDR5XyYJRURlxLLXNAX6UPWdunwGqwEvHmgbI6ROdbq_XLkpi1LZLEVcxQlYANpFiaFg5Ag9wCETCfxKQSnwUrDUV6e7bGCUVP2jkr6Nx5rDwtzDHX?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mbVTEozafJ-xIkVJpl3uoiW5xntsJcs7DXaWrsBP-d9-c8mQTqrIyk9umxmx0pBlqRWyVXvtyvhoITwJAdmr3Z-zRDmTkcYWwj2cgwfvBKUdEe9j7fHtyxcRzMaknFpfzCREFeW6qha3HUNEjj5D5qQncHPFFc3F72HHdZjUfntjh4Iau18x3SAq1xF53cHMz?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4m4vfJkWvXoi9C1jfPQa856wQgC44m9S8HJJikOYzBLMWLrK5beLqfMUZv_ecTtzpppODyPvKt3bXi8zqFSPLcAEYEjXIWEXMJpKXAu_zPlMr5BgAGEObKejChWUcuvk0wj5TIEFE7XswaY1JT2toZEZ3HWss-kBPpozvdX2khQ3Yz30-rbueZnOyF5_3QrrWj?width=819&height=1024&cropmode=none
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

  
