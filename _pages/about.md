---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/about.css?v={{ site.time | date: '%s' }}">
<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/publications.css?v={{ site.time | date: '%s' }}">

<!-- 상단: hero (사진 | 이름, 링크, Short bio) -->
<div class="home-hero">
  <img class="hero-photo" src="{{ site.baseurl }}/images/{{ site.author.avatar }}" alt="Photo of {{ site.author.name }}">

  <div class="hero-main">
    <h1 class="hero-name">{{ site.author.name }}, PhD</h1>
    <p class="hero-role">Research Scientist at NAVER AI Lab · HCI Researcher</p>

    {% include profile-links.html %}

    <h2 class="hero-subtitle">Short bio</h2>
    <table class="bio-table">
      <tr>
        <td>2026 – Now</td>
        <td><b>Research Scientist</b>, HCI Research Group, NAVER AI Lab</td>
      </tr>
      <tr>
        <td>2025</td>
        <td><b>Postdoctoral Fellow</b>, Center for Multimedia Intelligence, Sungkyunkwan University</td>
      </tr>
      <tr>
        <td>2025</td>
        <td><b>Research Intern</b>, HCI Research Group, NAVER AI Lab</td>
      </tr>
      <tr>
        <td>2020 – 2025</td>
        <td><b>Ph.D.</b> in Applied Artificial Intelligence, Sungkyunkwan University</td>
      </tr>
      <tr>
        <td>2017 – 2020</td>
        <td><b>B.A.</b> in Media Technology and Robot Engineering, Hanyang University ERICA</td>
      </tr>
    </table>
  </div>
</div>

<div class="home-bottom">
  <h2 class="section-title">About Me</h2>
  <div class="home-intro">
    <p>I am a Research Scientist at NAVER AI Lab at NAVER Corporation, working in the Human-Computer Interaction (HCI) Research Group led by <a href="https://younghokim.net/">Young-Ho Kim</a>.
    I design <b>AI systems that understand people more fully</b>, especially those whose ways of expressing themselves fall outside what AI usually assumes. Currently, I work on AI systems that <b>support neurodiverse people</b> and embrace the many different ways human experience shows up.</p>

    <p>I started out as a model builder. During my Ph.D., I developed AI systems that help art therapists assess drawings, where things too difficult to say often find their way out. The more models I built, the clearer it became that the hard part wasn't the model. It was the therapist who had to trust it, the client whose drawing it was reading, and everything that happened between them. That pulled me into HCI.</p>

    <p>Most AI is built around a narrow idea of "the user," and when someone falls outside it, the person is expected to adapt, not the system. The question I keep returning to is: <b>how do we design AI that supports people in ways that actually matter to them?</b></p>
  </div>

  <h2 class="section-title">News</h2>
  <table class="news-table">
    <tr>
      <td>Oct 2026</td>
      <td>Honored to present our paper "BetaDAPR: An AI-based Expert Support System for Art Therapists with Qualitative and Quantitative Assistance" at ACM CSCW 2026 in Salt Lake City, Utah! 🎤</td>
    </tr>
    <tr>
      <td>Apr 2026</td>
      <td>Presented my first CHI paper, "Autiverse: Eliciting Autistic Adolescents' Daily Narratives through AI-guided Multimodal Journaling," at ACM CHI 2026 in Barcelona, Spain! 🇪🇸</td>
    </tr>
    <tr>
      <td>Apr 2026</td>
      <td>Our paper "BetaDAPR: An AI-based Expert Support System for Art Therapists with Qualitative and Quantitative Assistance" has been accepted to ACM CSCW 2026 (PACM HCI)! 🎊</td>
    </tr>
  </table>
  
  <h2 class="section-title">Selected Publications</h2>
  <p class="section-description">For a full list, please visit <a href="/publications/">Publications</a>.</p>
  {% assign selected_pubs = site.publications | where: "selected", true | sort: "date" | reverse %}
  {% for post in selected_pubs %}
    {% include pub-item.html post=post %}
  {% endfor %}
</div>
