# vuethree

Vue + Three.js 웹앱 빌드 결과물 (아카이브).

과거 `MetaSonGi.github.io` 사용자 사이트 루트에 배포되었던 빌드이며,
2026-10-10 '성남 AI 랩' 포트폴리오 허브로 교체되면서 별도 저장소로 분리·보존되었습니다.

- `index.html` + `js/` + `css/`: Vue CLI 프로덕션 빌드
  (용량이 큰 벤더 청크 `chunk-vendors.*.js`, `.map` 소스맵, `favicon.ico`는 아카이브에서 제외
  — 앱 고유 코드인 `app.*.js`와 스타일은 모두 보존됨)
- `.gitattributes`: 기존 저장소 설정 유지

> 참고: 빌드된 `index.html`이 `/js/`, `/css/` 절대 경로를 참조하므로,
> GitHub Pages 프로젝트 사이트(서브 경로)에서는 그대로 실행되지 않습니다.
> 다시 라이브로 올리려면 루트 도메인에 배포하거나 경로를 상대 경로로 수정하세요.
