# PaceCue-A Korean Presentation Rehearsal Tool
한국어 말 빠르기 측정 및 연습 웹


## 브랜치 규칙

| 브랜치 | 용도 |
|---|---|
| `main` | 최종 제출용. **직접 push 금지** |
| `develop` | 팀 통합 브랜치. 모든 작업은 여기로 합쳐요 |
| `feature/이름-기능` | 개인 작업용 |
| `backup-old-main` | 예전 실습 기록 보관용. 건드리지 않아요 |

## 작업 순서

1. 작업 시작 전: `git checkout develop` → `git pull origin develop`
2. 내 브랜치 만들기: `git checkout -b feature/이름-기능`
3. 작업 후 커밋 → `git push -u origin feature/이름-기능`
4. GitHub에서 **develop으로** Pull Request 만들기
5. 팀원 1명 이상 승인 후 머지

## 커밋 메시지 규칙

`접두어: 내용` 형식으로 써요.

- `feat:` 새 기능 (예: `feat: 속도계 UI 추가`)
- `fix:` 버그 수정
- `style:` 디자인/CSS 변경
- `docs:` 문서 수정
- `chore:` 기타 설정

## 파일 담당

| 파일 | 담당 |
|---|---|
| `index.html` | 강희서 |
| `css/tokens.css` | 김서연(호크마) |
| `css/style.css` | 강희서 |
| `js/editor.js` | 김서연(컴공) |
| `js/speech.js`, `js/prompter.js` | 신재연 |
| `js/pace.js`, `js/storage.js` | 편채영 |
| `js/main.js` | 김서연(호크마) |

내 담당이 아닌 파일은 수정하기 전에 담당자에게 먼저 말해 주세요.