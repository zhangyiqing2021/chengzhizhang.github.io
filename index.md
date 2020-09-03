---
layout: page
title: About me
cover: false
---
I am a professor at ischool of [NJUST](http://english.njust.edu.cn/).
My [research](papers) interests include information retrieval, information organization, text mining and nature language processing. 

I am also a visiting scholar in the [School of Information Sciences (iSchool)](http://ischool.pitt.edu/) at the [University of Pittsburgh](http://www.pitt.edu/) and in the [Department of Linguistics and Translation ](lt.cityu.edu.hk/) at the [City University of Hong Kong](https://www.cityu.edu.hk/) 

 
## Recent News


## Recent Research Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

