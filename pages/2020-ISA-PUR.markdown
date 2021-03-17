---
layout: page
title: Isabella Kurung Moden Purple
id: 2020-ISA-PUR
colour : Purple
page_type: product
price : 250
discount : 
images:
- image: https://bl3302files.storage.live.com/y4mvBc96OEGYIJa4hFuRAMjVBKMaJsluogbhU2Dv0B8jh-vfh_TYMko_lzkr3wJGCxSny_Wkg8iYT1hrKex-QZE5E1tJjbAUZ5aod-VPBHmbovKENii3_uR2HbGpZs25za3wmkkvLld48FqBz9M-XEKvMf3IldpJy3l0duaS0qy6RSHvEln0SFx84KUrfWqGcXs?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mXn9k7qPnxvACzaR-1P-ijimJNKxrwrp5_ECUqHMLeZWBCX3i7m3u-cRGimw_w-uCom3Y-Zo33HPIxcqzbH3NlmD68EjygSuT46coa1s8kxBuTNf7VVQZ1yMvG6mXyzmBrMiq16k705b3lD1-qh6u44Yxp4SyYMaY5KVkAEnBrS--C-ohBupdKJz1c_1DVWNh?width=819&height=1024&cropmode=none
- image: https://bl3302files.storage.live.com/y4mQa76Y9YiIBE-RvRu-sG-ddJ-5hbJVLysgZxqL-FpqVYU0tBQcrEm5MU0UhNl5eEQaK6ON731TSrWf9DLH12bXXL3l6YQ9Rb5hvB_5mdAtEpSgaeFCDtnVA1zIthFgH1WruzbGbhX0EIchpXPD_KFfuhiaeZh6uq2J17IWfyfPaSRFJM3FdvObHqqeCPZrsWZ?width=819&height=1024&cropmode=none
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

  
