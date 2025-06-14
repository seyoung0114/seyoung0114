
Freelancer Jekyll theme  
=========================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/template-overviews/freelancer/)
이 프로젝트는 해당 테마를 기반으로 제작한 홈페이지 입니다.
실제 웹사이트: https://seyoung0114.github.io/seyoung0114/
---

# 주요 기능 및 구성
-상단 네비게이션을 통한 섹션 이동
-반응형 웹 디자인
-프로젝트 소개 섹션 구성
-기술 스택 정리
-자기소개 섹션 구현
-GitHub Pages를 활용한 정적 웹사이트 호스팅
---

# 이력서 관련 추가 기능
# 1) 기능 제목 : 자기소개
# 2) 설명
학력, 관심 분야, 비전 등을 소개하는 자기소개 섹션을 추가하였습니다.

# 3) 코드 위치
-HTML : '_includes/About.html'
-include 호출 : '_layouts/default.html'
-메뉴 연결 : '_includes/nav.html'
---

# 4) 코드 설명
- 'About.html' : HTML5의 `<section>` 태그를 사용해 고유 ID `about`를 부여하였으며, Bootstrap 클래스로 반응형 레이아웃 구성. 내부에는 제목, 부제목, 소개 문단을 포함하고 있으며, `p.text-muted`로 글자색과 톤을 조정함.
- `default.html`: `{% include About.html %}`를 통해 전체 레이아웃에 About 섹션을 삽입함.
- `nav.html`: `<li class="page-scroll"><a href="#about">About</a></li>` 항목을 추가하여, 네비게이션 메뉴에서 해당 섹션으로 스크롤 이동 가능하게 구현함.
---

# 프로젝트 목록
1. 부산행 프로젝트
2. 듄 프로젝트
3. 앱인벤터 프로젝트
4. 날씨 기반 패션 추천 앱(예정)
5. 파일 암호화 프로그램(예정)
---

# 희망 직무
-시스템소프트웨어 개발자
-정보보안 소프트웨어 개발자
---
