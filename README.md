# jaemin93.github.io

개인 기술 블로그. [Astro](https://astro.build/) + [AstroPaper](https://github.com/satnaing/astro-paper) 테마 기반이며,
`main` 브랜치에 push하면 GitHub Actions가 자동으로 GitHub Pages에 배포합니다.

## 개발

```sh
pnpm install
pnpm dev      # http://localhost:4321
pnpm build    # 정적 빌드 + pagefind 검색 인덱스 생성
```

## 글 쓰기

`src/content/posts/`에 markdown 파일을 추가합니다.

```md
---
title: "제목"
description: "설명"
pubDatetime: 2026-07-13T18:00:00+09:00
tags:
  - tag1
---

본문
```

사이트 설정(제목, 소셜 링크 등)은 `astro-paper.config.ts`에서 수정합니다.
