---
title: portfolio
layout: default
permalink: /portfolio/
gallery_boardgame:
  - url:
    image_path:
    alt:
    title:
    caption:
---
# A portfolio page.

<div style="display: flex; flex-wrap: wrap; gap:2rem; align-items: flex-start;">
  <div style="flex: 1 1 250px; min-width: 250px;">
    <h2>Board Games<h2>
      <p>This section is about Board Games</p>
  </div>
  <div style="flex: 1 1 250px; min-width: 250px;">
    {% include gallery id="gallery_boardgame" layout="third" thumb_height="180px" %}
  </div>
</div>
