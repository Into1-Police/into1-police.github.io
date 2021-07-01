---
layout: articles
title: 高卿尘图鉴
permalink: /nine-collection
pageview: false
---

<div class="item">
  <div class="item__image">
    <img class="image" src="../assets/images/cover/nine-cover.jpg"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>高卿尘(aka Nine,小九)</h4>
    </div>
    <div class="item__description">
      <p>高卿尘，泰国洞察娱乐练习生，前泰国组合OXQ成员，现into1成员。<br> 因参加创造营并以第五名高位出道而引起巨大争议。 作为选秀出道的公众人物，面对平均年龄相对小的粉圈群体，本应该建立正面形象，给青少年做正向引导。然而，经网友搜集发现，其公司及其本人不仅营销虚假人设获得流量，其背后的公司更是用各种手段挑起粉圈争端。into1其他成员粉丝及其本人都被各种anti和辱骂，深受其扰。</p>
      <a href="https://kprofiles.com/oxq-members-profile/">部分资料来源</a>
    </div>
  </div>
</div>

<div class="layout--articles">
  <section class="my-5">
    {% assign sorted-posts = site.posts | where: "categories","nine" %}
    {%- include article-list.html articles=sorted-posts type='item' show_readmore='true' show_excerpt='true' -%}
  </section>
</div>