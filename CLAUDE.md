# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project: tovin Labs 회사 홈페이지 (tovinlabs.com)

회사 소개, 제품 랜딩, 법적 문서(처방 정책·이용약관·아동 보호)를 게재하는 정적 마케팅 사이트. Cloudflare Pages 배포.

## 회사 운영 컨텍스트

이 repo는 **tovin Labs sibling 프로젝트** 중 하나. 회사 운영 허브는 [/Users/snhj/workspace/tovinLabs/](../tovinLabs/)이며 사이트 기획서·법적 문서 초안을 그쪽에서 관리한다:

- 기획서: [tovinLabs/docs/homepage-plan.md](../tovinLabs/docs/homepage-plan.md)
- 법적 문서 초안: [tovinLabs/docs/legal/](../tovinLabs/docs/legal/)
- 데이터 인벤토리: [tovinLabs/docs/data-inventory.md](../tovinLabs/docs/data-inventory.md)

이 repo는 **콘텐츠 게재용 코드**만 담는다. 전략·결정·초안은 허브에서.

## 명령어

```bash
npm run dev       # 개발 서버 (localhost:4321)
npm run build     # 프로덕션 빌드 (dist/)
npm run preview   # 빌드 미리보기
```

## 기술 스택

- Astro 6 + TypeScript (strict)
- Tailwind CSS 4 (Vite plugin, `@theme` directive in [src/styles/global.css](src/styles/global.css))
- MDX (법적 문서 콘텐츠 관리 — Phase 1+에 도입 예정)
- @astrojs/sitemap (i18n 지원, 자동 sitemap-index.xml 생성)
- Cloudflare Pages 배포 (main 자동, PR preview)
- 외부 SDK 없음. Cloudflare Web Analytics만 (privacy-friendly, 쿠키 X)

## i18n 라우팅

[astro.config.mjs](astro.config.mjs)의 `i18n` 설정으로 처리. `prefixDefaultLocale: false`이라 한국어가 디폴트.

- 기본 한국어: `/`, `/legal/...`
- 영어: `/en/`, `/en/legal/...`
- 일본어 (Phase 2): 코토바 제품 페이지만 추가 예정

페이지 추가 시 KR/EN 양쪽에 만드는 게 원칙.

## 디자인 토큰

[src/styles/global.css](src/styles/global.css)의 `@theme` 블록에서 정의. 색상·폰트를 모두 여기서 관리. 컴포넌트는 `var(--color-*)` 또는 Tailwind 임의값 (`bg-[var(--color-fg)]`)으로 참조.

폰트는 시스템 폰트 스택 (Pretendard 자체 호스팅은 Phase 1에 검토).

## Phase 0 범위 (출시 1주 전, 현재)

- `/` 회사 랜딩 (KR + EN) ✅
- `/legal/privacy/kotoba` (KR + EN) — stub 상태, 정식 콘텐츠 교체 예정
- `/legal/privacy/mochi-jump` (KR + EN) — stub
- `/legal/terms` (KR + EN) — stub
- `/legal/kids-policy` (KR + EN) — stub

법적 문서 정식 콘텐츠는 [tovinLabs/docs/legal/](../tovinLabs/docs/legal/)의 초안을 검수·확정 후 이 repo로 이관하여 게재.

Phase 1+ 페이지(`/products/*`, `/about`, `/contact`)는 이후 추가.

## 배포 파이프라인

- GitHub `main` push → Cloudflare Pages 자동 배포 (production: tovinlabs.com)
- PR open → preview deployment (`<branch>.tovinlabs-web.pages.dev`)
- 빌드: `npm run build`, output: `dist/`
- 환경변수 없음 (정적 사이트)
