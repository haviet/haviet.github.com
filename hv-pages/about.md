---
layout: page
title: Giới thiệu
tags: topnav
pos: 00
permalink: /about/

background:
- url: bg07.svg
- url: bg11.svg

bg: bg06.svg
---
<section class="outer">
    <div class="inner bgwhite page-content">
        <h2>{{ page.title }}</h2>
        <p>and the page permalink is {{ page.url }}</p>
    </div>
</section>

<section class="outer">
    <div class="inner about-prd-list tx-center">
        {% include content-blocks/products_list.html %}
    </div>
</section>

<section class="outer hv-06">
    <div class="inner tx-center">
        <div class="section-content hv-06-inner">
            <div class="ctc-block">
                {% include content-blocks/footer_contact_block.html %}
            </div>
        </div>
    </div>
</section>

