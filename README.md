# 건강퍼스트 (gunkangfirst.com)

50~60대를 대상으로 한 통증 자가체크 + 영양제 복용 시간표 웹 유틸리티입니다. 별도 빌드 과정 없는 순수 정적 사이트(HTML/CSS/JS)입니다.

## 사이트 구성

- `index.html` — 메인 도구. 통증 자가체크(부위별 증상 체크 → 결과/권장 영양성분 안내)와 영양제 복용 시간표(성분 선택 → 시간대별 스케줄, 함께 먹을 때 주의사항) 두 기능 제공
- `about.html` — 사이트 소개
- `privacy.html` — 개인정보처리방침
- `404.html` — 커스텀 404 페이지
- `vitamind-guide.html`, `knee-supplements.html`, `calcium-timing.html`, `omega3-guide.html` — 검색 유입용 영양 정보 아티클 4편 (식약처·질병관리청·한국영양학회·NIH ODS·Mayo Clinic 등 출처 기반)
- `favicon.svg` — 사이트 아이콘 (캡슐/알약 모티프)
- `sitemap.xml`, `robots.txt`, `ads.txt` — SEO/애드센스 관련 파일
- `naver*.html` — 네이버 서치어드바이저 사이트 소유확인용 파일 (루트에 있어야 함, 삭제 금지)

## 배포

Cloudflare에 연결되어 `main` 브랜치에 push하면 자동 배포됩니다. 커스텀 도메인: **gunkangfirst.com**

## 참고

- `ads.txt`의 게시자 ID(`pub-0000000000000000`)는 더미값입니다 — 구글 애드센스 승인 후 실제 ID로 교체해야 합니다.
- 모든 페이지의 `.ad-slot { display:none; }` 규칙은 애드센스 광고 코드를 실제로 삽입할 때 제거하면 됩니다.
- 의료 자문을 대체하지 않는 일반 건강 정보 제공 목적의 사이트입니다.
- 사이트명은 '건강이 우선'이라는 의미를 담아 **건강퍼스트**로 정했습니다 (이전 이름 '건강지킴이'는 검색 시 동명의 콘텐츠가 너무 많아 변경).
