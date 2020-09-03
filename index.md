---
layout: page
title: About me
cover: false
---
I am a professor at ischool of [NJUST](http://english.njust.edu.cn/).
My [research](papers) interests include information retrieval, information organization, text mining and nature language processing. 

I am also a visiting scholar in the [School of Information Sciences (iSchool)](http://ischool.pitt.edu/) at the [University of Pittsburgh](http://www.pitt.edu/) and in the [Department of Linguistics and Translation ](lt.cityu.edu.hk/) at the [City University of Hong Kong](https://www.cityu.edu.hk/) 

 
## Recent News
* In July 2020, I joined the research team at [Rasa](https://rasa.com)! I'm [leading a new research and product hub in Edinburgh](https://www.prnewswire.com/news-releases/rasa-raises-26m-in-series-b-funding-led-by-andreessen-horowitz-301081571.html).
  
* In 2019, five of my PhD students successfully defended their theses:
  - [Sameer Bansal](https://0xsameer.github.io/), whose [thesis](https://era.ed.ac.uk/handle/1842/36781) was on 
    Low-Resource Speech Translation. He is now a researcher at Bloomberg.
  - [Arabella Jane Sinclair](https://staff.fnwi.uva.nl/a.j.sinclair/),
    whose [thesis](https://era.ed.ac.uk/handle/1842/37009) was on Modelling Speaker Adaptation in Second 
    Language Learner Dialogue. 
    She is now a postdoctoral researcher at the University of Amsterdam.
  - [Clara Vania](https://claravania.github.io/), whose [thesis](https://era.ed.ac.uk/handle/1842/36742) was 
    On Understanding Character-level Models for Representing Morphology.
    She is now a postdoctoral researcher at New York University.
  - [Nikolay Bogoychev](https://nbogoychev.com/),
    whose [thesis](https://www.era.lib.ed.ac.uk/handle/1842/35886) 
    was on Fast Machine Translation on Parallel and Massively Parallel 
    Hardware. 
    He is now a postdoctoral researcher at the University of Edinburgh.
  - [Sorcha Gilroy](https://uk.linkedin.com/in/sorcha-gilroy-a6105693), whose 
    [thesis](https://www.era.lib.ed.ac.uk/handle/1842/35606) was on 
    Probabilistic Graph Formalisms for Meaning Representations. 
    She is now a data scientist at Peak.ai.

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

