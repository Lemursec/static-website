---
layout: page
title: Services
permalink: /services/
icon: fas fa-clipboard-check
order: 2
show_landing_pages: false
---

LemurSec specializes in the following core service areas.

<ul>
  {% for tab in site.tabs %}
    {% if tab.category == "services" %}
      <span>
        <a href="{{ tab.url | relative_url }}" class="nav-link services-link">
          <i class="fa-fw {{ tab.icon }}"></i>
          {% capture tab_name %}{{ tab.url | split: '/' }}{% endcapture %}
          <span>{{ site.data.locales[include.lang].tabs[tab_name] | default: tab.title | upcase }}</span>
        </a>
      </span>
    {% endif %}
  {% endfor %}
</ul>



{% if page.show_landing_pages == true %}
<h2><span class="me-2">Landing Pages</span></h2>

<ul>
  {% for tab in site.tabs %}
    {% if tab.show_in_nav == false %}
      <span>
        <a href="{{ tab.url | relative_url }}" class="nav-link services-link">
          <i class="fa-fw {{ tab.icon }}"></i>
          {% capture tab_name %}{{ tab.url | split: '/' }}{% endcapture %}
          <span>{{ site.data.locales[include.lang].tabs[tab_name] | default: tab.title | upcase }}</span>
        </a>
      </span>
    {% endif %}
  {% endfor %}
</ul>
{% endif %}

