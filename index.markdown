---
layout: single
permalink: /
author_profile: true
classes:
  - landing
  - wide
---

<div class="content-container">
  <p>I build systems that verify what’s true in the real world. My work bridges the gap between digital systems and physical infrastructure—making location, activity, and presence verifiable, secure, and programmable.</p>

<p>I co-founded Witness Chain to push the boundaries of how systems interact with the physical world. Before that, I spent years researching scalable, secure consensus systems across UIUC and Princeton University, focused on solving the so-called “blockchain trilemma.” I help teams build robust systems that are grounded in real-world constraints. I operate at the edge of research, engineering, and strategy.
</p>
  
  <h2>Roles</h2>
  <p>
  I’ve worked across research, entrepreneurship, and technical advisory roles. I co-founded and served as CEO of Witness Chain, leading efforts to bridge digital systems with real-world verification. I’ve advised multiple early-stage teams on system design and strategy. After my PhD, I was a Guest Lecturer at Princeton University, where I taught topics of Decentralized Finance. </p>
</div>

## Research Focus
My work explores how digital systems can reliably interface with the physical world. This spans infrastructure, intelligence, and incentive design across the following areas:


- Consensus protocols for reaching agreement on physical state
- Vision-language models (VLMs) for task planning in operations and robotics
- Design of robust financial instruments tied to real-world dynamics

## Selected Publications
<div class="featured-publications">
  {% assign bft_poloc = site.publications | where_exp: "item", "item.title contains 'BFT-PoLoc'" | first %}
  {% assign zeroswap = site.publications | where_exp: "item", "item.title contains 'ZeroSwap'" | first %}
  {% assign free2shard = site.publications | where_exp: "item", "item.title contains 'Free2Shard: Adversary'" | first %}
  
  {% assign selected_pubs = "" | split: "" %}
  {% if bft_poloc %}{% assign selected_pubs = selected_pubs | push: bft_poloc %}{% endif %}
  {% if zeroswap %}{% assign selected_pubs = selected_pubs | push: zeroswap %}{% endif %}
  {% if free2shard %}{% assign selected_pubs = selected_pubs | push: free2shard %}{% endif %}
  
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
<div class="see-all-link">
  <a href="/publications/" class="btn btn--primary">View All Publications</a>
</div>

## Selected Talks
<div class="grid__wrapper">
  {% assign selected_talks = "" | split: "" %}
  {% for talk in site.talks %}
    {% if talk.title == "Proof of Backhaul: Verifiable connectivity for Decentralized protocols" or talk.title == "Proof of Location: Trusted Observations for the Physical World" %}
      {% assign selected_talks = selected_talks | push: talk %}
    {% endif %}
  {% endfor %}
  
  {% for talk in selected_talks %}
  <div class="talk-card">
    <div class="talk-content">
      <h3><a href="{{ talk.videourl }}">{{ talk.title }}</a></h3>
      <p class="talk-meta">{{ talk.date | date: "%B %Y" }} • {{ talk.venue }}</p>
      <div class="talk-excerpt">
        {{ talk.content | markdownify | strip_html | truncate: 200 }}
      </div>
      <div class="talk-links">
        {% if talk.videourl %}<a href="{{ talk.videourl }}" class="btn btn--primary">Watch Video</a>{% endif %}
        {% if talk.slideurl %}<a href="{{ talk.slideurl }}" class="btn btn--primary">View Slides</a>{% endif %}
      </div>
    </div>
  </div>
  {% endfor %}
</div>
<div class="see-all-link">
  <a href="/talks/" class="btn btn--primary">View All Talks</a>
</div>

