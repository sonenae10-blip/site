<h1>웹 랜딩 페이지 퍼블리싱 프로젝트<br>
Static Web Landing Page – Publishing Project</h1>

<h2>1. 프로젝트 개요</h2>
본 프로젝트는 HTML/CSS 기반의 정적 웹 랜딩 페이지로,
기본적인 서비스 소개 흐름과 사용자 행동 유도(CTA)를 중심으로 구성된 퍼블리싱 포트폴리오용 웹사이트입니다.

레이아웃 설계, 시각적 위계, 컴포넌트 정렬 및 UI 완성도를 중점으로 제작하였으며,
실제 서비스 또는 브랜드 랜딩 페이지로 확장 가능한 구조를 목표로 합니다.

배포: GitHub Pages

목적: 웹 퍼블리싱(레이아웃·UI 구성·정적 페이지 구현) 역량 증명

<strong>🔗 배포 URL</strong>
https://sonenae10-blip.github.io/site/
<img width="1695" height="868" alt="image" src="https://github.com/user-attachments/assets/5c8938ff-4995-470c-9bc1-0bb5ca6047c6" />
<hr />

<h2>2. 화면 구성 및 사용자 흐름(UX Flow)</h2>
1. Header 영역

header에 fixed 헤더를 적용해 스크롤 시에도 메뉴 접근성을 유지합니다.

상단 네비게이션은 nav.nav로 구성하고, 주요 CTA는 공통 버튼 클래스 .btn으로 통일했습니다.<br><br>
2. Hero 섹션

메인 비주얼은 .hero 섹션에서 텍스트(.hero-text) 와 이미지(.hero-image) 를 병렬 배치했습니다.

제목은 .hero-hlorem, 설명은 .hero-lorem으로 위계를 분리했습니다.<br><br>
3. About 섹션

소개 영역은 .about 섹션으로 구성하고, 이미지(.about-image)와 텍스트(.about-text)를 나란히 배치했습니다.

제목은 .about-hlorem, 본문은 .about-lorem으로 구성했습니다.<br><br>
4. Gallery / Subscribe

이미지 갤러리는 .gallery-images로 그룹화하고, 하단 설명+버튼은 .gallery-footer로 분리했습니다.

구독 영역은 .subscribe-box 카드 형태로 구성했으며, 입력 UI는 .input-box 안에 .mail-icon + .input + .btn로 조합했습니다.<br><br>
5. Footer 영역

로고 및 저작권 문구 배치

페이지 마무리 영역으로서 서비스 형태의 완성도를 확보했습니다.<br><br>
<hr />

<h2>3. 구현 포인트</h2>
1. 레이아웃 중심 퍼블리싱

전체 페이지를 섹션 단위로 분리하여 정보 흐름이 자연스럽게 이어지도록 설계<br><br>
2. UI 컴포넌트 일관성

버튼, 입력창, 카드 요소에 동일한 디자인 규칙 적용

재사용 가능한 구조를 고려한 클래스 설계<br><br>
3. 가독성과 시각적 위계

제목, 본문, 강조 텍스트의 크기·색상·두께를 구분하여 정보 전달력 강화<br><br>
4. 확장 가능 구조

JavaScript 및 실제 데이터 연동을 고려한 기본 폼 구조 유지
