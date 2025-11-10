# 티도리 프레임워크 기반 블로그 템플릿

## Setup

- tidory.config.js 설정 파일 수정
  - ts_session: 티스토리 세션 아이디
  - url: 블로그 주소

## Preview

```bash
npm run preview
```

## 배포

**tidory.config.js** 에 `ts_session`, `url` 이 설정되었다면 배포를 진행할 수 있습니다. 티도리 프레임워크의 [빌드 및 배포](https://github.com/pronist/tidory/wiki/Deployment)를 참고하십시오.

```bash
npm run production && npm run store
```

```bash
npm run production && npm run deploy
```

## 저작권

Copyright 2020-2025. [SangWoo Jeong](https://github.com/pronist). All rights reserved.
