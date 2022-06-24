---
permalink: /
title: "Bhavish Pahwa"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dynamic and focused, final year undergrad with experience of more than a year in the professional tech industry. Early Career researcher working in Computational Social Science, with a particular focus on hate speech and abusive language detection on social media platforms, eager to contribute to developing an inclusive, safe social space for all communities. Beginner in open source contributions, deeply motivated by the ideology to democratize AI research.

# News

<div style="overflow-y:scroll; height:12em;">
<ul>
<li class="a"><strong>MAY, 2022</strong>:Attended <a href="https://www.2022.aclweb.org/" target="_blank">ACL 2022</a> as a student volunteer as well as had a poster presentation at co-located workshop <a href="https://dravidianlangtech.github.io/2022/" target="_blank">DravidianLangTech-2022</a> </li>
</ul>
</div>
<br>

# Work Experience

<ul>
{% for item in site.data.workex.experiences %}
<li class="a">
  <table class="a"><tr>
  <td class="a" width="20%"><img class="padded-image" src="/images/{{ item.img-path }}" alt="{{ item.name }}" style="width:100%"></td>
  <td class="a" width="80%">
  <span class="designation">{{ item.designation }}</span><br>
  <a class="company" href="{{ item.url }}" target="_blank">{{ item.name }}</a><br>
  <span class="date">{{item.date}}</span><br>
  <p class="desc">
  <br>
  {{item.desc}}
  </p><br>
  </td>
  </tr></table>
  </li>
{% endfor %}
</ul>

<br>
