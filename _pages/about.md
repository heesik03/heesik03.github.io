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
    padding-top: 1rem;
    margin-bottom: 3rem; 
  }
  
  /* 첫 번째 섹션(HeeSik 소개)은 예외 처리 */
  #intro {
    padding-top: 0;
    margin-top: 1.5rem;
    margin-bottom: 2.5rem;
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

  /* 다크모드 대응 */
  [data-theme="dark"] .tech-tag {
    background: #1f2937;
    border-color: #374151;
    color: #e5e7eb;
    box-shadow: 0 1px 2px rgba(0,0,0,0.3);
  }

  [data-theme="dark"] .tech-tag:hover {
    border-color: #4b5563;
    background: #374151;
  }

  [data-theme="dark"] section[id] {
    border-color: #374151 !important;
  }

  [data-theme="dark"] h3, 
  [data-theme="dark"] h4 {
    color: #f3f4f6 !important;
    border-color: #374151 !important;
  }

  [data-theme="dark"] p,
  [data-theme="dark"] span {
    color: #9ca3af !important;
  }
</style>

<div style="max-width: 768px; margin: 0 auto; letter-spacing: -0.02em;">

  <section id="intro">
    <h2 style="font-size: 1.25rem; font-weight: 400; margin-top: 0; color: #6b7280;" class="intro-subtitle">Full Stack Web Developer</h2>
    <p style="margin-top: 1rem; line-height: 1.6; font-size: 1.05rem; color: #374151;" class="intro-text">
      항상 성장하고 싶은 개발자, HeeSik입니다! 풀스택 웹 개발을 지향하며, 백엔드와 프론트엔드의 연결 구조를 이해하고 사용자 경험까지 고려한 서비스를 만드는 걸 좋아합니다. 새로운 기술을 빠르게 학습하고 실제 프로젝트에 적용하고 있습니다.
    </p>
  </section>

  <section id="education">
    <h3 style="font-size:1.5rem;font-weight:700;border-bottom:2px solid #f3f4f6;padding-bottom:0.5rem;margin-bottom:1.5rem;">
      🎓 학력
    </h3>

    <div style="display:flex;justify-content:space-between;align-items:flex-start;gap:1rem;flex-wrap:wrap;margin-bottom:1.25rem;">
      <h4 style="margin:0;font-size:1rem;font-weight:600;line-height:1.5;flex:1;min-width:220px;">
        광운전자공업고등학교 모바일소프트웨어과
        <span style="font-weight:400;color:#6b7280;">(현 광운인공지능고등학교 인공지능소프트웨어과)</span>
      </h4>
      <span style="font-size:0.85rem;color:#6b7280;white-space:nowrap;">2019.03 ~ 2022.02</span>
    </div>

    <div style="display:flex;justify-content:space-between;align-items:flex-start;gap:1rem;flex-wrap:wrap;">
      <h4 style="margin:0;font-size:1rem;font-weight:600;line-height:1.5;flex:1;min-width:220px;">
        동양미래대학교 컴퓨터소프트웨어공학과
      </h4>
      <span style="font-size:0.85rem;color:#6b7280;white-space:nowrap;">2022.03 ~ </span>
    </div>
  </section>

  <section id="tech-stack">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">🛠️ 기술 스택</h3>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
      
      <div>
        <h4 style="font-weight: 600; margin-bottom: 1rem; display: flex; align-items: center; gap: 8px;">
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
        <h4 style="font-weight: 600; margin-bottom: 1rem; display: flex; align-items: center; gap: 8px;">
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
        <h4 style="font-weight: 600; margin-bottom: 1rem; display: flex; align-items: center; gap: 8px;">
          <span style="width: 4px; height: 16px; background: #10b981; border-radius: 2px;"></span>
          Database
        </h4>
        <div style="display: flex; flex-wrap: wrap; gap: 10px;">
          <span class="tech-tag">MySQL</span>
          <span class="tech-tag">MongoDB</span>
        </div>
      </div>

      <div>
        <h4 style="font-weight: 600; margin-bottom: 1rem; display: flex; align-items: center; gap: 8px;">
          <span style="width: 4px; height: 16px; background: #8b5cf6; border-radius: 2px;"></span>
          DevOps & Cloud
        </h4>
        <div style="display: flex; flex-wrap: wrap; gap: 10px;">
          <span class="tech-tag">AWS</span>
          <span class="tech-tag">Docker</span>
          <span class="tech-tag">GitHub Actions</span>
        </div>
      </div>

    </div>
  </section>

  <section id="projects">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1rem;">💻 프로젝트</h3>
    
    <div style="margin-bottom: 2.5rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">Learn-Time</h4>
      <a href="https://github.com/Dongyang-LearnTime" target="_blank" style="font-size: 0.9rem; color: #3b82f6; text-decoration: none; display: inline-block; margin-bottom: 0.5rem;">https://github.com/Dongyang-LearnTime</a>
      <p style="margin: 0 0 0.5rem 0; font-size: 0.95rem; line-height: 1.5;">AI 기반 공부 및 루틴 관리 웹사이트입니다. AI 기반 공부 진도 생성과 운동 관리 기능을 게이미피케이션과 결합하여 사용자의 지속적인 학습 습관 형성을 지원합니다.</p>
      <span style="font-size: 0.85rem; color: #6b7280;">2026.03 ~ | Spring Boot, React TypeScript, MySQL, AWS, Docker, GitHub Actions</span>
    </div>

    <div style="margin-bottom: 2.5rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">슬기틔움</h4>
      <a href="https://github.com/heesik03/Seulgi-Tuium" target="_blank" style="font-size: 0.9rem; color: #3b82f6; text-decoration: none; display: inline-block; margin-bottom: 0.5rem;">https://github.com/heesik03/Seulgi-Tuium</a>
      <p style="margin: 0 0 0.5rem 0; font-size: 0.95rem; line-height: 1.5;">어려운 표현을 AI가 쉽게 설명해 주는 문해력 향상 웹사이트입니다. Gemini API를 활용하여 어려운 단어와 문장을 쉬운 표현으로 변환하고, 어휘 학습 콘텐츠를 제공하여 문해력 저하 문제 해결에 이바지합니다.</p>
      <span style="font-size: 0.85rem; color: #6b7280;">2026.05 ~ 2026.06 | Spring Boot, React TypeScript, MySQL, Redis</span>
    </div>

    <div style="margin-bottom: 2.5rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">Visit Japan</h4>
      <a href="https://github.com/heesik03/team2-BackendProject" target="_blank" style="font-size: 0.9rem; color: #3b82f6; text-decoration: none; display: inline-block; margin-bottom: 0.5rem;">https://github.com/heesik03/team2-BackendProject</a>
      <p style="margin: 0 0 0.5rem 0; font-size: 0.95rem; line-height: 1.5;">일본 여행 정보 제공 및 일정 관리 웹사이트입니다. Jsoup 기반 크롤링으로 여행 정보를 수집하고, Google Maps를 활용해 주요 관광지 경로를 시각화하며, 사용자 맞춤형 여행 일정 관리 기능을 제공합니다.</p>
      <span style="font-size: 0.85rem; color: #6b7280;">2025.10 ~ 2025.12 | Java Servlet, JSP, MongoDB</span>
    </div>
  </section>

  <section id="activities">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1rem;">🏃 활동</h3>
    
    <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 1rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">전공동아리 DASOM 활동</h4>
      <span style="font-size: 0.9rem; color: #6b7280;">2025.09 ~ </span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">연합동아리 UMC 10th Spring Boot 챌린저 활동</h4>
      <span style="font-size: 0.9rem; color: #6b7280;">2026.03 ~ </span>
    </div>
  </section>

  <section id="certifications">
    <h3 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid #f3f4f6; padding-bottom: 0.5rem; margin-bottom: 1rem;">📜 자격증</h3>

    <div style="display: flex; justify-content: space-between; align-items: baseline;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">컴퓨터활용능력 2급</h4>
      <span style="font-size: 0.9rem; color: #6b7280;">2019.07.12</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 1rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">프로그래밍기능사(구 정보처리기능사)</h4>
      <span style="font-size: 0.9rem; color: #6b7280;">2021.07.16</span>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 1rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">SQL 개발자 (SQLD)</h4>
      <span style="font-size: 0.9rem; color: #6b7280;">2025.06.27</span>
    </div>
    
    <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 1rem;">
      <h4 style="margin: 0; font-size: 1.1rem; font-weight: 600;">정보처리산업기사</h4>
      <span style="font-size: 0.9rem; color: #6b7280;">2026.06.12</span>
    </div>

  </section>

</div>
