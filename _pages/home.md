---
title: "Simulation of European Politics"
layout: splash
permalink: /
date: 2017-04-11 01:48:41 -04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-meu2015.jpg
  _cta_label: "Join Our Network"
  _cta_url: "http://forum.beta-europe.org"
  caption: "Photo credit: [**MEUS 2015**](http://www.meu-strasbourg.org)"
excerpt: "Bringing Europeans Together Association Slovakia (BETA Slovakia) is a politically independent, non-profit association aiming to organize simulations of European politics – Model European Union Bratislava.  "

intro_01:
  - title: Our Association
    image_path:  /assets/images/beta-logo-200-transparent.png 
    alt: "Logo of BETA Slovakia"
    excerpt:
    |
      Bringing European Together Association Slovakia (BETA Slovakia) is a young, politically independent, non-profit organisation founded in 2017 by 8 Europeans in Bratislava. As one of its 10 branches, we share the core objectives and values of the Bringing Europeans Together Association Europe (BETA e.V.) based in Mainz, Germany. The BETA network constitutes of more than 1,500 youth of 33 nationalities and supports over 20 events worldwide.
    url: "/contact/"
    btn_label: "People behind BETA Slovakia"
    btn_class: "btn--primary"
intro_02:
  - title: Our Mission
    image_path: /assets/images/ourmission.jpeg
    alt: "Group Photo BETA Slovakia"
    excerpt:
    |
Our mission is to promote European consciousness and identity based on plurality, tolerance and cooperation in Slovakia and beyond. We aim to further strengthen European civil society by developing critical thinking in young people through intercultural dialogue and informal education.
    url: "/about/"
    btn_label: "About Us"
    btn_class: "btn--primary"

    |
      In order to achieve its goals, BETA Slovakia organises different MEUs in Slovakia.
    _url: "/calendar/"
    _btn_label: "Conference Calendar"
    _btn_class: "btn--primary"

---

{% include feature_row id="intro_01" type="left" %}

{% include feature_row id="intro_02" type="right" %}

{% include feature_row id="intro_03" type="left" %}

<div class="layout--splash__recent--posts">
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
</div>
