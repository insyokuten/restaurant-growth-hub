---
layout: default
title: 飲食店の売上・利益・集客を改善する経営支援
description: 個人・小規模飲食店の経営者向け。売上・利益・集客の悩みに役立つ経営改善記事、無料シミュレーター、公式LINEの無料売上アップAI診断をご案内します。
---
<section class="hero home-hero" aria-labelledby="home-title">
  <div class="home-hero-inner">
    <p class="eyebrow">個人・小規模飲食店の経営者へ</p>
    <h1 id="home-title">お店の経営に、<br><em>次の一手を。</em></h1>
    <p class="home-hero-lead">売上・利益・集客の悩みを、ひとりで抱え込まない。<br>実践的な経営ノウハウとAIで、お店の改善をサポートします。</p>
    <div class="actions">
      <a class="button home-primary-button" href="{{ site.line_url | escape }}" target="_blank" rel="noopener noreferrer">公式LINEで無料売上アップAI診断</a>
      <a class="button secondary" href="{{ '/articles/' | relative_url }}">経営改善の記事を読む</a>
    </div>
    <p class="home-helper">無料診断は公式LINEからご利用いただけます。</p>
  </div>
</section>
<section class="section home-section" aria-labelledby="home-problems">
  <p class="eyebrow">YOUR CHALLENGES</p>
  <h2 id="home-problems">こんなお悩みはありませんか？</h2>
  <div class="home-problem-grid">
    <div class="home-problem">売上が伸び悩んでいる</div>
    <div class="home-problem">原価や利益を改善したい</div>
    <div class="home-problem">新規のお客様を増やしたい</div>
    <div class="home-problem">リピーターを増やしたい</div>
  </div>
  <p class="home-section-note">経営課題を整理し、数字と具体策の両面から改善のヒントを探せます。</p>
</section>
<section class="section home-section" aria-labelledby="home-content">
  <p class="eyebrow">CONTENTS</p>
  <h2 id="home-content">経営改善に役立つコンテンツ</h2>
  <div class="cards home-content-cards">
    <a class="card" href="{{ '/articles/' | relative_url }}"><span>01 / KNOWLEDGE</span><h3>経営改善の記事</h3><p>客単価、原価管理、集客、リピート対策など、日々の経営に役立つ考え方をわかりやすく解説。</p><strong class="home-card-link">記事一覧を見る →</strong></a>
    <a class="card" href="{{ '/tools/' | relative_url }}"><span>02 / TOOLS</span><h3>無料シミュレーター</h3><p>売上や利益がどう変わるかを数字で確認し、改善策の検討に役立てられます。</p><strong class="home-card-link">無料ツールを見る →</strong></a>
  </div>
</section>
<section class="section home-section" aria-labelledby="home-latest">
  <div class="home-heading-row"><div><p class="eyebrow">LATEST ARTICLES</p><h2 id="home-latest">新着記事</h2></div><a class="home-text-link" href="{{ '/articles/' | relative_url }}">記事一覧へ →</a></div>
  {% if site.posts.size > 0 %}
  <div class="cards home-article-cards">
    {% for post in site.posts limit: 6 %}
    <a class="card" href="{{ post.url | relative_url }}"><span>{{ post.date | date: '%Y.%m.%d' }}</span><h3>{{ post.title | escape }}</h3>{% if post.description %}<p>{{ post.description | escape }}</p>{% endif %}<strong class="home-card-link">続きを読む →</strong></a>
    {% endfor %}
  </div>
  {% else %}
  <p class="muted">記事を準備中です。公開後、こちらに表示されます。</p>
  {% endif %}
</section>
<section class="home-bottom-cta" aria-labelledby="home-cta-title">
  <p class="eyebrow">FREE AI DIAGNOSIS</p>
  <h2 id="home-cta-title">あなたのお店に合った、改善のヒントを。</h2>
  <p>まずは無料の売上アップAI診断から。<br>経営課題を整理するきっかけにご活用ください。</p>
  <a class="button home-primary-button" href="{{ site.line_url | escape }}" target="_blank" rel="noopener noreferrer">公式LINEで無料診断する</a>
  <p class="home-cta-note">診断結果は売上改善を保証するものではありません。</p>
</section>
