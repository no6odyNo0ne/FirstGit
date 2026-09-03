# 🎮 My Game Development Portfolio

안녕하세요! 직접 제작하고 출시한 게임 프로젝트들을 모아둔 리포지토리입니다.  
각 프로젝트의 소개, 핵심 기능 및 플레이 방법을 확인하실 수 있습니다.

---

## 📌 목차 (Table of Contents)
- [✨ 대표 프로젝트 (Featured Games)](#-대표-프로젝트-featured-games)
- [🛠 사용 언어 및 개발 툴 (Tech Stack)](#-사용-언어-및-개발-툴-tech-stack)
- [🚀 게임 리포지토리 게시 가이드 (Publishing Guide)](#-게임-리포지토리-게시-가이드-publishing-guide)

---

## ✨ 대표 프로젝트 (Featured Games)

### 1. 🕹️ [게임 1 이름]
> **한 줄 소개:** 게임의 핵심 컨셉이나 한 줄 요약을 적어주세요.

![게임 스크린샷 또는 GIF](https://via.placeholder.com/600x300?text=Game+Screenshot+1)

* **장르:** 2D 플랫포머 / 3D 액션 / 퍼즐 등
* **개발 기간:** 202X.00 ~ 202X.00
* **사용 기술:** Unity, C#, Aseprite
* **주요 특징:**
  * 특징 1 (예: 물리 엔진을 활용한 액션)
  * 특징 2 (예: 보스전 패턴 설계)
* **링크:** [🎮 플레이하기 / 다운로드](https://github.com/your-username/game-repo-1) | [📄 상세 README 읽기](./game-1-folder)

---

### 2. 🕹️ [게임 2 이름]
> **한 줄 소개:** 게임의 핵심 컨셉이나 한 줄 요약을 적어주세요.

![게임 스크린샷 또는 GIF](https://via.placeholder.com/600x300?text=Game+Screenshot+2)

* **장르:** Rhythym / RPG / Casual 등
* **개발 기간:** 202X.00 ~ 202X.00
* **사용 기술:** Unreal Engine 5, C++, Blueprints
* **주요 특징:**
  * 특징 1
  * 특징 2
* **링크:** [🎮 플레이하기 / 다운로드](https://github.com/your-username/game-repo-2)

---

## 🛠 사용 언어 및 개발 툴 (Tech Stack)

| 구분 | 엔진 및 언어 / 도구 |
| :--- | :--- |
| **Game Engine** | Unity, Unreal Engine, Godot |
| **Languages** | C#, C++, Python |
| **Graphics & Audio** | Photoshop, Aseprite, Blender, Audacity |
| **VCS & Project** | Git, GitHub, Trello |

---

## 🚀 게임 리포지토리 게시 가이드 (Publishing Guide)

깃허브에 게임 프로젝트를 깔끔하고 체계적으로 게시하는 표준 방법입니다.

### 1. `.gitignore` 설정 필수
용량이 큰 바이너리 파일이나 빌드 임시 파일(예: Unity의 `Library/`, `Temp/`, Unreal의 `Intermediate/`)이 깃허브에 올라가지 않도록 설정합니다.
* Repository 생성 시 **Add .gitignore**에서 본인이 사용하는 엔진(`Unity`, `UnrealEngine` 등)을 선택하세요.

### 2. Git LFS (Large File Storage) 활용
게임 소스 코드 외에 대용량 텍스트, 에셋, 에디터 파일(PSD, FBX, WAV 등)이 있을 경우 Git LFS를 설정해야 용량 제한 오류를 방지할 수 있습니다.
```bash
# Git LFS 설치 및 초기화
git lfs install

# 대용량 파일 확장자 추적 등록
git lfs track "*.psd"
git lfs track "*.fbx"
git lfs track "*.wav"