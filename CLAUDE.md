# CLAUDE.md — codecraft-site (code-craft-service.com 소개 사이트)

찾아요!홈즈 소개용 정적 랜딩 페이지. GitHub Pages(`master`)로 서빙된다.

## 공통 지침 (워크스페이스 공유)
푸시 정책, docu 기록, 하네스/훅 원칙은 아래 공통문서를 따른다. **실행·배포 명령은 이 문서의 프로젝트별 절을 우선**한다.
@/Users/codecraft/Desktop/01.workspace/md-common/CLAUDE_COMMON.md

## 구성 · 확인
- `index.html`(섹션: realty / subscription / community / ai), `css/styles.css`, `js/scripts.js`, `img/`, `assets/favicon.ico`
- 빌드 단계 없음. 로컬 확인은 `python3 -m http.server`.

## 규칙
- **`master` push 가 곧 공개 배포**다. 확인 후 올린다.
- `CNAME`(code-craft-service.com) 삭제 금지 — 지우면 커스텀 도메인이 끊긴다.
- 앱 CTA 는 Google Play `kr.pe.ayo.app` 로 연결된다(찾아요! 홈즈 앱, `java/m.ayo.pe.kr`). 패키지명이 바뀌면 함께 고친다.
- 서비스 문구 변경 시 `<meta name="description">` 과 `og:description` 도 같이 갱신한다.
- 문서: `/Users/codecraft/Desktop/01.workspace/docu/ext/codecraft-site/README.md` (changelog 파일 없음)
