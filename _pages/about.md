---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.home-top {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 30px;
  max-width: 1100px;
  margin: 0 auto 40px auto;
}

.home-sidebar {
  flex-shrink: 0;
  width: 260px;
}

.home-sidebar .author__avatar img {
  max-width: 200px;
  border-radius: 50%;
}

.home-sidebar .author__urls li {
  font-size: 0.75em;
  white-space: normal;
}

.home-intro {
  flex: 1;
}

.home-intro p {
  font-size: 1em;
  line-height: 1.75;
  color: #494e52;
  margin-bottom: 1em;
}

.home-intro a {
  color: #52adc8;
  text-decoration: none;
}

.home-intro a:hover {
  text-decoration: underline;
}

.about-title {
  font-size: 1.8em;
  font-weight: bold;
  margin-top: 35px;
  margin-bottom: 20px;
  color: #494e52;
}

/* 아래 1컬럼 영역 */
.home-bottom {
  max-width: 1100px;
  margin: 0 auto;
}

.section-title {
  font-size: 1.5em;
  font-weight: normal;
  margin-top: 35px;
  margin-bottom: 20px;
  color: #494e52;
}

.news-table {
  width: 100%;
  border-collapse: collapse;
}

.news-table td {
  padding: 12px 0;
  vertical-align: top;
  border: none;
  font-size: 0.95em;
}

.news-table td:first-child {
  font-weight: 600;
  width: 120px;
  color: #494e52;
}

.news-table td:last-child {
  color: #494e52;
}

@media (max-width: 768px) {
  .home-top {
    flex-direction: column;
    gap: 30px;
  }
  
  .home-sidebar {
    width: 100%;
  }
}


</style>

<!-- 상단: 2컬럼 (프로필 | 소개글) -->
<div class="home-top">
  <div class="home-sidebar">
    {% include author-profile.html %}
  </div>
  
  <div class="home-intro">
    <h2 class="about-title">About Me!</h2>
    <p>Hello:) I am Migyeong Yang, and I go by Miggy. I received my Ph.D. in Applied Artificial Intelligence from Sungkyunkwan University (SKKU) in Seoul, Republic of Korea. Currently, I am a <b>Research Scientist</b> in the <b>Human-Computer Interaction (HCI) Research Group at NAVER AI Lab, NAVER Cloud</b>.
    
    <p> My research interests mainly revolve around HCI, Human-centered AI, and Affective Computing. I am excited about developing accessible AI-infused systems to address tangible, real-world challenges, especially in mental health and healthcare. I am enthusiastic about collaborating with experts across diverse domains. Feel free to reach out with collaboration proposals or for discussions anytime.</p>
    
    <p>For more details about me, please check my <a href="/cv/">CV</a>.</p>
  </div>
</div>

<!-- 하단: 1컬럼 (News, Publications) -->
<div class="home-bottom">
  <h2 class="section-title">News</h2>
  <table class="news-table">
    <tr>
      <td>Jan 2026</td>
      <td>Started a new position as Research Scientist at NAVER AI Lab!</td>
    </tr>
    <tr>
      <td>Aug 2025</td>
      <td>Successfully defended my PhD dissertation! 🎓</td>
    </tr>
    <tr>
      <td>Mar 2025</td>
      <td>Started as an Intern at NAVER AI Lab HCI Research Group.</td>
    </tr>
  </table>
  
  <h2 class="section-title">Selected Publications</h2>
  <p style="color: #494e52;">For a full list, please visit <a href="/publications/" style="color: #52adc8;">Publications</a>.</p>
</div>
