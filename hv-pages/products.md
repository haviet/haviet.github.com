---
layout: home
title: Sản phẩm tiêu biểu
tags: topnav
pos: 01
permalink: /products/

background:
- url: bg04.svg
- url: bg08.svg

headerbg:
- url: bg06.svg

slideshow:
- slide: /hv-assets/imgs/n4.jpg
- slide: /hv-assets/imgs/n2.jpg
---

<section class="outer">
    <div class="inner bgwhite">
        <h2>Trang gioi thieu ve san pham</h2>
        {{ page.title }}
    </div>
</section>

<section class="outer">
    <div class="inner bgyellow tx-center">
        {% include content-blocks/services_list.html %}
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

