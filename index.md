<!-- 1. 상단 방문자 카운터 영역 (동영상 박스와 상단 헤더 사이) -->
<div style="display: flex; justify-content: center; align-items: center; margin: 10px 0 25px 0;">
  <img src="https://komarev.com/ghpvc/?username=smart-civil-maintain&label=Visitor&color=0366d6&style=flat" 
       alt="Visitor Count" 
       style="height: 32px; box-shadow: 0 3px 8px rgba(0,0,0,0.12); border-radius: 4px;" />
</div>

<!-- 2. 동영상 배너 영역 -->
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; overflow: hidden; border-radius: 12px; margin-bottom: 35px; box-shadow: 0 6px 20px rgba(0,0,0,0.15); background-color: #0b253a;">
  
  <video autoplay loop muted playsinline preload="auto"
         style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: 1;">
    <source src="{{ '/assets/videos/maintain_mv.mp4' | relative_url }}" type="video/mp4">
    <source src="./assets/videos/maintain_mv.mp4" type="video/mp4">
    동영상을 지원하지 않는 브라우저입니다.
  </video>

  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(135deg, rgba(14, 65, 102, 0.15), rgba(16, 107, 85, 0.15)); z-index: 2;"></div>

  <div style="position: relative; z-index: 3; display: flex; flex-direction: column; align-items: center; justify-content: flex-end; height: 100%; text-align: center; color: #ffffff; padding: 0 20px 40px 20px;">
    <h1 style="font-size: 32px; font-weight: 700; margin: 0 0 12px 0; color: #ffffff; text-shadow: 0 2px 8px rgba(0,0,0,0.9); border-bottom: none;">
      AI 토목 구조물 유지관리
    </h1>
    <p style="font-size: 16px; margin: 0; color: #f0f6fc; font-weight: 500; text-shadow: 0 2px 6px rgba(0,0,0,0.9);">
      데이터 기반 구조물 유지관리 및 설계 자동화 연구 아카이브
    </p>
    <p style="font-size: 13px; margin: 8px 0 0 0; color: #c9d1d9; font-weight: 300; letter-spacing: 0.5px; text-shadow: 0 2px 5px rgba(0,0,0,0.9);">
      Civil Structural Engineering & Automated Maintenance Systems
    </p>
      
  </div>

</div>
---

## 🔬 주요 연구 및 기술 도메인

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 16px; margin: 20px 0;">

  <div style="border: 1px solid #e1e4e8; border-radius: 8px; padding: 18px; background-color: #f8f9fa; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #0366d6;">🌉 교량 및 구조물 유지관리</h3>
    <p style="font-size: 14px; color: #586069; line-height: 1.6;">
      기존 인프라 노후화에 대비한 데이터 기반 상태 평가 및 잔존 수명 예측.
    </p>
    <ul style="font-size: 13px; padding-left: 20px; color: #24292e;">
      <li style="margin-bottom: 8px;"><b>간편 균열 측정앱:</b> <br>
        <a href="/crack-gauge/" style="display: inline-block; margin-top: 6px; padding: 6px 14px; background-color: #0366d6; color: #ffffff; font-size: 14px; font-weight: bold; border-radius: 6px; text-decoration: none; box-shadow: 0 2px 5px rgba(0,0,0,0.15);">▶ 균열폭 측정기 실행 ↗</a>
        <a href="/assets/images/01_crack_sample.jpg" download="균열측정_샘플사진.jpg" style="display: inline-block; margin-top: 8px; padding: 5px 12px; background-color: #2ea44f; color: #ffffff; font-size: 13px; font-weight: bold; border-radius: 6px; text-decoration: none; box-shadow: 0 1px 3px rgba(0,0,0,0.15);">📥 균열 샘플사진 다운로드</a>
      </li>
      <li>센서 계측 데이터 기반 거동 분석</li>
      <li>점검 자동화 프로세스 구축</li>
    </ul>
  </div>

  <div style="border: 1px solid #e1e4e8; border-radius: 8px; padding: 18px; background-color: #f8f9fa; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #28a745;">⚙️ 구조 해석 및 설계 자동화</h3>
    <p style="font-size: 14px; color: #586069; line-height: 1.6;">
      반복적인 구조 계산 오류를 원천 차단하고 정밀도를 극대화하는 Python 모듈 개발.
    </p>
    <ul style="font-size: 13px; padding-left: 20px; color: #24292e;">
      <li>시행쐐기법(Trial Wedge) 기반 토압 산정 모듈</li>
      <li>KDS 기준 만족 여부 자동 검토 스크립트</li>
      <li>구조 계산서 및 배근 데이터 정밀 연동</li>
    </ul>
  </div>

  <div style="border: 1px solid #e1e4e8; border-radius: 8px; padding: 18px; background-color: #f8f9fa; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #6f42c1;">📐 구조 재료 및 기준 분석</h3>
    <p style="font-size: 14px; color: #586069; line-height: 1.6;">
      철근콘크리트, 강구조 및 신소재(비강재, 유리 등) 구조 거동 검토.
    </p>
    <ul style="font-size: 13px; padding-left: 20px; color: #24292e;">
      <li style="margin-bottom: 12px;">
        <strong>KDS(국가건설기준) 개정 사항 및 적용성 검토</strong>
        <div style="margin-top: 8px;">
          <a href="./docs/obsidian-gemini.html" target="_blank" style="display: inline-block; background-color: #0d6efd; color: white; padding: 6px 12px; border-radius: 6px; text-decoration: none; font-weight: bold; font-size: 13px;">
            ▶ 옵시디언 + 제미나이 ↗
          </a>
        </div>
      </li>
      <li style="margin-bottom: 6px;">국내외 학술 논문 및 실무 검증 자료 정리</li>
      <li>특수 구조물 해석 사례 연구</li>
    </ul>
