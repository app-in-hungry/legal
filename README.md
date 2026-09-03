# legal — 앱인토스 미니앱 약관 · 개인정보처리방침 (통합 게시 레포)

에프티에스(FTS)가 운영하는 앱인토스 미니앱들의 서비스 이용약관과 개인정보처리방침을 **앱마다 폴더 하나**로 모아 GitHub Pages 로 게시한다.
2026-09-01 부터 새 앱은 앱별 레포(`<슬러그>-legal`) 대신 여기에 둔다. 운세 무당벌레(app26)는 이미 콘솔에 등록된 별도 레포(`lucky-ladybug-legal`)를 그대로 쓴다.

```
legal/
├── index.html          앱 목록 (루트가 404 가 되지 않게)
├── <appName>/          앱 하나 = 폴더 하나. 폴더 이름은 콘솔 appName
│   ├── index.html      안내 페이지
│   ├── terms-of-service.html   ← 콘솔 '토스 로그인 > 등록하기' 에 넣는 링크
│   └── privacy-policy.html
└── README.md
```

| 앱 | 폴더 | 이용약관 URL |
|---|---|---|
| 오늘 뭐 해먹지 (app27) | `what-to-cook/` | https://app-in-hungry.github.io/legal/what-to-cook/terms-of-service.html |
| QR코드 만들기 (app28) | `qr-code-maker/` | https://app-in-hungry.github.io/legal/qr-code-maker/terms-of-service.html — 게시 2026-09-04 |
| 만 나이 계산기 (app30) | `age-calc/` | https://app-in-hungry.github.io/legal/age-calc/terms-of-service.html — 게시 2026-09-04 |
| N빵 계산기 (app29) | `nbbang-calc/` | https://app-in-hungry.github.io/legal/nbbang-calc/terms-of-service.html — 게시 2026-09-03 |

## 규칙

- **여기 파일은 전부 생성물이다. 직접 고치지 않는다.** 원본은 각 앱 레포의 `src/app/legal.ts`(앱의 사실) + `src/platform/legal/build.ts`(조항 뼈대)이고,
  앱에서 `npm run legal:export` 를 돌리면 `app-registration/04-terms/site/` 와 함께 이 레포의 `<appName>/` 에도 써진다(`../LEGAL` 이 있을 때).
- 개정: 앱에서 export → 여기서 commit · push. URL 이 안 바뀌어 콘솔 재등록은 불필요. **본문이 바뀌는 개정은 push 전에 사람이 읽는다** — 게시된 순간 법적 문서다.
- 페이지는 외부 요청이 없어야 한다(폰트·CSS 인라인). 약관 페이지가 제3자에 접속 기록을 흘리면 방침의 '국외 이전 없음'과 어긋난다.
- 폴더 이름은 콘솔 appName 과 같게 — 앱이 많아져도 어느 약관이 어느 앱인지 헷갈리지 않게.
