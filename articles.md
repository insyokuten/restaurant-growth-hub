---
layout: default
title: 記事一覧
description: 飲食店の売上改善、利益向上、集客に役立つ記事一覧。
permalink: /articles/
---
<section class="section"><p class="eyebrow">ARTICLES</p><h1>経営改善の記事一覧</h1><p>今日から試せる、飲食店経営のヒントをお届けします。</p>{% if site.posts.size > 0 %}<div class="cards">{% for post in site.posts %}<a class="card" href="{{ post.url | relative_url }}"><span>{{ post.date | date: '%Y.%m.%d' }}</span><h2>{{ post.title | escape }}</h2><p>{{ post.description | escape }}</p></a>{% endfor %}</div>{% else %}<p class="muted">現在、公開済みの記事はありません。記事は確認・承認後に追加します。</p>{% endif %}</section>
