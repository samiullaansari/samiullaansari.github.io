---
layout: default
title: Home
---

<div class="header">

  <img src="/assets/profile.jpg" class="profile-img">

  <div class="header-text">
    <h1>Samiulla Ansari</h1>
    <p class="tagline">
      I build AI systems for real-world impact across NLP, Generative AI and large-scale ML systems.
    </p>

    <div class="social">
      <a href="https://github.com/samiullaansari">GitHub</a>
      <a href="https://www.linkedin.com/in/sami-iitb/">LinkedIn</a>
      <a href="#">X</a>
    </div>
  </div>

</div>

<div class="divider"></div>

## Career

<div class="career">

  <div class="row">
    <div class="year">2022 - Present</div>
    <div class="line"><div class="dot"></div></div>

    <div class="content">
      <img src="/assets/hsbc.png" class="logo">
      <div class="content-text">
        <b>HSBC</b>, AI/ML Engineer<br>
        Built production NLP systems for financial data processing and scalable ML pipelines.
      </div>
    </div>
  </div>

  <div class="row">
    <div class="year">2019 - 2022</div>
    <div class="line"><div class="dot"></div></div>

    <div class="content">
      <img src="/assets/jio.jpg" class="logo">
      <div class="content-text">
        <b>Jio</b>, Data Scientist<br>
        Worked on large-scale telecom data and predictive ML systems.
      </div>
    </div>
  </div>

</div>

<div class="divider"></div>

## Projects

- [AI Interview Questions](https://github.com/samiullaansari/AI-Interview-Questions)

---

## Writing

{% raw %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endraw %}

