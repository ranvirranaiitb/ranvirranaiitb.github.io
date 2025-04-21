---
title: Research Publications
layout: single
permalink: /publications/
classes: wide
---

<div class="publications-header">
  <p>My research focuses on blockchain technology, distributed systems, cryptoeconomic security, and decentralized AI.</p>
</div>

## Selected Publications
<div class="featured-publications">
  {% assign bft_poloc = site.publications | where_exp: "item", "item.title contains 'BFT-PoLoc'" | first %}
  {% assign zeroswap = site.publications | where_exp: "item", "item.title contains 'ZeroSwap'" | first %}
  {% assign free2shard = site.publications | where_exp: "item", "item.title contains 'Free2Shard: Adversary'" | first %}
  {% assign communication = site.publications | where_exp: "item", "item.title contains 'Communication algorithms'" | first %}
  {% assign sakshi = site.publications | where_exp: "item", "item.title contains 'Sakshi'" | first %}
  
  {% assign selected_pubs = "" | split: "" %}
  {% if bft_poloc %}{% assign selected_pubs = selected_pubs | push: bft_poloc %}{% endif %}
  {% if zeroswap %}{% assign selected_pubs = selected_pubs | push: zeroswap %}{% endif %}
  {% if free2shard %}{% assign selected_pubs = selected_pubs | push: free2shard %}{% endif %}
  {% if communication %}{% assign selected_pubs = selected_pubs | push: communication %}{% endif %}
  {% if sakshi %}{% assign selected_pubs = selected_pubs | push: sakshi %}{% endif %}
  
  {% for pub in selected_pubs %}
    <div class="featured-publication-card">
      <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
      <p class="pub-excerpt">{{ pub.excerpt }}</p>
      <div class="pub-links">
        <a href="{{ pub.paperurl }}" class="paper-link">Paper</a>
        {% if pub.codeurl %}<a href="{{ pub.codeurl }}" class="code-link">Code</a>{% endif %}
        {% if pub.slideurl %}<a href="{{ pub.slideurl }}" class="slides-link">Slides</a>{% endif %}
      </div>
    </div>
  {% endfor %}
</div>

## All Publications
<div class="publications-container">
  {% assign sorted_publications = site.publications | sort: "date" | reverse %}
  {% for publication in sorted_publications %}
    <div class="publication-card">
      <h3><a href="{{ publication.url }}">{{ publication.title }}</a></h3>
      <p class="pub-excerpt">{{ publication.excerpt }}</p>
      <div class="pub-links">
        <a href="{{ publication.paperurl }}" class="paper-link">Paper</a>
        {% if publication.codeurl %}<a href="{{ publication.codeurl }}" class="code-link">Code</a>{% endif %}
        {% if publication.slideurl %}<a href="{{ publication.slideurl }}" class="slides-link">Slides</a>{% endif %}
      </div>
    </div>
  {% endfor %}
</div>

<div class="citation-note">
  <p><i>For detailed citation information or to request full-text copies of any publication, please <a href="/about/">contact me</a>.</i></p>
</div>

<!-- This empty element prevents Jekyll from adding default collection content -->
<div class="empty-element-to-prevent-auto-entries-layout"></div>