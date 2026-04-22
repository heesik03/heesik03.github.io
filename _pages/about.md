---
permalink: /
title: "About HeeSik"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 앵커 링크 이동 시 상단 여백 확보 */
  section[id] {
    scroll-margin-top: 80px;
    padding-top: 2rem;
    margin-bottom: 6rem; /* 섹션 간 간격을 대폭 확대 */
  }
  
  /* 첫 번째 섹션(HeeSik 소개)은 예외 처리 */
  #intro {
    padding-top: 0;
    margin-top: 2rem;
    margin-bottom: 5rem;
  }

  /* Tech Stack 스타일 */
  .tech-tag {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 6px;
    padding: 6px 14px;
    font-size: 0.9rem;
    font-weight: 500;
    color: #374151;
    box-shadow: 0 1px 2px rgba(0,0,0,0.05);
    transition: all 0.2s ease;
    display: inline-block;
  }
  
  .tech-tag:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    border-color: #d1d5db;
  }
</style>

<div style="max-width: 768px; margin: 0 auto; letter-spacing: -0.02em;">

  <section id="intro">
    <h2 style="font-size: 1.25rem; color: #6b7280; font-weight: 400; margin-top: 0;">Full Stack Web Developer</h2>
    <p style="margin-top: 1rem; line-height: 1.6; color: #374151; font-size: 1.05rem;">
      항상 성장하는 개발자가 되고 싶습니다.
    </p>
  </section>

  <section id="education">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1rem;">🎓 Education</h3>
    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600; color: #111827;">동양미래대학교 컴퓨터소프트웨어공학과</h4>
      <span style="color: #6b7280; font-size: 0.9rem;">2023.03 ~ 현재</span>
    </div>
  </section>

  <section id="tech-stack">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">🛠️ Tech Stack</h3>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
      
      <div>
        <h4 style="font-weight: 600; margin-bottom: 1rem; color: #4b5563; display: flex; align-items: center; gap: 8px;">
          <span style="width: 4px; height: 16px; background: #3b82f6; border-radius: 2px;"></span>
          Backend
        </h4>
        <div style="display: flex; flex-wrap: wrap; gap: 10px;">
          <span class="tech-tag">Java</span>
          <span class="tech-tag">Spring Boot</span>
          <span class="tech-tag">Node.js</span>
        </div>
      </div>

      <div>
        <h4 style="font-weight: 600; margin-bottom: 1rem; color: #4b5563; display: flex; align-items: center; gap: 8px;">
          <span style="width: 4px; height: 16px; background: #fbbf24; border-radius: 2px;"></span>
          Frontend
        </h4>
        <div style="display: flex; flex-wrap: wrap; gap: 10px;">
          <span class="tech-tag">JavaScript</span>
          <span class="tech-tag">React</span>
          <span class="tech-tag">Bootstrap</span>
        </div>
      </div>

      <div>
        <h4 style="font-weight: 600; margin-bottom: 1rem; color: #4b5563; display: flex; align-items: center; gap: 8px;">
          <span style="width: 4px; height: 16px; background: #10b981; border-radius: 2px;"></span>
          Database
        </h4>
        <div style="display: flex; flex-wrap: wrap; gap: 10px;">
          <span class="tech-tag">MySQL</span>
          <span class="tech-tag">MongoDB</span>
        </div>
      </div>

    </div>
  </section>

  <section id="certifications">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1rem;">📜 Certifications</h3>
    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600; color: #111827;">SQL 개발자 (SQLD)</h4>
      <span style="color: #6b7280; font-size: 0.9rem;">2025.06</span>
    </div>
  </section>

</div>
