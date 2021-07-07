---
layout: articles
title: 草莓酱图鉴
permalink: /ninefans-collection
pageview: false
---

<div class="item">
  <div class="item__image">
    <img class="image" src="../assets/images/strawberry.png"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>高卿尘粉丝(aka 草莓酱)</h4>
    </div>
    <div class="item__description">
        高卿尘后援会皮下及其大粉带头引导互撕谩骂、拉踩引战、造谣攻击、人肉网暴等行为，在豆瓣等平台多次组织屠版等“团建”活动，企图干扰舆论、破坏粉圈生态。更有粉丝在线上anti艺人，肆意宣泄恶意。
    </div>
  </div>
</div>

<div class="layout--articles">
  <section class="my-5">
    {% assign sorted-posts = site.posts | where: "categories","nine-fans" %}
    {%- include article-list.html articles=sorted-posts type='item' show_readmore='true' show_excerpt='true' -%}
  </section>
</div>