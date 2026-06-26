---
layout: default
title: Home — Muhammad Bilal Saad
---

<section class="hero">
  <div class="hero-container">
    <div class="hero-image">
      <img src="/assets/images/bilal.jpg" alt="Muhammad Bilal Saad" class="profile-pic">
    </div>
    <div class="hero-text">
      <span class="badge">🟢 Available for Work</span>
      <h1>Muhammad <span class="highlight">Bilal Saad.</span></h1>
      <p class="subtitle">BS Computer Engineering | Semester 2</p>
      <p class="university">🎓 UET Faisalabad | Reg: 2025-BSCPE-109</p>
      <p class="bio">Web Developer & University Student from Pakistan. I build clean websites and share my real journey through writing.</p>
      <div class="hero-buttons">
        <a href="/about" class="btn-primary">About Me →</a>
        <a href="/contact" class="btn-secondary">Contact</a>
      </div>
    </div>
  </div>
</section>

<section class="journey-section" id="journey">
  <div class="journey-header" onclick="toggleJourney()">
    <span class="journey-icon">🗺️</span>
    <h2>My Journey</h2>
    <span class="arrow" id="journey-arrow">▼</span>
  </div>
  <div class="journey-content" id="journey-content">
    <h3>My Journey as a Computer Engineering Student</h3>
    <p>Choosing Computer Engineering has been one of the most important decisions of my academic life. I am currently studying Computer Engineering at UET Faisalabad Campus, Pakistan, where every semester brings new challenges and valuable learning experiences.</p>
    <p>During my studies, I have explored different subjects, including programming, digital logic design, mathematics, electronics, and computer systems.</p>
    <p>University life has also helped me grow as a person. Living away from home, managing my own schedule, completing assignments on time, and working on group projects have taught me responsibility and discipline.</p>
    <p>One of the things I enjoy most about Computer Engineering is that it combines both hardware and software. Although my journey is still continuing, I believe every lecture, project, and practical experience is helping me become a better engineer.</p>
  </div>
</section>

<script>
function toggleJourney() {
  const content = document.getElementById('journey-content');
  const arrow = document.getElementById('journey-arrow');
  content.classList.toggle('open');
  arrow.textContent = content.classList.contains('open') ? '▲' : '▼';
}
</script>
