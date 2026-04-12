---
title: "home"
layout: default
permalink: /
---
<div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">
  <div style="flex: 1 1 250px; min-width: 250px;">
    <h2 class="source-code-pro" style="width:600px">About Me</h2>
    <p style="width:600px">I am a ... </p>
    {% include button
    title="Download my CV"
    label="Download CV"
    class="btn--primary"
    url="/assets/downloads/Ben-McKee-CV.pdf"
    download="Ben-McKee-CV.pdf"
    %}
  </div>
  <div style="flex: 1 1 250px; min-width: 250px;">
    {% include figure image_path="/assets/images/Headshot_edit.png" alt="Headshot of Ben McKee" style="width:100px height:100px" %}
  </div>
</div>
