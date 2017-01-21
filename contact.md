---
layout: page
title: Contact
permalink: /contact/
---

Otomori wordt ontwikkeld door:
<br>
<br>
<a href="http://www.timohoogland.com" target="_blank">Timo Hoogland</a> & <a href="http://www.ninodewit.com" target="_blank">Nino de Wit</a>.
<br>
<br>
<div class="footer-col-wrapper">
      <div class="footer-col footer-col-1">
        <ul class="contact-list">
          <li>
            {% if site.author %}
              {{ site.author | escape }}
            {% else %}
              {{ site.title | escape }}
            {% endif %}
            </li>
            {% if site.email %}
            <li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
            {% endif %}
        </ul>
      </div>

      <div class="footer-col footer-col-2">
        <ul class="social-media-list">
          {% if site.github_username %}
          <li>
            {% include icon-github.html username=site.github_username %}
          </li>
          {% endif %}

          {% if site.twitter_username %}
          <li>
            {% include icon-twitter.html username=site.twitter_username %}
          </li>
          {% endif %}
        </ul>
      </div>

      <div class="footer-col footer-col-3">
        <p>{{ site.description | escape }}</p>
      </div>
    </div>
    
<info.otomori@gmail.com>

&nbsp;

&nbsp;
