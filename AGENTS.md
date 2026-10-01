# AGENTS — codecraft-site (code-craft-service.com 소개 사이트)

## 워크스페이스 공통 지침 비적용 (독립 프로젝트)

- `etc/`·`ext/` 는 실험·외부 협업 영역이라 `md-common/`(AGENTS_COMMON·HARNESS·HOOK)과 공통 하네스를 따르지 않는다(2026-09-30). 이 문서와 `CLAUDE.md` 만 따른다.
- 기본값: 푸시·배포·발행은 사용자가 요청할 때만. 비밀값 커밋 금지.

## Stack & Dev (Project Specific)

- 스택: 정적 HTML/CSS/JS. 빌드 단계 없음.
- 확인: `open index.html` 또는 `python3 -m http.server`
- 저장소: `CodeCraftService/CodeCraftService.github.io` (브랜치 `master`)

## Deploy & Docs (Project Specific)

- **`master` push = 즉시 공개 배포**(GitHub Pages). 커스텀 도메인은 `CNAME` 파일이 지정하므로 삭제 금지.
- 앱 CTA 는 Google Play `kr.pe.ayo.app` 로 연결된다 — 패키지명 변경 시 함께 수정한다.
- changelog 파일은 없다. 변경은 `/Users/codecraft/workspace/docu/ext/codecraft-site/README.md` 에 반영한다.
