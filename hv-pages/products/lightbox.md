---
layout: post
kind: prdlist
class: lightbox
img_pull: left
cnt_pull: right

title: Biển trên dải phân cách
postimage_url: '/hv-assets/imgs/h_preview/lightbox2.jpg'
desc: sẵn sàng suốt ngày đêm...
pos: 02
detail: true

bg: /hv-assets/imgs/h_preview/lightbox2.jpg
---

<div id="lightboxmap" style="height:350px;"></div>

<div class="product-desc bgyellow tx-center">
    <h1>Hệ thống biển trên dải phân cách</h1>
    <p>Hệ thống biển hộp đèn trên dải phân cách đã và đang được xây dựng trên nhiều tuyến phố lớn ở HN.<br>Vừa tầm mắt, tầm nhìn rộng, có đèn chiếu sáng ban đêm...</p>

    <ul class="intro-list">
        <li><a class="btn" href="#">Một số hình ảnh thực tế</a></li>
        <li><a class="btn" href="#">Thiết kế điển hình</a></li>
    </ul>
</div>

<div class="product-detail">
    {% include prd_lightbox/dongda.html %}
</div>

<div class="product-detail">
    {% include prd_lightbox/badinh.html %}
</div>

<div class="product-detail">
    {% include prd_lightbox/tayho.html %}
</div>

<div class="product-detail">
    {% include prd_lightbox/thanhxuan.html %}
</div>


<div class="product-detail">
    {% include prd_lightbox/caugiay.html %}
</div>

<div class="product-detail">
    {% include prd_lightbox/tuliem.html %}
</div>



<p style="font-size:60px;"><i class="fa fa-refresh fa-spin"></i></p>

<!-- use mapbox for displaying maps -->
<script src='https://api.tiles.mapbox.com/mapbox.js/v2.1.0/mapbox.js'></script>

<script>
    L.mapbox.accessToken = 'pk.eyJ1IjoieGFiZW5nIiwiYSI6InBBRUsyV00ifQ.7Yx2re8GKhtZ83sg0oPHGQ';
    var map = L.mapbox.map('lightboxmap', 'xabeng.jiikdb7b')
        .setView([21.032, 105.824],12);     
</script>