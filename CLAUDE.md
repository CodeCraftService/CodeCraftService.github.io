# CLAUDE.md — codecraft-site (code-craft-service.com 소개 사이트)

찾아요!홈즈 소개용 정적 랜딩 페이지. GitHub Pages(`master`)로 서빙된다.

## 워크스페이스 공통 지침 비적용 (독립 프로젝트)
`etc/`·`ext/` 는 실험·외부 협업 영역이라 워크스페이스 공통 지침(`md-common/`)과 공통 하네스(`ws-orchestrator`·공통 에이전트/스킬)를 **따르지 않는다**(2026-09-30 사용자 지시).
상위 `01.workspace/CLAUDE.md` 가 같이 읽혀도 그 공통 규칙·하네스 트리거는 적용하지 않는다. **이 문서만 따른다.**
기본값: 푸시·배포·발행은 사용자가 요청할 때만 한다. 비밀값은 커밋하지 않는다.

## 구성 · 확인
- `index.html`(섹션: realty / subscription / community / ai), `css/styles.css`, `js/scripts.js`, `img/`, `assets/favicon.ico`
- 빌드 단계 없음. 로컬 확인은 `python3 -m http.server`.

## 규칙
- **`master` push 가 곧 공개 배포**다. 확인 후 올린다.
- `CNAME`(code-craft-service.com) 삭제 금지 — 지우면 커스텀 도메인이 끊긴다.
- 앱 CTA 는 Google Play `kr.pe.ayo.app` 로 연결된다(찾아요! 홈즈 앱, `java/m.ayo.pe.kr`). 패키지명이 바뀌면 함께 고친다.
- 서비스 문구 변경 시 `<meta name="description">` 과 `og:description` 도 같이 갱신한다.
- 문서: `/Users/codecraft/workspace/docu/ext/codecraft-site/README.md` (changelog 파일 없음)
