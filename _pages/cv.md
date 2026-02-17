---
layout: archive
title: "CV &#127796;"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-section {
    margin-bottom: 32px;
  }

  .cv-section h2 {
    font-size: 18px;
    font-weight: bold;
    color: #494e52;
    margin-bottom: 6px;
    padding-bottom: 6px;
    border-bottom: 2px solid #494e52;
  }

  .download-row {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    margin-bottom: 32px;
  }

  .download-btn {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    font-size: 13.5px;
    font-weight: 500;
    color: #494e52;
    background: #f2f3f3;
    border: 1px solid #ddd;
    border-radius: 2px;
    padding: 8px 16px;
    text-decoration: none;
    transition: all 0.2s;
  }

  .download-btn:hover {
    background: #494e52;
    color: #fff;
    border-color: #494e52;
    text-decoration: none;
  }

  /* ── CARDS ── */
  .cv-card {
    border-left: 4px solid #494e52;
    background: #fff;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    border-radius: 2px;
    padding: 18px 24px;
    margin-top: 14px;
  }

  .cv-card-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 6px;
    margin-bottom: 4px;
  }

  .cv-card-title {
    font-size: 15.5px;
    font-weight: bold;
    color: #494e52;
  }

  .cv-card-date {
    font-size: 13px;
    color: #888;
    white-space: nowrap;
  }

  .cv-card-sub {
    font-size: 13.5px;
    color: #888;
    font-style: italic;
    margin-bottom: 8px;
  }

  .cv-card-detail {
    font-size: 14px;
    color: #666;
    margin-bottom: 4px;
  }

  .cv-card-divider {
    border: none;
    border-top: 1px solid #f2f3f3;
    margin: 10px 0;
  }

  .cv-list {
    list-style: none;
    padding-left: 0;
    margin-top: 8px;
  }

  .cv-list li {
    font-size: 14px;
    color: #666;
    line-height: 1.7;
    padding-left: 18px;
    position: relative;
    margin-bottom: 6px;
  }

  .cv-list li::before {
    content: "▸";
    position: absolute;
    left: 0;
    top: 2px;
    font-size: 11px;
    color: #494e52;
  }

  .cv-responsibilities {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #999;
    margin: 10px 0 6px;
  }

  /* ── SKILLS ── */
  .skills-row {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 14px;
  }

  .skill-tag {
    font-size: 12.5px;
    color: #494e52;
    background: #f2f3f3;
    border: 1px solid #ddd;
    border-radius: 2px;
    padding: 5px 12px;
  }

  /* ── REFERENCES ── */
  .ref-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 14px;
    margin-top: 14px;
  }

  .ref-card {
    background: #f9f9f9;
    border-radius: 2px;
    border: 1px solid #eee;
    padding: 16px 18px;
  }

  .ref-name {
    font-size: 15px;
    font-weight: bold;
    color: #494e52;
    margin-bottom: 4px;
  }

  .ref-role {
    font-size: 13px;
    color: #666;
    font-style: italic;
    line-height: 1.5;
    margin-bottom: 6px;
  }

  .ref-email {
    font-size: 13px;
    color: #52adc8;
    text-decoration: none;
    word-break: break-all;
  }

  .ref-email:hover {
    text-decoration: underline;
  }
</style>

<!-- Download Buttons -->
<div class="download-row">
  <a class="download-btn" href="../files/Yiran Zheng-CV.pdf" target="_blank" rel="noopener noreferrer">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
    Download CV
  </a>
</div>

<!-- Education -->
<div class="cv-section">
  <h2>Education</h2>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">Texas Tech University</span>
      <span class="cv-card-date">August 2025</span>
    </div>
    <div class="cv-card-sub">Ph.D. in Economics</div>
    <div class="cv-card-detail">Focus: Industrial Organization, Quantitative Methods</div>
  </div>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">George Washington University</span>
      <span class="cv-card-date">May 2020</span>
    </div>
    <div class="cv-card-sub">M.S. in Tourism Administration</div>
  </div>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">University of Liverpool</span>
      <span class="cv-card-date">July 2018</span>
    </div>
    <div class="cv-card-sub">B.S. in Economics</div>
  </div>
</div>

