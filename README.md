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

| 앱 | 폴더 | 이용약관 URL (시행일은 각 폴더 `terms-of-service.html` 머리말이 정본) |
|---|---|---|
| 오늘 뭐 해먹지 (app27) | `what-to-cook/` | https://app-in-hungry.github.io/legal/what-to-cook/terms-of-service.html — 게시 2026-09-01 · **개정 2026-09-14**(방침 저장 항목에서 '안내 확인 여부' 삭제, 시행일 2026-09-14) · 제7조 토스 포인트(미션 레시피 확인하기) |
| QR코드 만들기 (app28) | `make-qr/` | https://app-in-hungry.github.io/legal/make-qr/terms-of-service.html — 게시 2026-09-04 · **개정 2026-09-14**(제7조 토스 포인트 — 미션 QR코드 만들기, 시행일 2026-09-14) |
| 나이계산기 (app30) | `calc-age/` | https://app-in-hungry.github.io/legal/calc-age/terms-of-service.html — 게시 2026-09-14 (9/4~9/5 `age-calc/` 에서 옮김 — 콘솔 appName) · 시행일 2026-09-14 · 제7조 토스 포인트(미션 인생 시간표 확인하기) · 본문 '나이 연표' → '인생 시간표' |
| N빵 계산기 (app29) | `nbbang-calc/` | https://app-in-hungry.github.io/legal/nbbang-calc/terms-of-service.html — 게시 2026-09-03 · 개정 2026-09-14(방침 저장 항목 '첫 안내 확인 여부' → '결과 화면을 연 횟수') · **개정 2026-09-18**(제7조 토스 포인트 — 미션 서비스 이용하기, 시행일 2026-09-18) |
| 카톡 대화 온도계 (app31) | `kakaotalk-thermo/` | https://app-in-hungry.github.io/legal/kakaotalk-thermo/terms-of-service.html — 게시 2026-09-07 · **개정 2026-09-14**(제7조 토스 포인트 — 미션 우리 카톡방 분석해보기 · 같은 날 저녁 개인정보처리방침 저장 항목 개정: 첫 방문 여부 삭제 · 저장본 분석 데이터 · 토스 포인트 지급 기록, 시행일 2026-09-14) |
| 아침 인사 카드 (app34) | `morningcard/` | https://app-in-hungry.github.io/legal/morningcard/terms-of-service.html — 게시 2026-09-22 · **개정 2026-09-23**(방침 2항 '문제 알리기' 전송 항목 · 5항 구글 계정 보관 · 국외 · 90일 삭제, 시행일 2026-09-23) · 제7조 토스 포인트(미션 '추석 인사카드 받아가기' 5원 × 하루 1 · 저장 = 보상형 광고 뒤) · 콘솔 appName `morningcard`(하이픈 없음) |
| 인스타 DM 온도계 (app32) | `insta-thermo/` | https://app-in-hungry.github.io/legal/insta-thermo/terms-of-service.html — 게시 2026-09-18 · **개정 2026-09-23**(시행일 2026-09-23 · 제7조 토스 포인트 신설 — 미션 '인스타DM 분석하기' 1원 × 하루 5 · 광고를 끝까지 보고 전체 카드를 열 때 · 뒤 조 번호 +1 · 방침 저장 항목에 토스 포인트 지급 기록 · 통계 항목에 적립 여부 · 4항 '광고와 토스 포인트 과정의 정보 처리') · 방침 저장 항목에 "파일을 요청했다고 표시한 시각"(대기 화면) |
| 황금 거위 (app45) | `golden-goose-egg/` | https://app-in-hungry.github.io/legal/golden-goose-egg/terms-of-service.html — 게시 · 시행일 2026-10-10(같은 날 1.1 맞춤 개정 — 못 받은 차례는 나중에 · 그날 줄 수 없는 금액은 건너뜀 · 방침 놀기 기록) · 제7조 토스 포인트(미션 '[황금거위] 모이 주기 · 모이 더 주기 · 여섯 번째 · 일곱 번째 모이 주기' 1 · 2 · 3 · 4원 — 모이 주기 뒤 광고를 끝까지 볼 때 · 차례대로 1 · 1 · 1 · 2 · 2 · 3 · 4원 · 30분) · 황금알은 그림(금전적 가치 없음) · 기록은 기기 안 |
| 달러 줍기 (app46) | `dollar-walk/` | https://app-in-hungry.github.io/legal/dollar-walk/terms-of-service.html — 게시 · 시행일 2026-10-10(같은 날 1.1 맞춤 개정 — 못 받은 차례는 나중에 · 그날 줄 수 없는 금액은 건너뜀 · 방침 놀기 기록) · 제7조 토스 포인트(미션 '[달러줍기] 산책 보내기 · 산책 더 보내기 · 여섯 번째 · 일곱 번째 산책 보내기' 1 · 2 · 3 · 4원) · 제8조 ④ 달러 환산은 공개 환율로 계산한 참고값(바꿔 주지 않음) · 방침: 하루 몇 차례 공개 환율 데이터(currency-api.pages.dev · cdn.jsdelivr.net) 요청에 개인정보 없음 · 강아지가 줍는 달러는 그림 |
| 짹짹 습관 (app38) | `chirp-habit/` | https://app-in-hungry.github.io/legal/chirp-habit/terms-of-service.html — 게시 2026-10-05 · 시행일 2026-10-05 · 제7조 토스 포인트(미션 '[짹짹습관] 첫 번째 · 두 번째 · 세 번째 간식 주기' 1 · 2 · 3원 · 토닥 · 체크 뒤 간식 광고를 끝까지 볼 때 · 순서대로) · **같은 날 개정 재게시**(출시 전 · 제8조 ③ "앞 차례를 받고 30분이 지나야 다음 차례가 열립니다" — 간식 사이 30분, 시행일 그대로 2026-10-05) · 기록은 기기 안(식별키는 저장 · 전송 안 함) · appName 은 콘솔 등록 전 제안값 — 콘솔 값이 다르면 폴더를 옮긴다 |
| 궁합 보기 (app33) | `gung-hap/` | https://app-in-hungry.github.io/legal/gung-hap/terms-of-service.html — 게시 2026-10-06 · 시행일 2026-10-06 · 제7조 토스 포인트(미션 '궁합 확인하기' · 1원 × 하루 1 — 광고를 끝까지 보고 조언 카드를 열 때) · **같은 날 개정**(제7조 ① 지급 조건 · ③ 한도를 약관에 직접 — 홈의 고지 문단을 뺌) |
| 오늘 음력 (app35) | `today-lunar/` | https://app-in-hungry.github.io/legal/today-lunar/terms-of-service.html — 게시 2026-10-06 · 시행일 2026-10-06 · **같은 날 개정**(제7조 토스 포인트 — 미션 '우리집 연간표 확인하기' · 1원 × 하루 1 · 광고를 끝까지 보고 연간 표를 열 때) · **2026-10-07 개정**(1.1 한 갈래 — 광고 문턱 · 입력 저장 안 함 문장, 시행일 2026-10-07) |
| 그때 그 돈 (app36) | `money-then/` | https://app-in-hungry.github.io/legal/money-then/terms-of-service.html — 게시 2026-10-06 · 시행일 2026-10-06 · **같은 날 개정**(제7조 토스 포인트 — 미션 '그 해 물가표 확인하기' · 1원 × 하루 1 · 광고를 끝까지 보고 물가표 · 연표를 열 때) |
| 내 폰 인구조사 (app37) | `phone-census/` | https://app-in-hungry.github.io/legal/phone-census/terms-of-service.html — 게시 2026-10-06 · 시행일 2026-10-06 · **같은 날 개정**(제8조 토스 포인트 — 미션 '내 폰 인구조사 해보기' · 1원 × 하루 1 · 광고를 끝까지 보고 내 연락처 카드를 열 때) · 연락처 권한(기기 안 계산 · 저장 · 전송 없음) |
| 물 한 잔 (app39) | `water-glass/` | https://app-in-hungry.github.io/legal/water-glass/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [물한잔] 물 마시기 · 물 더 마시기 · 일곱 번째 · 여덟 번째 물 마시기 1 · 2 · 3 · 4원 + 일주일 개근하기 3원 — 물 마시기 뒤 광고를 끝까지 볼 때 · 차례대로 1 · 1 · 1 · 1 · 2 · 2 · 3 · 4원) · 기록은 기기 안 |
| 창문 열었어요 (app40) | `open-window/` | https://app-in-hungry.github.io/legal/open-window/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [창문열었어요] 첫 번째 · 두 번째 · 세 번째 창문 열기 1 · 2 · 3원 + 일주일 개근하기 3원) · 기록은 기기 안 |
| 스트레칭 한 번 (app41) | `stretch-once/` | https://app-in-hungry.github.io/legal/stretch-once/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [스트레칭한번] 기지개 켜기 · 기지개 더 켜기 · 다섯 번째 기지개 켜기 1 · 2 · 3원 + 일주일 개근하기 3원) · 기록은 기기 안 |
| 오늘 웃었어요 (app42) | `daily-smile/` | https://app-in-hungry.github.io/legal/daily-smile/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [오늘웃었어요] 웃음 도장 찍기 · 웃음 도장 더 찍기 · 다섯 번째 도장 찍기 1 · 2 · 3원 + 일주일 개근하기 3원) · 기록은 기기 안 |
| 오늘의 계단 (app43) | `daily-stairs/` | https://app-in-hungry.github.io/legal/daily-stairs/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [오늘의계단] 계단 오르기 · 계단 더 오르기 · 여섯 번째 · 일곱 번째 계단 오르기 1 · 2 · 3 · 4원 + 일주일 개근하기 3원) · 기록은 기기 안 |
| 달러 버튼 (app44) | `dollar-button/` | https://app-in-hungry.github.io/legal/dollar-button/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [달러버튼] 달러 버튼 누르기 · 달러 버튼 더 누르기 · 여섯 번째 · 일곱 번째 버튼 누르기 1 · 2 · 3 · 4원 + 일주일 개근하기 3원 · 제8조 ④ 달러 환산은 공개 환율 참고값) · 기록은 기기 안 |
| 돈나무 물 주기 (app47) | `money-tree-water/` | https://app-in-hungry.github.io/legal/money-tree-water/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [돈나무물주기] 물 주기 · 물 더 주기 · 여섯 번째 · 일곱 번째 물 주기 1 · 2 · 3 · 4원 + 일주일 개근하기 3원 · 동전 잎 · 금화 열매는 그림) · 기록은 기기 안 |
| 복돼지 저금통 (app48) | `lucky-piggy-bank/` | https://app-in-hungry.github.io/legal/lucky-piggy-bank/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [복돼지저금통] 동전 넣기 · 동전 더 넣기 · 여섯 번째 · 일곱 번째 동전 넣기 1 · 2 · 3 · 4원 + 일주일 개근하기 3원 · 동전은 그림) · 기록은 기기 안 |
| 버튼 100번 (app49) | `button-100/` | https://app-in-hungry.github.io/legal/button-100/terms-of-service.html — 게시 · 시행일 2026-10-13(첫 게시) · 제7조 토스 포인트(미션 [버튼100번] 풍선 불기 · 풍선 더 불기 · 여섯 번째 · 일곱 번째 풍선 불기 1 · 2 · 3 · 4원 + 일주일 개근하기 3원) · 기록은 기기 안 |
| 행운봉투뽑기 (app50) | `lucky-envelope/` | https://app-in-hungry.github.io/legal/lucky-envelope/terms-of-service.html — 게시 · 시행일 2026-10-23(10/21 첫 게시 → 10/22 개정: 제8조 ② 끝 '오픈 기념 한정 이벤트' 단서 — 이벤트 동안 광고 없이 적립 · 일찍 끝날 수 있음 → 10/23 개정: '기간을 정하지 않고' 뺌 · 시행일을 게시일(한국 날짜)로) · 제7조 토스 포인트(미션 [행운봉투뽑기] 첫 번째 · 두 번째 · 세 번째 봉투 열기 · 하루 셋) · 제8조 ① 금액별 구성 · 몫(1~10원 · 5,000원 · 화면은 1~5,000원) · 기록은 기기 안 |
| 피식아재개그 (app56) | `pisik-joke/` | https://app-in-hungry.github.io/legal/pisik-joke/terms-of-service.html — 게시 · 시행일 2026-10-29(첫 게시 · 같은 날 `dad-joke/` 에서 옮김 — 콘솔 appName `pisik-joke`, `dad-joke` 는 선점) · 제7조 토스 포인트(미션 '[피식아재개그] 정답 보기' · 1원 × 하루 1 — 정답 보기 뒤 광고를 끝까지 볼 때) · 제8조 개그는 널리 알려진 아재개그를 모아 고른 것 · 풀이는 AI 도움으로 미리 씀 · 기록은 기기 안 · `og.png` = 보내기 링크 미리보기 그림 |
| 랄라세계여행 (app57) | `lala-travel/` | https://app-in-hungry.github.io/legal/lala-travel/terms-of-service.html — 게시 · 시행일 2026-10-31(첫 게시) · 제7조 토스 포인트(미션 '[랄라세계여행] 여행 떠나기' · 1원 × 하루 1 — 출발 뒤 광고를 끝까지 볼 때) · 나라 이야기는 외교부 · 백과사전 같은 공개 자료를 보고 미리 쓴 글(생성형 AI 이용 · 실시간 생성 아님) · 기록은 기기 안 · `og.png` = 보내기 링크 미리보기 그림 |
| 아따사투리 (app58) | `atta-dialect/` | https://app-in-hungry.github.io/legal/atta-dialect/terms-of-service.html — 게시 · 시행일 2026-10-31(첫 게시) · 제7조 토스 포인트(미션 '[아따사투리] 사투리 뜻 보기' · 1원 × 하루 1 — 그날 첫 뜻 보기에서 광고를 끝까지 볼 때) · 사투리와 뜻은 실제로 쓰이는 말을 모은 것 · 예문은 생성형 AI 의 도움으로 미리 지은 것(실시간 생성 아님) · 기록은 기기 안 · `og.png` = 보내기 링크 미리보기 그림 |