</div> <!-- 세 번째 카드 닫는 태그 -->

</div> <!-- ★★★ 이 태그가 반드시 있어야 전체 3단 배치가 끝납니다 ★★★ -->


---


## 📊 진행 중인 연구 및 모듈 현황

| 모듈 / 연구 주제 | 적용 기술 / 기준 | 현재 상태 | 서비스 및 소스 링크 |
| :--- | :--- | :---: | :---: |
| **사진 기반 균열 계측 (`crack-gauge`)** | JavaScript, Canvas API | `운영/검증` | [▶ 웹 앱 실행](/crack-gauge/) \| [GitHub](https://github.com/b23041/crack-gauge) |
| **옹벽 토압 산정기 (시행쐐기법)** | Python, KDS 기준 연계 | `개발 중` | 내부 문서 |
| **교량 상태 진단 데이터베이스** | 시계열 데이터 전처리 | `기획 단계` | 아카이브 |

---

## 📬 방명록 및 기술 교류 / 문의 (간편 접수)
> 연구 협업, 기술 자문 문의, 사이트 방문 소감을 자유롭게 남겨주세요. (로그인 없이 바로 작성하실 수 있습니다.)

<div style="margin: 20px 0;">
  <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdm8utDvKiTUiGMIrL98XJRjxfXtlojDVRfsiEhHTHtIEwIQg/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0" style="border: 1px solid #e1e4e8; border-radius: 8px; background: #fff;">로드 중…</iframe>
</div>

---

## 💬 연구실 방명록 & 피드백 (GitHub)
> GitHub 계정으로 공개 토론 및 피드백 글을 남기실 수 있습니다.

<div class="giscus" style="margin-top: 20px; min-height: 250px;"></div>

<script src="https://giscus.app/client.js"
        data-repo="b23041/b23041.github.io"
        data-repo-id="R_kgDOUmwSfg"
        data-category="General"
        data-category-id="DIC_kwDOUmwSfs4DGNhP"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="light"
        data-lang="ko"
        crossorigin="anonymous"
        async>
</script>

---

## 📌 연구 철학 (Engineering Philosophy)
> *"구조 계산의 작은 오차는 안전과 인명 피해로 직결됩니다. '추정'이 아닌 명확한 공학적 기준과 검증된 데이터를 근거로 설계하고 유지관리합니다."*

---

<p align="center" style="font-size: 12px; color: #8c959f; margin-top: 40px;">
  © 2026 smart-civil-maintain.com · Built with GitHub Pages & Jekyll
</p>

<style>
  /* 깃허브 테마의 기본 표 스타일을 강제로 100%로 확장 */
  .main-content table,
  .markdown-body table,
  table {
    display: table !important;
    width: 100% !important;
  }

  /* 푸터 숨김 */
  footer, .site-footer {
    display: none !important;
  }
  
  /* 페이지 전체 본문 폭을 1320px로 넓게 조정 */
  .main-content {
    max-width: 1320px !important; 
  }
  
  /* 상단 헤더 높이 축소 */
  .page-header {
    padding: 1.5rem 1rem !important; 
  }
  .project-name {
    font-size: 1.8rem !important; 
    margin-bottom: 0.3rem !important;
  }
  .project-tagline {
    font-size: 1rem !important; 
    margin-bottom: 0 !important;
  }
</style>