<!-- Teaching Experience -->
<div class="cv-section">
  <h2>Teaching Experience</h2>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">Texas Tech University</span>
      <span class="cv-card-date">August 2023 – August 2025</span>
    </div>
    <div class="cv-card-sub">Instructor of Record</div>
    <div class="cv-card-detail">Principles of Economics: Fall 2023 · Spring 2024 · Summer 2024 · Fall 2024 · Spring 2025</div>
    <hr class="cv-card-divider">
    <p class="cv-responsibilities">Responsibilities</p>
    <ul class="cv-list">
      <li>Taught classes ranging in size from 12 to 106 students.</li>
      <li>Prepared and presented engaging lectures that effectively deliver course content.</li>
      <li>Designed exams, quizzes, and homework assignments that evaluate student understanding.</li>
      <li>Completed course-related administrative tasks, including maintaining attendance and grade records, submitting grades by required deadlines, and adhering to institutional policies.</li>
      <li>Directed teaching assistants, providing guidance and support to ensure effective delivery of course materials and a seamless learning experience for students.</li>
    </ul>
  </div>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">Texas Tech University</span>
      <span class="cv-card-date">August 2020 – May 2023</span>
    </div>
    <div class="cv-card-sub">Teaching Assistant</div>
    <div class="cv-card-detail">
      Undergraduate Principles of Microeconomics (Fall 2020) · Principles of Economics (Spring 2021) · Managerial Economics (Fall 2021, Fall 2022) · Monetary Theory (Spring 2022) · Game Theory (Spring 2023)
    </div>
    <hr class="cv-card-divider">
    <p class="cv-responsibilities">Responsibilities</p>
    <ul class="cv-list">
      <li>Graded assignments, exams, and quizzes to assess and provide feedback to students.</li>
      <li>Set up regular tutoring sessions and office hours to support students outside the class.</li>
      <li>Organized and administered examinations, including preparation, proctoring, and maintaining academic integrity.</li>
    </ul>
  </div>
</div>

<!-- Research Experience -->
<div class="cv-section">
  <h2>Research Experience</h2>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">Texas Tech University</span>
    </div>
    <div class="cv-card-sub">Ph.D. Researcher</div>
    <ul class="cv-list">
      <li>Developed structural models using Stata and R on large-scale datasets to test consumer decision making and provide strategic business implications.</li>
      <li>Investigated the impact of rental stabilization policy using quasi-experimental methods on the housing market.</li>
      <li>Presented work at regional and national scientific conferences.</li>
    </ul>
  </div>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">George Washington University</span>
    </div>
    <div class="cv-card-sub">Master Researcher</div>
    <ul class="cv-list">
      <li>Interviewed business managers to conduct research projects and address real-world business challenges in the hospitality industry.</li>
      <li>Developed hypotheses and designed research methodologies tailored to industry-specific problems.</li>
      <li>Utilized advanced analytical tools and statistical techniques, including SPSS and R, to process and analyze data efficiently.</li>
    </ul>
  </div>
</div>

<!-- Certifications -->
<div class="cv-section">
  <h2>Certifications</h2>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title">Graduate Certificate in Digital Marketing and Communication</span>
      <span class="cv-card-date">May 2020</span>
    </div>
    <div class="cv-card-sub">George Washington University</div>
  </div>

  <div class="cv-card">
    <div class="cv-card-header">
      <span class="cv-card-title"><a href="../files/*Coursera P6D0XVXCGQGN.pdf" target="_blank" rel="noopener noreferrer" style="color:#494e52; text-decoration:none;">Google Data Analytics</a></span>
      <span class="cv-card-date">September 2024</span>
    </div>
    <div class="cv-card-sub">Google / Coursera</div>
  </div>
</div>

<!-- Skills -->
<div class="cv-section">
  <h2>Skills</h2>
  <div class="skills-row">
    <span class="skill-tag">R</span>
    <span class="skill-tag">Stata</span>
    <span class="skill-tag">Python</span>
    <span class="skill-tag">SQL</span>
    <span class="skill-tag">Tableau</span>
    <span class="skill-tag">SPSS</span>
    <span class="skill-tag">EViews</span>
    <span class="skill-tag">LaTeX</span>
    <span class="skill-tag">MS Office</span>
  </div>
</div>

<!-- Honors -->
<div class="cv-section">
  <h2>Honors &amp; Scholarships</h2>

  <div class="cv-card">
    <ul class="cv-list">
      <li>SEA Graduate Student Award, 2024</li>
      <li>Dr. Rashid B. Al-Hmoud Scholarship in Economics, 2024</li>
      <li>Teaching Assistantship, 2020–2025</li>
    </ul>
  </div>
</div>

<!-- References -->
<div class="cv-section">
  <h2>References</h2>

  <div class="ref-grid">
    <div class="ref-card">
      <div class="ref-name">Michael Noel</div>
      <div class="ref-role">Dissertation Chair<br>Professor in Economics<br>Texas Tech University</div>
      <a class="ref-email" href="mailto:michael.noel@ttu.edu">michael.noel@ttu.edu</a>
    </div>
    <div class="ref-card">
      <div class="ref-name">Kaj Gittings</div>
      <div class="ref-role">Associate Professor in Economics<br>Texas Tech University</div>
      <a class="ref-email" href="mailto:kaj.gittings@ttu.edu">kaj.gittings@ttu.edu</a>
    </div>
    <div class="ref-card">
      <div class="ref-name">Sie Won Kim</div>
      <div class="ref-role">Assistant Professor in Economics<br>Texas Tech University</div>
      <a class="ref-email" href="mailto:siewon.kim@ttu.edu">siewon.kim@ttu.edu</a>
    </div>
    <div class="ref-card">
      <div class="ref-name">James Kemper</div>
      <div class="ref-role">Lecturer / GPTI Coordinator<br>Texas Tech University</div>
      <a class="ref-email" href="mailto:james.kemper@ttu.edu">james.kemper@ttu.edu</a>
    </div>
  </div>
</div>
