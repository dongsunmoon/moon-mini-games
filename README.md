# 🌙 Moon Mini Games

어린이를 위한 웹 미니 게임 모음입니다. 설치 없이 휴대폰·태블릿·PC 브라우저에서 바로 할 수 있어요.
Mini games for kids that run right in the browser on phones, tablets and PCs.

▶ **Play:** https://dongsunmoon.github.io/moon-mini-games/

| 게임 | 파일 | 설명 |
|---|---|---|
| 🕵️ 꼬마 탐정단 · Little Detectives | `detective_game_v17.html` | 목격자 단서로 범인 찾기, 순찰 미니게임 6종 |
| 🔮 마블 레이스 3D · Marble Rush 3D | `marble_rush_3d_v3.html` | 내 구슬을 골라 📣 응원하는 구슬 레이스 |

## GitHub Pages로 공개하기

1. 이 폴더의 파일을 `main` 브랜치에 push 합니다.
2. GitHub 저장소 → **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main / (root)** → Save.
3. 1~2분 뒤 위 Play 주소로 접속하면 `index.html`(게임 선택 화면)이 열립니다.

무료 계정은 저장소가 **public**이어야 Pages를 쓸 수 있습니다.

## 언어 (한국어 / English)

- 처음에는 기기 언어를 따르고, 화면의 🌐 버튼으로 바꾸면 모든 게임에 함께 적용됩니다.
- 주소 뒤에 `?lang=ko` 또는 `?lang=en`을 붙이면 해당 언어로 바로 열립니다.
- 음성은 브라우저 내장 TTS(Web Speech API)를 사용하므로 음성 파일이 필요 없습니다. 음질은 기기에 설치된 목소리에 따라 달라집니다.

### 게임을 고칠 때

- 화면에 보이는 문장은 `L('한국어','English')` 형태로 두 언어를 나란히 적습니다.
- HTML에 직접 쓴 문장은 `data-en="English"` 속성을 붙이면 영어 모드에서 바뀝니다.
- 새 게임을 추가하려면 `index.html`의 `GAMES` 목록에 항목 하나를 복사해 `file`과 문구를 바꾸면 됩니다.
