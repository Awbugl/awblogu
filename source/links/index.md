---
title: 友链
type: links
date: 2022-11-19 01:23:30
---
<div class="links-content">
<div class="no-icon note warning">
<div class="link-info">来点友链！</div>
<div class="link-info">排序不分先后</div>
<div class="link-info"><del>我也不知道这是怎么排的</del></div></div>
<div class="link-navigation">
{% for link in site.data.links %}
<div class="card"><img class="ava nomediumzoom" src="{{ link.avatar }}"/>
<div class="card-header">
<div><a href="{{ link.site }}" target="_blank"> {{ link.name }}</a> </div>
<div class="info">{{ link.info }}</div>
</div>
</div>
{% endfor %}
</div>
{% note success %}
**友链申请格式：**
```
- name: Awblogu
  info: 啊呜布洛咕
  site: https://blog.awbugl.top
  avatar: https://blog.awbugl.top/images/avatar.jpg
```
{% endnote %}
