---
title: Talks & Panels
layout: single
permalink: /talks/
classes: wide
---

<div class="publications-header">
  <p>Presentations, keynotes, and speaking engagements at conferences, workshops, and events.</p>
</div>

## Featured Talks
<div class="featured-publications">
  {% assign selected_talks = "" | split: "" %}
  {% for talk in site.talks %}
    {% if talk.title == "Proof of Backhaul: Verifiable connectivity for Decentralized protocols" or talk.title == "Proof of Location: Trusted Observations for the Physical World" %}
      {% assign selected_talks = selected_talks | push: talk %}
    {% endif %}
  {% endfor %}
  
  {% for talk in selected_talks %}
    <div class="featured-publication-card">
      <h3><a href="{{ talk.videourl | default: talk.eventurl | default: talk.url }}">{{ talk.title }}</a></h3>
      <p class="pub-excerpt">{{ talk.date | date: "%B %Y" }} • {{ talk.venue }}</p>
      <p class="pub-excerpt">{{ talk.excerpt }}</p>
      <div class="pub-links">
        {% if talk.videourl %}<a href="{{ talk.videourl }}" class="paper-link">Video</a>{% endif %}
        {% if talk.slideurl %}<a href="{{ talk.slideurl }}" class="code-link">Slides</a>{% endif %}
        {% if talk.eventurl %}<a href="{{ talk.eventurl }}" class="slides-link">Event</a>{% endif %}
      </div>
    </div>
  {% endfor %}
</div>

## All Talks
<div class="publications-container">
  {% assign sorted_talks = site.talks | sort: "date" | reverse %}
  {% for talk in sorted_talks %}
    <div class="publication-card">
      <h3><a href="{{ talk.videourl | default: talk.eventurl | default: talk.url }}">{{ talk.title }}</a></h3>
      <p class="pub-excerpt">{{ talk.date | date: "%B %Y" }} • {{ talk.venue }}</p>
      <p class="pub-excerpt">{{ talk.excerpt }}</p>
      <div class="pub-links">
        {% if talk.videourl %}<a href="{{ talk.videourl }}" class="paper-link">Video</a>{% endif %}
        {% if talk.slideurl %}<a href="{{ talk.slideurl }}" class="code-link">Slides</a>{% endif %}
        {% if talk.eventurl %}<a href="{{ talk.eventurl }}" class="slides-link">Event</a>{% endif %}
      </div>
    </div>
  {% endfor %}
</div>

<!-- This empty element prevents Jekyll from adding default collection content -->
<div class="empty-element-to-prevent-auto-entries-layout"></div>