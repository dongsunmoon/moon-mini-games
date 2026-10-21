# 악기 소리 출처 · Instrument sound sources

`music_academy.html`(꼬마 음악 아카데미)이 쓰는 실제 악기 녹음입니다. 모두 **CC0 1.0(퍼블릭 도메인 기증)** 으로 공개된 자료라 누구나 자유롭게 쓸 수 있고, 저장소의 사용 제한에 포함되지 않습니다. CC0는 출처 표기가 필요 없지만, 고마운 마음으로 밝혀 둡니다.

These are real instrument recordings used by `music_academy.html`. Every file comes from material released under **CC0 1.0 (public domain dedication)**, so anyone may use them freely, and they are not covered by this repository's usage restriction. CC0 needs no credit, but we credit the sources anyway.

| 출처 · Source | 만든 곳 · Author | 라이선스 · License |
| --- | --- | --- |
| [Versilian Community Sample Library (VCSL)](https://github.com/sgossner/VCSL) | Versilian Studios | [CC0 1.0](https://github.com/sgossner/VCSL/blob/master/LICENSE) |
| [VSCO 2 Community Edition](https://github.com/sgossner/VSCO-2-CE) | Versilian Studios | [CC0 1.0](https://github.com/sgossner/VSCO-2-CE/blob/master/LICENSE) |
| [Taegum-1.aif](https://freesound.org/people/bletort/sounds/94934/) | bletort (Freesound) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |

## 폴더별 원본 · Files and where they came from

| 폴더 · Folder | 원본 · Original recording |
| --- | --- |
| `piano/` | VCSL · Grand Piano, Steinway B / NoSus (vl3) |
| `violin/` | VSCO 2 CE · Solo Violin / Arco Vib |
| `cello/` | VSCO 2 CE · Cello Section / susvib |
| `flute/` | VSCO 2 CE · Flute / susvib |
| `clarinet/` | VSCO 2 CE · Clarinet / susLong |
| `trumpet/` | VSCO 2 CE · Trumpet / sus |
| `trombone/` | VSCO 2 CE · Tenor Trombone / sus |
| `tuba/` | VSCO 2 CE · Tuba / sus |
| `sax/` | VCSL · Tenor Saxophone / Vibrato |
| `recorder/` | VCSL · Baroque Soprano Recorder / Sustain |
| `xylophone/` | VCSL · Xylophone / Medium Mallets |
| `glock/` | VCSL · Glockenspiel |
| `guitar/` | VCSL · Strumstick / Finger |
| `gayageum/` | VCSL · Dan Tranh / Normal |
| `daegeum/` | Freesound · bletort, Taegum-1.aif |
| `perc/` | VCSL · Bass Drum 1, Snare Drum Modern 1, Hi-Hat Cymbal, Tom 2, Suspended Cymbal 1, Claps, Woodblock, Shaker Small, Tambourine 1, Triangles, Timpani 1, Darbuka, Frame Drum, Gong 1, Brake Drum |

파일 이름은 실제로 나는 음 높이입니다(`Cs4` = C♯4). 원본 이름의 옥타브 표기가 라이브러리마다 달라서, 하나하나 음높이를 측정해 맞췄습니다.

File names give the pitch each file actually sounds (`Cs4` = C♯4). The libraries label octaves differently, so every file was pitch-measured and renamed.

## 바꾼 점 · Changes from the originals

- 모노로 바꾸고, 소리 시작 직전까지 앞부분을 자르고, 길이를 줄인 뒤 끝을 부드럽게 줄였습니다. 음량을 맞추고 AAC(`.m4a`)로 압축했습니다.
- Converted to mono, trimmed to the start of the sound, shortened with a gentle fade-out, level-matched and encoded as AAC (`.m4a`).

## 비슷한 소리로 대신한 악기 · Stand-ins

공개된 CC0 녹음이 없는 악기는 가장 비슷한 녹음으로 대신합니다.

Instruments without a CC0 recording borrow the closest one.

| 악기 · Instrument | 쓰는 녹음 · Recording used |
| --- | --- |
| 가야금 Gayageum, 거문고 Geomungo | 베트남 쟁 Dan Tranh (거문고는 더 낮게 · lower for geomungo) |
| 해금 Haegeum | 바이올린 Violin |
| 단소 Danso | 소프라노 리코더 Soprano recorder |
| 장구 Janggu | 다르부카 Darbuka (낮은 소리 쿵 · 높은 소리 덕 / low "kung", high "deok") |
| 북 Buk | 프레임 드럼 Frame drum |
| 징 Jing | 공 Gong |
| 꽹과리 Kkwaenggwari | 브레이크 드럼 Brake drum |
| 기타 Guitar | 스트럼스틱 Strumstick |

메트로놈 소리와 오르간은 지금도 브라우저에서 직접 합성합니다. 녹음 파일을 받기 전이나 받지 못할 때도 합성음으로 대신 소리가 납니다.

The metronome and the organ are still synthesized in the browser. Synthesized voices also play until the recordings load, or if they cannot load.
