---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Year 2020 Collections 
{% for item in site.pages %}
    {% if item.page_type %}
<div class="row">
<div class="column-picture">
<img src="{{item.images[0].image}}"  width="250" />
</div>
<div class="column-content">
<h2 style="margin-bottom: 1px;">{{ item.title | escape }}</h2>
<h3 style="margin-top: -5px; margin-bottom: 1px;">RM {{ item.price | escape }}</h3>
<a href="{{ item.url | relative_url }}">see more</a>
</div>
</div>
    {% endif %}
{% endfor %}


<style>
.column-picture {
  float: left;
  width: 25%;
}
.column-content {
  float: left;
  width: 60%;
  padding-left: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
  padding: 20px;
  
}
</style> 

 