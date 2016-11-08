---
title: Committee
layout: default
ecommittee:
- name: Arun Jain
  desc: President
  img:  aj.jpg
- name: Amardip Singh Dhaliwal
  desc: Vice President
  img:  as.jpg
  link: https://www.facebook.com/amardipdhaliwal
- name: Mahendra Bagaria
  desc: General Secretary
  img:  mb.jpg
  link: https://www.facebook.com/MahendraBagaria
- name: Shahnawaz Ahmed
  desc: Asst. Secretary
  img:  sna.jpg
  link: https://www.facebook.com/shahnawaz.ahmed.9887
- name: Manoj Borgohain
  desc: Treasurer
  img:  mb2.jpg
  link: https://www.facebook.com/manoj.gohain1
- name: Hiren Gogoi
  desc: Project Manager
  img:  hiren.jpg
  link: https://www.facebook.com/hiren.gogoi.54
- name: Swapna G. Nahardeka
  desc: Exec. Member
  img:  sg.jpg
- name: Wahida Ahmed
  desc: Exec. Member
  img:  wahida.jpg
  link: https://www.facebook.com/wahida.ahmed.5667
- name: Bismoy Bhardwaj
  desc: Exec. Member
  img:  bismoy.jpg
  link: https://www.facebook.com/stenwulf.shadowbane
acommittee:
- name: Podmeswar Phukan
  desc: Advisor
  img:  podmeswar.jpg
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
{% if m.link %}<a href="{{ m.link }}">{% endif %}<img alt="{{ m.name }}" src="/files/committee/{{ m.img }}" width="125">{% if m.link %}</a>{% endif %}
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
{% if m.link %}<a href="{{ m.link }}">{% endif %}<img alt="{{ m.name }}" src="/files/committee/{{ m.img }}" width="125">{% if m.link %}</a>{% endif %}
<div class="caption">
<h4>{% if m.link %}<a href="{{ m.link }}">{{ m.name }}</a>{% else %}{{ m.name }}{% endif %}</h4>
<!-- <h5>{{ m.desc }}</h5> -->
</div>
</div>
{% endfor %}
</div>
