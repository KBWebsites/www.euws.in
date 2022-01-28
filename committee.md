---
title: Committee
layout: default
ecommittee:

- name: Manoj Borgohain
  desc: President
  img:  mb3.jpg
  link: https://www.facebook.com/bipakshi.mohan
- name: Mitalima Baruah
  desc: Vice President
  img:  uc.jpg
  link: https://www.facebook.com/mithu.baruah.14
- name: Mahendra Bagaria
  desc: General Secretary
  img:  mb1.jpg
  link: https://www.facebook.com/MahendraBagaria
- name: Wahida Ahmed
  desc: Asst. Secretary
  img:  wa1.jpg
  link: https://www.facebook.com/wahida.ahmed.5667
- name: Benazeer Khatun
  desc: Treasurer
  img:  df-g.jpg
  link: https://www.facebook.com/profile.php?id=100007493717151
- name: Popi Kalita Hazarika
  desc: Exec. Member
  img:  pkh.jpg
- name: Mondip Chakma
  desc: Exec. Member
  img:  mo.jpg
  link: https://www.facebook.com/mondip.chakma
acommittee:
- name: Ramesh Gohain
  desc: Chief Advisor
  img:  rg.jpg
  link: https://www.facebook.com/ramesh.gohain.399
---
### Executive Committee

<div class="committee">
{% for m in page.ecommittee %}
<div class="thumbnail">
{% if m.link %}<a href="{{ m.link }}">{% endif %}<div style="background:url(/files/committee/{{ m.img }}) center;margin:auto;background-size:cover;width:125px;height:125px"></div>{% if m.link %}</a>{% endif %}
<div class="caption">
<h4>{% if m.link %}<a href="{{ m.link }}">{{ m.name }}</a>{% else %}{{ m.name }}{% endif %}</h4>
<h5>{{ m.desc }}</h5>
</div>
</div>
{% endfor %}
</div>

<br/>

### Advisory Committee

<div class="committee a">
{% for m in page.acommittee %}
<div class="thumbnail">
{% if m.link %}<a href="{{ m.link }}">{% endif %}<div style="background:url(/files/committee/{{ m.img }}) center;margin:auto;background-size:cover;width:125px;height:125px"></div>{% if m.link %}</a>{% endif %}
<div class="caption">
<h4>{% if m.link %}<a href="{{ m.link }}">{{ m.name }}</a>{% else %}{{ m.name }}{% endif %}</h4>
<!-- <h5>{{ m.desc }}</h5> -->
</div>
</div>
{% endfor %}
</div>
