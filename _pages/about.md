---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.home-container {
  max-width: 1100px;
  margin: 0 auto;
}

.home-header {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 60px;
  margin-bottom: 40px;
}

.home-profile {
  flex-shrink: 0;
  width: 280px;
  text-align: center;
}

.home-profile img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
}

.home-profile-name {
  font-size: 1.5em;
  font-weight: 700;
  margin-bottom: 5px;
}

.home-profile-title {
  font-size: 1em;
  color: #666;
  margin-bottom: 20px;
}

.home-profile-info {
  text-align: left;
  font-size: 0.95em;
  line-height: 2.2;
}

.home-profile-info a {
  color: #333;
  text-decoration: none;
}

.home-profile-info a:hover {
  color: #0066cc;
}

.home-profile-info i {
  width: 20px;
  margin-right: 8px;
  color: #666;
}

.home-content {
  flex: 1;
}

.home-content p {
  font-size: 1em;
  line-height: 1.8;
  color: #333;
  margin-bottom: 15px;
}

.section-title {
  font-size: 1.6em;
  font-weight: 400;
  margin-top: 35px;
  margin-bottom: 20px;
}

.news-table {
  width: 100%;
  border-collapse: collapse;
}

.news-table td {
  padding: 10px 0;
  vertical-align: top;
  border: none;
}

.news-table td:first-child {
  font-weight: 600;
  width: 120px;
  color: #333;
}

.news-table td:last-child {
  color: #444;
}

@media (max-width: 768px) {
  .home-header {
    flex-direction: column;
    gap: 30px;
  }
  
  .home-profile {
    width: 100%;
  }
}
</style>

<div class="home-container">
  <div class="home-header">
    <div class="home-profile">
      <img src="/images/profile.png" alt="Migyeong Yang">
      <div class="home-profile-name">Migyeong Yang</div>
      <div class="home-profile-title">HCI Researcher, PhD</div>
      
      <div class="home-profile-info">
        <div><i class="fas fa-location-dot"></i>Republic of Korea</div>
        <div><i class="fas fa-building-columns"></i>NAVER AI Lab</div>
        <div><a href="mailto:migyeong.yang@navercorp.com"><i class="fas fa-envelope"></i>migyeong.yang@navercorp.com</a></div>
        <div><a href="https://scholar.google.com/citations?user=YOUR_ID"><i class="ai ai-google-scholar"></i>Google Scholar</a></div>
        <div><a href="https://orcid.org/0000-0000-0000-0000"><i class="ai ai-orcid"></i>ORCID</a></div>
        <div><a href="https://github.com/yangmigyeong"><i class="fab fa-github"></i>GitHub</a></div>
        <div><a href="https://www.linkedin.com/in/YOUR_ID"><i class="fab fa-linkedin"></i>LinkedIn</a></div>
      </div>
    </div>
    
    <div class="home-content">
      <p>Hello!😊 I am a Research Scientist in Human-Computer Interaction (HCI) Research Group at NAVER AI Lab, NAVER Cloud. I received my Ph.D. in Applied Artificial Intelligence from Sungkyunkwan University (SKKU) in Seoul, Republic of Korea.</p>
      
      <p>My research interests mainly revolve around HCI, Human-centered AI, and Affective Computing. I am excited about developing accessible AI healthcare systems to address tangible real-world challenges. I am enthusiastic for collaborating with experts across diverse domains. Feel free to reach out with collaboration proposals or for discussions anytime.</p>
      
      <p>For more details about me, please check my <a href="/cv/">CV</a>.✨</p>
      
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
      <p>For a full list, please visit <a href="/publications/">Publications</a>.</p>
    </div>
  </div>
</div>
