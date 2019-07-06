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
- name: Runa Das
  desc: Treasurer
  img:  rd.jpg
  link: https://www.facebook.com/runa.das.96
- name: Udipta Chetia Phukan
  desc: Exec. Member
  img:  mb4.jpg
  link: https://www.facebook.com/udipta.chetia.1
- name: Mondip Chakma
  desc: Exec. Member
  img:  mo.jpg
  link: https://www.facebook.com/mondip.chakma
acommittee:
- name: Bijay Kumar Boruah
  desc: Advisor
  img:  bb.jpg
- name: Kabita Gogoi
  desc: Advisor
  img:  kabita.jpg
  link: https://www.facebook.com/kabita.gogoi.906
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
