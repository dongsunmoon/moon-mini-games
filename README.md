# 🌙 Moon Mini Games

어린이를 위한 웹 미니 게임 모음입니다. 설치 없이 휴대폰·태블릿·PC 브라우저에서 바로 할 수 있어요.
Mini games for kids that run right in the browser on phones, tablets and PCs.

▶ **Play:** https://game.dongsunmoon.com/

| 게임 | 파일 | 설명 |
|---|---|---|
| 🕵️ 꼬마 탐정단 · Little Detectives | `detective_game.html` | 목격자 단서로 범인 찾기, 순찰 미니게임 7종 |
| 🔮 마블 레이스 · Marble Rush | `marble_rush_3d.html` | 진짜 물리로 튕기는 마블런 레이스, 내 구슬 응원 · 리그 5경기 |
| ♞ 꼬마 체스 기사단 · Little Chess Knights | `chess_knights.html` | 체스 퍼즐 모험 6지역 · 보스 AI 대결 · 번개 퍼즐 · 레벨업과 상점 |
| 🔬 꼬마 과학 수호대 · Little Science Guardians | `science_guardians.html` | 초등 과학 퀴즈와 실험으로 악당 물리치기 · 9지역 · 학년별 난이도 3단계 · 대원(플레이어) 여러 명 |

## GitHub Pages로 공개하기

1. 이 폴더의 파일을 `main` 브랜치에 push 합니다.
2. GitHub 저장소 → **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main / (root)** → Save.
3. 1~2분 뒤 위 Play 주소로 접속하면 `index.html`(게임 선택 화면)이 열립니다.
4. 사용자 도메인(`game.dongsunmoon.com`)은 저장소의 `CNAME` 파일로 연결돼 있어요. 이 파일은 지우지 마세요.

무료 계정은 저장소가 **public**이어야 Pages를 쓸 수 있습니다.

## 언어 (한국어 / English)

- 처음에는 기기 언어를 따르고, 화면의 🌐 버튼으로 바꾸면 모든 게임에 함께 적용됩니다.
- 주소 뒤에 `?lang=ko` 또는 `?lang=en`을 붙이면 해당 언어로 바로 열립니다.
- 음성은 브라우저 내장 TTS(Web Speech API)를 사용하므로 음성 파일이 필요 없습니다. 음질은 기기에 설치된 목소리에 따라 달라집니다.

### 게임을 고칠 때

- 화면에 보이는 문장은 `L('한국어','English')` 형태로 두 언어를 나란히 적습니다.
- HTML에 직접 쓴 문장은 `data-en="English"` 속성을 붙이면 영어 모드에서 바뀝니다.
- 새 게임을 추가하려면 `index.html`의 `GAMES` 목록에 항목 하나를 복사해 `file`과 문구를 바꾸면 됩니다.

## 체스 퍼즐 출처

`chess_knights.html`의 퍼즐은 [Lichess 공개 퍼즐 데이터베이스](https://database.lichess.org/#puzzles)에서 골랐습니다. 이 데이터는 CC0(퍼블릭 도메인)으로 공개돼 있어 자유롭게 쓸 수 있습니다. 체스판·기물 그림, 캐릭터, 효과음, AI는 이 게임을 위해 직접 만들었습니다.

## 과학 게임 내용

`science_guardians.html`의 문제, 설명, 실험, 그림, 소리는 모두 이 게임을 위해 직접 썼습니다. 한국과 캐나다(온타리오 등) 초등 과학 교과에서 다루는 주제(방위·그림자·힘과 운동·자석·물질의 상태·생물·날씨와 지구·소리와 몸)와 생활 안전 상식을 바탕으로 했습니다.

- 난이도는 학년에 맞춰 나뉩니다. 쉬움(1~2학년)은 생활 속 관찰과 체험, 보통(3~4학년)은 한국 2022 개정 3~4학년군 단원(힘과 우리 생활, 자석, 물의 상태 변화, 땅의 변화, 밤하늘, 생물과 환경, 기체, 기후변화 등), 어려움(5~6학년)은 5~6학년군 단원(빛의 굴절과 렌즈, 열, 지구의 운동과 계절, 날씨, 속력, 우리 몸, 전기, 산과 염기, 용해, 연소, 에너지, 지층과 화석)을 다룹니다. 온타리오 1~6학년 주제(구조물, 단순 기계, 비행, 흙과 암석 등)도 함께 넣었습니다.
- 어려움을 골라도 아래 학년 문제가 복습으로 조금씩 섞여 나옵니다. 보통은 약 4문제 중 3문제, 어려움은 약 3문제 중 2문제가 자기 학년 문제입니다.
