---
title: Pricing Reference
permalink: "/pricing-reference/"
layout: therapy
---

### Facial Pricing
----

<ul class="text-left">
    {% for item in site.data.prices.facial %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>

### Waxing Pricing
----

<ul class="text-left">
    {% for item in site.data.prices.waxing %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>

### Body Pricing
----


<ul class="text-left">
    {% for item in site.data.prices.body %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>

### Acupuncture Pricing
----

<ul class="text-left">
    {% for item in site.data.prices.acupuncture %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>

### Osteopathy Pricing
----

<ul class="text-left">
    {% for item in site.data.prices.osteo %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>

### Massage Pricing
----

<ul class="text-left">
    {% for item in site.data.prices.massage %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>

### Spa Therapy Pricing
----
<ul class="text-left">
    {% for item in site.data.prices.spa %}
        <li>{{item.name}} - ${{item.price}}</li>
    {% endfor %}
</ul>
