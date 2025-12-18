---
layout: home
---

{% include hero.html %}
{% include header.html %}
{% include services.html %}
{% include portfolio.html %}
{% include about.html %}
{% include timeline.html %}
{% include team.html %}
{% include clients.html %}
{% include contact.html %}

<!-- Only one popup -->
{% if site.popup.show %}
<div id="popup" style="position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.6);display:flex;align-items:center;justify-content:center;z-index:9999;">
  <div style="background:white;padding:2rem;text-align:center;max-width:400px;border-radius:8px;">
    <h2>{{ site.popup.title }}</h2>
    <p>{{ site.popup.message }}</p>
    <a href="{{ site.popup.button_link }}" class="btn btn-primary">{{ site.popup.button_text }}</a>
    <button onclick="document.getElementById('popup').style.display='none'" style="margin-top:1rem;">Close</button>
  </div>
</div>
{% endif %}