## 규칙

- **여기 파일은 전부 생성물이다. 직접 고치지 않는다.** 원본은 각 앱 레포의 `src/app/legal.ts`(앱의 사실) + `src/platform/legal/build.ts`(조항 뼈대)이고,
  앱에서 `npm run legal:export` 를 돌리면 `app-registration/04-terms/site/` 와 함께 이 레포의 `<appName>/` 에도 써진다(`../LEGAL` 이 있을 때).
- 개정: 앱에서 export → 여기서 commit · push. URL 이 안 바뀌어 콘솔 재등록은 불필요. **본문이 바뀌는 개정은 push 전에 사람이 읽는다** — 게시된 순간 법적 문서다.
- 페이지는 외부 요청이 없어야 한다(폰트·CSS 인라인). 약관 페이지가 제3자에 접속 기록을 흘리면 방침의 '국외 이전 없음'과 어긋난다.
- 폴더 이름은 콘솔 appName 과 같게 — 앱이 많아져도 어느 약관이 어느 앱인지 헷갈리지 않게.
- 예외: `kakaotalk-thermo/og.png` 는 약관이 아니라 **공유 링크 미리보기 이미지**(Share.createLink ogImageUrl · app31 `app-registration/02-screenshots/landscape-1.png` 복사, 2026-09-08). 다시 만들면 여기도 덮어쓴다.
