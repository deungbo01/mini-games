# 🎮 미니게임천국 4.0 (HTML Mini-Games 4.0 Commercial Edition)

[![Play Live](https://img.shields.io/badge/PLAY_NOW-ONLINE-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white)](https://deungbo01.github.io/mini-games/)
[![Games Count](https://img.shields.io/badge/GAMES-38종_수록-10b981?style=for-the-badge)](https://deungbo01.github.io/mini-games/)
[![PWA Ready](https://img.shields.io/badge/PWA-100%25_OFFLINE-f59e0b?style=for-the-badge)](https://deungbo01.github.io/mini-games/)
[![License](https://img.shields.io/badge/LICENSE-MIT-64748b?style=for-the-badge)](LICENSE)

> **지뢰찾기, 2048, 블록블라스트, 수박게임, 타워 디펜스 등 38종의 아케이드·퍼즐·전략·스포츠 미니게임을 외부 라이브러리(Zero-Dependency) 없이 단일 HTML 패키지로 완성한 상용급 웹 아케이드 포털입니다.**

👉 **[🌐 지금 웹에서 바로 플레이하기](https://deungbo01.github.io/mini-games/)**  
*(스마트폰, 태블릿, PC 어디서든 브라우저만 열면 즉시 설치 없이 실행됩니다.)*

---

## 🕹️ 수록된 38종 미니게임 목록

| 카테고리 | 수록 게임 목록 |
| :--- | :--- |
| **퍼즐 & 두뇌** | 지뢰찾기 (클래식/커스텀), 2048, 블록블라스트, 스도쿠, 노노그램(네모로직), 소코반, 하노이탑, 사과게임, 색채 일치, 파이프 연결, 라이츠 아웃, 슬라이딩 퍼즐, 한붓그리기, 레이저 반사 |
| **액션 & 아케이드** | 스와이프 벽돌깨기, 스네이크, 수박 합치기, 원버튼 점프 러너, 버블 슈터, 세로 슈팅(무한 오버드라이브), 핀볼(피버 잭팟), 미로 추격, 타워 쌓기, 두더지 리액션, 낚시 타이밍 |
| **보드 & 추리** | 솔리테어(클론다이크), 오목, 오셀로, 체커, 숨은 함대(해전), 숫자야구, 주사위 야찌 |
| **전략 & 디펜스** | 미니 타워 디펜스 (22웨이브, 3단계 전직 타워, 속성 상성) |
| **스포츠 & 리듬** | 에어하키, 미니골프, 주차 탈출, 리듬 네온, 기억력 카드 |

---

## ✨ 4.0 상용 에디션 핵심 특징 (Key Features)

- **🪙 통합 메타 경제 & 아케이드 상점 (`ArcadeEconomy`)**
  - 38개 게임 플레이, 일일 챌린지, 58종 업적 달성을 통해 **아케이드 골드(`G`)**를 획득합니다.
  - 상점에서 **글로벌 테마 4종**(`사이버 네온`, `게임보이 1989`, `로열 골드`, `미드나잇 OLED`)과 **인게임 스킨 4종**(`레이저 지뢰`, `드래곤 스네이크`, `사이버 닌자`, `골든 카드 덱`), 프로필 칭호를 해금하고 즉시 장착할 수 있습니다.
- **🎨 플랫폼 비종속 벡터 그래픽 (`ArcadeSprites`)**
  - OS(Windows/iOS/Android/macOS)별로 깨지던 기본 폰트 이모지를 전면 탈피하고, 순수 **인라인 SVG 및 Canvas 2D 벡터 스프라이트**로 구현하여 어떤 기기에서도 칼 같은 선명도와 일관된 아트 룩을 제공합니다.
- **🎵 프로시저럴 실시간 합성 BGM & 오디오 마스터링**
  - 외부 MP3 음원 파일 없이 Web Audio API로 실시간 연주되는 **4종 테마 BGM**(`Lo-Fi`, `Synthwave`, `Chiptune`, `Jazz`) 내장.
  - 효과음 발생 시 BGM 볼륨이 부드럽게 줄어드는 **사이드체인 덕킹(Ducking)** 및 귀의 피로도를 줄여주는 **5.2kHz Lowpass Biquad Filter + Dynamics Compressor** 마스터링 체인 적용.
- **🏆 가상 리더보드 & SNS 1200×630 스코어카드**
  - 정교하게 시뮬레이션된 50인 글로벌 AI 래더와 티어 경쟁 (Bronze ~ Champion).
  - 클리어 기록을 1200×630 고해상도 인증 이미지 카드로 생성해 원클릭 복사/공유 가능.
- **💾 JSON 세이브 데이터 백업 & 복원**
  - 로컬 스토리지에 저장된 모든 기록, 골드, 상점 구매 내역, 58종 업적을 단 하나의 JSON 파일로 백업하고 언제든 다른 기기로 복원 가능.
- **📲 100% 오프라인 PWA (Progressive Web App)**
  - 브라우저 메뉴에서 **'홈 화면에 추가'** 또는 **'앱 설치'**를 누르면 인터넷 연결이 끊긴 비행기나 지하철에서도 앱처럼 전체 화면으로 완벽 구동됩니다.

---

## 🚀 플레이 방법

### 1. 웹 브라우저에서 바로 플레이
아래 공식 GitHub Pages 링크를 클릭하면 브라우저에서 바로 실행됩니다:  
👉 **https://deungbo01.github.io/mini-games/**

### 2. 내 컴퓨터에서 오프라인으로 실행
별도의 웹 서버나 설치 과정 없이 저장소의 `minesweeper.html` (또는 `index.html`) 파일을 더블클릭하여 브라우저로 열면 됩니다.

---

## 📦 파일 구성

| 파일명 | 설명 |
| :--- | :--- |
| `index.html` | GitHub Pages 루트 접속 시 게임 본체로 즉시 연결해 주는 엔트리 포인트 |
| `minesweeper.html` | 38종 게임 엔진, BGM 신디사이저, 상점, 벡터 스프라이트가 모두 담긴 0-Dependency 핵심 파일 |
| `manifest.webmanifest` | 모바일/PC PWA 앱 설치 설정 파일 |
| `sw.js` | 100% 오프라인 캐싱 및 빠른 로딩을 지원하는 Service Worker |
| `icon-192.png` / `icon-512.png` | 고해상도 PWA 앱 아이콘 |
