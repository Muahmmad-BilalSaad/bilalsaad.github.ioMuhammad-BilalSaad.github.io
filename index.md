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
    <p class="journey-intro">My Computer Engineering journey at UET Faisalabad — semester by semester!</p>
    <div class="semester-grid">

      <!-- SEMESTER 1 -->
      <div class="semester-box" onclick="toggleSemester('sem1', event)">
        <div class="semester-box-header">
          <span class="sem-icon">📚</span>
          <div>
            <h3>Semester 1</h3>
            <p>2025 — Foundation</p>
          </div>
          <span class="sem-arrow" id="sem1-arrow">▼</span>
        </div>
        <div class="semester-posts" id="sem1">
          <a href="/2025/09/01/my-journey/" class="post-link">
            <span>📝</span> My Journey as a CE Student
          </a>
          <a href="/2025/09/15/why-i-chose-computer-engineering/" class="post-link">
            <span>💻</span> Why I Chose Computer Engineering
          </a>
          <a href="/2025/10/01/hostel-life/" class="post-link">
            <span>🏫</span> Hostel Life: A New Experience
          </a>
          <a href="/2025/10/15/benefits-of-hostel-life/" class="post-link">
            <span>✅</span> Benefits of Hostel Life
          </a>
          <a href="/2025/11/01/drawbacks-of-hostel-life/" class="post-link">
            <span>⚠️</span> Drawbacks of Hostel Life
          </a>
          <a href="/2025/11/15/programming-fundamentals/" class="post-link">
            <span>🐍</span> Programming Fundamentals & ML
          </a>
          <a href="/2025/12/01/exam-week/" class="post-link">
            <span>📖</span> Exam Week Experience
          </a>
        </div>
      </div>

      <!-- SEMESTER 2 -->
      <div class="semester-box" onclick="toggleSemester('sem2', event)">
        <div class="semester-box-header">
          <span class="sem-icon">🎓</span>
          <div>
            <h3>Semester 2</h3>
            <p>2026 — Ongoing</p>
          </div>
          <span class="sem-arrow" id="sem2-arrow">▼</span>
        </div>
        <div class="semester-posts" id="sem2">
          <a href="/2026/02/01/first-week/" class="post-link">
            <span>🏫</span> My First Days at University
          </a>
          <a href="#" class="post-link coming-soon">
            <span>⏳</span> More posts coming soon...
          </a>
        </div>
      </div>

    </div>
  </div>
</section>

<script>
function toggleJourney() {
  const content = document.getElementById('journey-content');
  const arrow = document.getElementById('journey-arrow');
  content.classList.toggle('open');
  arrow.textContent = content.classList.contains('open') ? '▲' : '▼';
}

function toggleSemester(id, event) {
  event.stopPropagation();
  const posts = document.getElementById(id);
  const arrow = document.getElementById(id + '-arrow');
  posts.classList.toggle('open');
  arrow.textContent = posts.classList.contains('open') ? '▲' : '▼';
}
</script>
