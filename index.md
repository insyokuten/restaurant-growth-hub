---
layout: default
title: 飲食店の売上と利益を改善するヒント
description: 個人・小規模飲食店の経営者向けに、売上改善、原価管理、集客の実践的なヒントと無料ツールを提供します。
---
<section class="hero"><p class="eyebrow">個人・小規模飲食店の経営者へ</p><h1>お店の経営に、<br><em>次の一手を。</em></h1><p>売上、利益、集客。毎日の経営で迷ったときに役立つ、実践的な記事と無料ツールをお届けします。</p><div class="actions"><a class="button" href="{{ '/articles/' | relative_url }}">記事を読む</a><a class="button secondary" href="{{ '/tools/' | relative_url }}">無料ツールを使う</a></div></section>
<section class="section"><p class="eyebrow">CONTENTS</p><h2>経営に役立つコンテンツ</h2><div class="cards"><a class="card" href="{{ '/articles/' | relative_url }}"><span>01 / KNOWLEDGE</span><h3>経営改善の記事</h3><p>客単価、原価、集客、リピート対策などをわかりやすく解説。</p></a><a class="card" href="{{ '/tools/' | relative_url }}"><span>02 / TOOLS</span><h3>無料シミュレーター</h3><p>改善策を数字で確かめて、意思決定に活かせます。</p></a></div></section>
<section class="section"><h2>新着記事</h2>{% if site.posts.size > 0 %}<div class="cards">{% for post in site.posts limit: 6 %}<a class="card" href="{{ post.url | relative_url }}"><span>{{ post.date | date: '%Y.%m.%d' }}</span><h3>{{ post.title | escape }}</h3><p>{{ post.description | escape }}</p></a>{% endfor %}</div>{% else %}<p class="muted">記事を準備中です。公開後、こちらに表示されます。</p>{% endif %}</section>
