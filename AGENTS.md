# AGENTS — codecraft-site (code-craft-service.com 소개 사이트)

## Common References (워크스페이스 공유)

- /Users/codecraft/Desktop/01.workspace/md-common/AGENTS_COMMON.md
- /Users/codecraft/Desktop/01.workspace/md-common/HARNESS_ENGINEERING.md
- /Users/codecraft/Desktop/01.workspace/md-common/HOOK_ENGINEERING.md

> 실행·배포 명령은 프로젝트별로 다르다. 본 프로젝트는 아래 스택별 명령과 `CLAUDE.md` 를 우선한다.

## Stack & Dev (Project Specific)

- 스택: 정적 HTML/CSS/JS. 빌드 단계 없음.
- 확인: `open index.html` 또는 `python3 -m http.server`
- 저장소: `CodeCraftService/CodeCraftService.github.io` (브랜치 `master`)

## Deploy & Docs (Project Specific)

- **`master` push = 즉시 공개 배포**(GitHub Pages). 커스텀 도메인은 `CNAME` 파일이 지정하므로 삭제 금지.
- 앱 CTA 는 Google Play `kr.pe.ayo.app` 로 연결된다 — 패키지명 변경 시 함께 수정한다.
- changelog 파일은 없다. 변경은 `/Users/codecraft/Desktop/01.workspace/docu/ext/codecraft-site/README.md` 에 반영한다.
