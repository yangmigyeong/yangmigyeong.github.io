---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.home-wrapper {
  max-width: 1200px;
  margin: 0 auto;
}

.home-header {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 50px;
  margin-bottom: 50px;
}

/* 왼쪽 프로필 - 기존 사이드바 스타일 */
.home-profile {
  flex-shrink: 0;
  width: 260px;
}

.home-profile img {
  width: 100%;
  max-width: 200px;
  border-radius: 50%;
  display: block;
  margin: 0 auto 15px auto;
}

.home-profile-name {
  margin-top: 0;
  margin-bottom: 5px;
  font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
  font-size: 1.25em;
  font-weight: bold;
  text-align: center;
}

.home-profile-title {
  font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
  font-size: 0.9em;
  color: #7a8288;
  text-align: center;
  margin-bottom: 15px;
}

.home-profile-links {
  font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
  font-size: 0.9em;
  list-style: none;
  padding: 0;
  margin: 0;
}

.home-profile-links li {
  margin-bottom: 8px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.home-profile-links a {
  color: #494e52;
  text-decoration: none;
}

.home-profile-links a:hover {
  text-decoration: underline;
}

.home-profile-links i {
  width: 1.25em;
  margin-right: 0.5em;
  color: #7a8288;
}

/* 오른쪽 본문 */
.home-content {
  flex: 1;
  font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
}

.home-content p {
  font-size: 1em;
  line-height: 1.75;
  color: #494e52;
  margin-bottom: 1em;
}

.home-content a {
  color: #52adc8;
  text-decoration: none;
}

.home-content a:hover {
  text-decoration: underline;
}

/* 아래 섹션 (News, Publications) - 1 column */
.home-section {
  max-width: 1200px;
  margin: 0 auto;
}

.section-title {
  font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
  font-size: 1.5em;
  font-weight: normal;
  margin-top: 30px;
  margin-bottom: 20px;
  color: #494e52;
}

.news-table {
  width: 100%;
  border-collapse: collapse;
  font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", "Helvetica Neue", "Lucida Grande", Arial, sans-serif;
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
  .home-header {
    flex-direction: column;
    gap: 30px;
  }
  
  .home-profile {
    width: 100%;
    text-align: center;
  }
}
</style>

<div class="home-wrapper">
  <div class="home-header">
    <div class="home-profile">
      <img src="/images/profile.png" alt="Migyeong Yang">
      <h3 class="home-profile-name">Migyeong Yang</h3>
      <p class="home-profile-title">HCI Researcher</p>
      
      <ul class="home-profile-links">
        <li><i class="fas fa-fw fa-location-dot"></i>Republic of Korea</li>
        <li><i class="fas fa-fw fa-building-columns"></i>NAVER AI Lab</li>
        <li><a href="mailto:migyeong.yang@navercorp.com"><i class="fas fa-fw fa-envelope"></i>migyeong.yang@navercorp.com (curr)</a></li>
        <li><a href="mailto:migyeong@g.skku.edu"><i class="fas fa-fw fa-envelope"></i>migyeong@g.skku.edu (prev)</a></li>
        <li><a href="https://scholar.google.com/citations?user=YOUR_ID"><i class="ai ai-google-scholar ai-fw"></i>Google Scholar</a></li>
        <li><a href="https://orcid.org/0000-0000-0000-0000"><i class="ai ai-orcid ai-fw"></i>ORCID</a></li>
        <li><a href="https://github.com/yangmigyeong"><i class="fab fa-fw fa-github"></i>GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/YOUR_ID"><i class="fab fa-fw fa-linkedin"></i>LinkedIn</a></li>
      </ul>
    </div>
    
    <div class="home-content">
      <p>I am a Research Scientist in Human-Computer Interaction (HCI) Research Group at NAVER AI Lab, NAVER Cloud. I work on applied artificial intelligence and human-centered AI. My research focuses on developing AI systems that are socially responsible, interpretable, and practically useful in real-world applications.</p>
      
      <p>My research interests mainly revolve around HCI, Human-centered AI, and Affective Computing. I am excited about developing accessible AI healthcare systems to address tangible real-world challenges. I am enthusiastic for collaborating with experts across diverse domains. Feel free to reach out with collaboration proposals or for discussions anytime.</p>
      
      <p>For more details about me, please check my <a href="/cv/">CV</a>. ✨</p>
    </div>
  </div>
  
  <div class="home-section">
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
    <p style="font-family: -apple-system, BlinkMacSystemFont, 'Roboto', 'Segoe UI', 'Helvetica Neue', 'Lucida Grande', Arial, sans-serif; color: #494e52;">For a full list, please visit <a href="/publications/" style="color: #52adc8;">Publications</a>.</p>
  </div>
</div>
