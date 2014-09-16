---
layout: post
kind: prdlist
class: billboard
img_pull: right
cnt_pull: left

title: Biển quảng cáo tấm lớn
postimage_url: '/hv-assets/imgs/h_preview/billboard2.jpg'
desc: hiệu quả luôn dẫn đầu...
pos: 01
detail: true
---

<div class="product-desc bgyellow tx-center">
    <h1>Hệ thống biển quảng cáo tấm lớn</h1>
    <p>Đoạn giới thiệu ngắn về hệ thống biển tấm lớn của HV...</p>
</div>

<div class="product-detail">
    {% for post in site.posts %}
        <div class="posts">
        {% if post.cats == 'billboard' %}
            <div class="{{ post.class }}-detail">
                {{ post.content }}
            </div>
            <hr>
        {% endif %}
    {% endfor %}
</div>

<p style="font-size:60px;"><i class="fa fa-refresh fa-spin"></i></p>