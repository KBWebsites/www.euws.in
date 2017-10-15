---
title: Committee
layout: default
ecommittee:
- name: Arun Jain
  desc: President
  img:  aj1.jpg
  link: https://www.facebook.com/profile.php?id=100010568193063
- name: Amardip Singh Dhaliwal
  desc: Vice President
  img:  as.jpg
  link: https://www.facebook.com/amardipdhaliwal
- name: Mahendra Bagaria
  desc: General Secretary
  img:  mb1.jpg
  link: https://www.facebook.com/MahendraBagaria
- name: Rubi Gogoi
  desc: Asst. Secretary
  img:  ruby.jpg
  link: https://www.facebook.com/rubi.gogoi.75457
- name: Manoj Borgohain
  desc: Treasurer
  img:  mb3.jpg
  link: https://www.facebook.com/bipakshi.mohan
- name: Swapna G. Nahardeka
  desc: Exec. Member
  img:  sg1.jpg
  link: https://www.facebook.com/profile.php?id=100009180797036
- name: Wahida Ahmed
  desc: Exec. Member
  img:  wahida.jpg
  link: https://www.facebook.com/wahida.ahmed.5667
- name: Bismoy Bhardwaj
  desc: Exec. Member
  img:  bismoy.jpg
  link: https://www.facebook.com/stenwulf.shadowbane
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
