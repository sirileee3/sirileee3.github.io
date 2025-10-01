---
layout: page
permalink: /people/
title: people
description: members of the lab or group
nav: true
nav_order: 4
---

<!-- ===== PI block: put this ABOVE the students grid ===== -->
<section class="pi-hero" id="pi">
  <div class="pi-left">
    <img src="/assets/img/prof_pic.jpg" class="pi-photo">
    <div class="pi-name">Yuzhe Yang</div>
    <div class="pi-title">Assistant Professor</div>
  </div>
  <div class="pi-right">
    <p>
      Professor Yang is an Assistant Professor of <a href="https://compmed.ucla.edu/">Computational Medicine</a> and
      <a href="https://www.cs.ucla.edu/">Computer Science</a> at UCLA. Previously, he received his Ph.D. in Computer Science at MIT, advised by
      <a href="https://people.csail.mit.edu/dina/">Dina&nbsp;Katabi</a>. Before MIT, he received his B.S. from
      <a href="https://english.pku.edu.cn/">Peking University</a>.
    </p>
    <p>
      Professor Yang develops machine learning methods to solve important problems in healthcare and medicine. Please see
      <a href="https://web.cs.ucla.edu/~yuzhe/">Professor Yang's website</a> for details. His work has been recognized by Ten Notable Advances in 2022 by Nature Medicine, Takeda PhD Fellowship, Baidu PhD Fellowship, MathWorks PhD Fellowship, Rising Stars in AI (Yunfan Award), Rising Stars in Data Science, AMIA Doctoral Dissertation Award Honorable Mention, and Forbes 30 Under 30.
    </p>
    <p>
      <a href="https://scholar.google.com/citations?user=0_bSbIoAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a> /
      <a href="https://github.com/YyzHarry" target="_blank" rel="noopener">GitHub</a> /
      <a href="mailto:yuzhey@ucla.edu">Email</a>
    </p>
  </div>
</section>

<!-- PhD students -->
<h2 class="people-section-title" id="phd">PhD Students</h2>
<div class="people-grid">
  <div class="profile-card">
    <img src="/assets/img/lab_members/spiderman.jpg" class="profile-img" />
    <div class="profile-name">Zitao. Shuai</div>
    <div class="profile-role">CS PhD Student</div>
  </div>
  <div class="profile-card">
    <img src="/assets/img/lab_members/spiderman.jpg" class="profile-img" />
    <div class="profile-name">Zongzhe. Xu</div>
    <div class="profile-role">CS PhD Student</div>
  </div>
  <div class="profile-card">
    <img src="/assets/img/lab_members/spiderman.jpg" class="profile-img" />
    <div class="profile-name">Sirui. Li</div>
    <div class="profile-role">Biomath PhD Student</div>
  </div>
  <!-- Add more members -->
</div>

<!-- ===== Interns ===== -->
<h2 class="people-section-title" id="interns">Research Interns</h2>
<div class="people-grid">
  <div class="profile-card">
    <img src="/assets/img/lab_members/spiderman.jpg" class="profile-img" />
    <div class="profile-name">Shuhan. Xiao</div>
    <div class="profile-role">ECE Master Student</div>
  </div>
  <div class="profile-card">
    <img src="/assets/img/lab_members/spiderman.jpg" class="profile-img" />
    <div class="profile-name">Shuhan. Xiao</div>
    <div class="profile-role">ECE Master Student</div>
  </div>
  <div class="profile-card">
    <img src="/assets/img/lab_members/spiderman.jpg" class="profile-img" />
    <div class="profile-name">Shuhan. Xiao</div>
    <div class="profile-role">ECE Master Student</div>
  </div>
  <!-- Add more members -->
</div>

<style>
/* ===== PI block ===== */
.pi-hero{
  display:grid;
  grid-template-columns: 220px 1fr;    
  gap:24px;
  align-items:start;
  margin-top: 0.5rem;
  padding-bottom: 1.25rem;
  border-bottom: 1px solid #eaeaea;
}
.pi-left{
  display:flex;
  flex-direction:column;
  align-items:center;                  
  text-align:center;
}
.pi-photo{
  width:180px; height:180px;           
  object-fit:cover;
  border-radius:12px;
  border:1px solid #ddd;
  background:#f7f7f7;
}
.pi-name{ margin-top:.5rem; font-weight:700; font-size:1.05rem; }
.pi-title{ color:#666; font-size:.93rem; }

@media (max-width: 800px){
  .pi-hero{ grid-template-columns: 1fr; }
  .pi-photo{ width:140px; height:140px; }
}

/* ===== subtitle for phd/intern ===== */
.people-section-title{
  margin: 1.5rem 0 .6rem 0;
  font-size: 1.25rem;
  font-weight: 500;
  line-height: 1.3;
  border-left: 4px solid #111;
  padding-left: .6rem;
}

/* ===== student grid =====*/
.people-grid{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 160px)); /* fix width */
  gap:24px;
  justify-content:center;               /* centralize each row */
  margin-top: 1rem;
}
.profile-card{ width:160px; text-align:center; }
.profile-img{ width:160px; height:160px; object-fit:cover; border-radius:16px; }
.profile-name{ margin-top:.6rem; font-weight:600; }
.profile-role{ font-size:.9rem; color:#666; }

/* 极窄屏：卡片缩小一点，仍保持行内居中 */
@media (max-width: 420px){
  .people-grid{
    grid-template-columns: repeat(auto-fit, minmax(140px, 140px));
    gap:18px;
  }
  .profile-card, .profile-img{ width:140px; }
  .profile-img{ height:140px; }
}
</style>