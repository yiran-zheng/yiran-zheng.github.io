---
permalink: /
title: "Welcome &#127758;"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .bio-card {
    background: #ffffff;
    border-radius: 4px;
    padding: 48px 52px;
    margin-bottom: 20px;
    border-left: 4px solid #1a1a2e;
    box-shadow: 0 2px 20px rgba(0,0,0,0.06);
    opacity: 0;
    transform: translateY(18px);
    animation: fadeUp 0.7s ease forwards;
  }

  .bio-eyebrow {
    font-family: inherit;
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: #8a7f72;
    margin-bottom: 16px;
  }

  .bio-name {
    font-family: Georgia, serif;
    font-size: 36px;
    font-weight: 600;
    color: #1a1a2e;
    line-height: 1.15;
    margin-bottom: 24px;
  }

  .bio-name span {
    display: block;
    font-size: 15px;
    font-family: inherit;
    font-weight: 300;
    color: #8a7f72;
    letter-spacing: 0.04em;
    margin-top: 6px;
  }

  .bio-divider {
    width: 40px;
    height: 2px;
    background: #1a1a2e;
    margin-bottom: 24px;
  }

  .bio-text {
    font-size: 15.5px;
    font-weight: 300;
    line-height: 1.85;
    color: #3d3d3d;
  }

  .bio-text strong {
    font-weight: bold;
    color: inherit;
  }

  .bio-list {
    list-style: none;
    margin-top: 18px;
    padding-left: 0;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }

  .bio-list li {
    font-size: 15px;
    font-weight: 300;
    line-height: 1.6;
    color: #3d3d3d;
    padding-left: 20px;
    position: relative;
  }

  .bio-list li::before {
    content: "▸";
    position: absolute;
    left: 0;
    color: #1a1a2e;
    font-weight: 500;
    font-size: 12px;
    top: 3px;
  }

  .bio-list li strong {
    font-weight: bold;
    color: inherit;
  }

  .tags-row {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 28px;
  }

  .tag {
    font-size: 12px;
    font-weight: 500;
    letter-spacing: 0.06em;
    color: #1a1a2e;
    background: #f0ede8;
    border-radius: 2px;
    padding: 6px 14px;
  }

  .contact-card {
    background: #1a1a2e;
    border-radius: 4px;
    padding: 28px 52px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 16px;
    box-shadow: 0 2px 20px rgba(0,0,0,0.12);
    opacity: 0;
    transform: translateY(18px);
    animation: fadeUp 0.7s ease 0.2s forwards;
  }

  .contact-label {
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.16em;
    text-transform: uppercase;
    color: #8a8fa8;
    margin-bottom: 4px;
  }

  .contact-links {
    display: flex;
    gap: 28px;
    flex-wrap: wrap;
    align-items: center;
  }

  .contact-item {
    display: flex;
    flex-direction: column;
  }

  .contact-item a {
    font-size: 14px;
    font-weight: 400;
    color: #e8e4dc;
    text-decoration: none;
    letter-spacing: 0.01em;
    transition: color 0.2s ease;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .contact-item a:hover {
    color: #ffffff;
  }

  .contact-divider {
    width: 1px;
    height: 32px;
    background: rgba(255,255,255,0.12);
  }

  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }

  @media (max-width: 600px) {
    .bio-card { padding: 32px 28px; }
    .contact-card { padding: 24px 28px; }
    .bio-name { font-size: 28px; }
    .contact-links { gap: 16px; }
    .contact-divider { display: none; }
  }
</style>

<!-- Bio Card -->
<div class="bio-card">
  <p class="bio-eyebrow">Quantitative Researcher &amp; Data Analyst</p>
  <h1 class="bio-name">
    Yiran Zheng
    <span>郑怡然</span>
  </h1>
  <div class="bio-divider"></div>
  <p class="bio-text">
    I am a <strong>PhD economist</strong> and quantitative researcher passionate about turning complex data into clear, actionable insights. Here is what I bring to the table:
  </p>
  <ul class="bio-list">
    <li><strong>5+ years of experience</strong> in data analysis, <strong>statistical modeling</strong>, and <strong>applied econometrics</strong></li>
    <li>Proficient in <strong>R, Python, Stata, and SQL</strong> with hands-on experience on datasets of <strong>5M+ records</strong></li>
    <li>Skilled in <strong>data cleaning, merging, and pipeline building</strong> for large-scale complex datasets</li>
    <li>Experience translating analytical findings into <strong>clear reports, visualizations, and presentations</strong> for diverse audiences</li>
    <li>Research expertise in <strong>consumer behavior, market segmentation, pricing strategy</strong>, and <strong>causal inference</strong></li>
    <li>Open to opportunities in <strong>data analytics, market research</strong>, and <strong>applied research</strong> across industry and academia</li>
  </ul>
  <div class="tags-row">
    <span class="tag">Industrial Organization</span>
    <span class="tag">Consumer Behavior</span>
    <span class="tag">Econometrics</span>
    <span class="tag">Market Analysis</span>
    <span class="tag">R · Python · Stata · SQL</span>
  </div>
</div>

<!-- Contact Card -->
<div class="contact-card">
  <div>
    <p class="contact-label">Get in touch</p>
  </div>
  <div class="contact-links">
    <div class="contact-item">
      <span class="contact-label">Working</span>
      <a href="mailto:yiranzheng25@gmail.com">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
        yiranzheng25@gmail.com
      </a>
    </div>
    <div class="contact-divider"></div>
    <div class="contact-item">
      <span class="contact-label">Academic</span>
      <a href="mailto:yiranzheng.aca@gmail.com">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
        yiranzheng.aca@gmail.com
      </a>
    </div>
  </div>
</div>
