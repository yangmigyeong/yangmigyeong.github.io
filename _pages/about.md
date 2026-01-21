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
  padding: 20px;
}

.home-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 50px;
  margin-bottom: 40px;
}

.home-intro {
  flex: 1;
}

.home-name {
  font-size: 2.5em;
  margin-bottom: 5px;
  font-weight: 400;
  margin-top: 0;
}

.home-name .first-name {
  font-weight: 700;
}

.home-title {
  font-size: 1.1em;
  color: #666;
  margin-bottom: 20px;
}

.home-bio {
  font-size: 1em;
  line-height: 1.7;
  color: #333;
}

.home-bio p {
  margin-bottom: 15px;
}

.home-photo {
  text-align: center;
  flex-shrink: 0;
}

.home-photo img {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  object-fit: cover;
}

.home-affiliation {
  margin-top: 15px;
  font-family: monospace;
  font-size: 0.9em;
  line-height: 1.6;
  text-align: center;
}

.home-links {
  margin-top: 25px;
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  font-size: 0.95em;
}

.home-links a {
  color: #333;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 6px;
}

.home-links a:hover {
  color: #0066cc;
}

.section-title {
  font-size: 1.8em;
  font-weight: 400;
  margin-top: 40px;
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
  width: 130px;
  color: #333;
}

.news-table td:last-child {
  color: #444;
}

@media (max-width: 768px) {
  .home-header {
    flex-direction: column;
  }
  
  .home-photo {
    order: -1;
    margin-bottom: 20px;
  }
  
  .home-photo img {
    width: 180px;
    height: 180px;
  }
  
  .home-links {
    flex-direction: column;
    gap: 10px;
  }
}
</style>

<div class="home-container">
  <div class="home-header">
    <div class="home-intro">
      <h1 class="home-name"><span class="first-name">Migyeong</span> Yang</h1>
      <p class="home-title">Research Scientist</p>
      
      <div class="home-bio">
        <p>Hello!😊 I am a Research Scientist in Human-Computer Interaction (HCI) Research Group at NAVER AI Lab, NAVER Cloud. I received my Ph.D. in Applied Artificial Intelligence from Sungkyunkwan University (SKKU) in Seoul, Republic of Korea.</p>
        
        <p>My research interests mainly revolve around HCI, Human-centered AI, and Affective Computing. I am excited about developing accessible AI healthcare systems to address tangible real-world challenges. I am enthusiastic for collaborating with experts across diverse domains. Feel free to reach out with collaboration proposals or for discussions anytime.</p>
        
        <p>For more details about me, please check my <a href="/cv/">CV</a>.✨</p>
      </div>
      
      <div class="home-links">
        <a href="mailto:migyeong.yang@navercorp.com"><i class="fas fa-envelope"></i> migyeong.yang@navercorp.com</a>
        <a href="https://scholar.google.com/citations?user=YOUR_ID"><i class="ai ai-google-scholar"></i> Google Scholar</a>
        <a href="https://orcid.org/0000-0000-0000-0000"><i class="ai ai-orcid"></i> ORCID</a>
        <a href="https://github.com/yangmigyeong"><i class="fab fa-github"></i> GitHub</a>
        <a href="https://www.linkedin.com/in/YOUR_ID"><i class="fab fa-linkedin"></i> LinkedIn</a>
      </div>
    </div>
    
    <div class="home-photo">
      <img src="/images/profile.png" alt="Migyeong Yang">
      <div class="home-affiliation">
        <strong>NAVER AI Lab</strong><br>
        Republic of Korea
      </div>
    </div>
  </div>

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
