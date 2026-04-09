---
title: "home"
layout: default
permalink: /
---
<div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">
  <div style="flex: 1 1 250px; min-width: 250px;">
    <h2 style="font-family:Source Code Pro">About Me</h2>
    <p>I am a ... </p>
    {% include button
    label="Download CV"
    class="btn--primary"
    download=""
    %}
  </div>
  <div style="flex: 1 1 250px; min-width: 250px;">
    {% include figure image_path="/assets/images/placeholder-2.png" alt="Headshot of Ben McKee" style="width:100px height:100px" %}
  </div>
</div>
