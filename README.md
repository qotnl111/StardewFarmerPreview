# 🧑‍🌾 Stardew Farmer Previewer

> **[🌐 Try Live Web Version (웹에서 바로 실행하기)](https://qotnl111.github.io/StardewFarmerPreview/)**

A lightweight, standalone web-based previewer for Stardew Valley farmer sprites and textures. Test your custom outfits, hairs, and body textures across all 58 in-game animations without launching the game.

스타듀밸리 파머(플레이어) 리텍스쳐 제작자를 위한 단일 HTML 웹 프리뷰어입니다. 게임을 켜지 않고도 브라우저에서 58종의 모션과 도트 1픽셀의 어긋남을 즉시 검수할 수 있습니다.

- **Version**: `v1.1.0`
- **Supported Languages**: English, 한국어, 中文, 日本語

---

## English

### 1. Purpose
- **Eliminate In-Game Testing Friction**: No need to launch Stardew Valley, move around, or swing tools repeatedly just to check a minor 1-pixel change on a custom shirt, hair, or skin.
- **Instant Pixel Alignment & Defect Checking**: Quickly spot misaligned pixels across 58 movement, tool, combat, and emote animations with 2x to 10x crisp pixel zoom.
- **Zero Installation & Standalone**: Runs completely offline in your browser (Chrome, Edge, Whale, Firefox) as a single HTML file with no dependencies or build steps.

### 2. Key Features
- **Accurate Layering Engine**: Faithfully replicates vanilla drawing order (`Body Base` $\rightarrow$ `Pants` $\rightarrow$ `Shirts` $\rightarrow$ `Eyes` $\rightarrow$ `Hair`).
- **Real-Time Hair X/Y Offset Nudge & Copy**: Fine-tune hair position in real-time (+/- buttons or `Shift + Arrow keys`) and copy config values (e.g. `[1, 0]`) with 1-click—ideal for *Sprite Sheet Extender* custom poses!
- **Auto HD Texture Scaling**: Automatically detects high-resolution farmer base sprite sheets (2x, 4x, etc.).
- **Custom Texture Drag & Drop**: Simply drag and drop your custom `farmer_base.png`, `hairstyles.png`, `shirts.png`, or `pants.png` onto the previewer.
- **58 Complete Animations**: Walking, running, tool swinging, watering, fishing (casting/reeling), weapon attacks, harvesting, eating, emotes, and more.
- **Pixel Art Toolset**:
  - 2x ~ 10x crisp Nearest-Neighbor scaling
  - Frame-by-frame stepping & pause controls
  - Speed adjustment (0.25x slow motion to 2.0x)
  - Checkerboard, solid color, and chroma-key backgrounds
  - 16x32 / 16x16 pixel grid toggles
  - Live Sprite Sheet tracker with bounding box
- **Real-Time 4-Language UI (i18n)**: Seamless instant switching between English, 한국어, 中文, and 日本語.

---

## 한국어

### 1. 제작 목적
- **인게임 리텍스쳐 검수 피로도 해소**: 셔츠, 바지, 헤어의 1픽셀 수정을 확인할 때마다 게임을 실행하고 도구를 휘두르는 번거로움을 완전히 없앴습니다.
- **도트 정렬 및 모션 결함 조기 발견**: 걷기, 달리기, 낚시, 물주기, 도구 스윙, 전투 등 58가지 동작에서 도트가 어긋나지 않는지 2x~10x 고배율로 즉각 검수할 수 있습니다.
- **완전 무설치 단일 파일 & 로컬 구동**: 복잡한 설치나 서버 없이 `.html` 파일 하나만 더블 클릭하면 오프라인에서도 즉시 작동합니다.

### 2. 주요 기능
- **완벽한 레이어 합성 엔진**: 바닐라 스타듀밸리의 드로잉 순서(`신체 베이스` $\rightarrow$ `바지` $\rightarrow$ `셔츠` $\rightarrow$ `눈동자` $\rightarrow$ `헤어`)를 충실히 구현.
- **실시간 헤어 X/Y 오프셋 미세조정 & 원클릭 복사**: `+/-` 버튼 및 `Shift + 방향키`로 헤어 위치를 1px 단위로 실시간 조정하고, 설정값(`[1, 0]`)을 원클릭 복사 (*Sprite Sheet Extender* 등 커스텀 포즈 모드 완벽 대응).
- **고해상도 HD 텍스처 배율 자동 감지**: 2x, 4x 등 고해상도 HD 베이스 시트 자동 지원.
- **커스텀 파일 드래그 앤 드롭**: 제작 중인 `farmer_base.png`, `hairstyles.png`, `shirts.png`, `pants.png` 이미지를 드래그하여 즉시 테스트.
- **58종 전방향 모션 완벽 수록**: 기본 이동, 도구 사용, 물주기, 낚시(캐스팅/입질/릴), 무기 공격, 수확, 먹기/마시기, 감정표현 등.
- **정밀 검수 도구 세트**:
  - 2x ~ 10x 픽셀 확대 (Nearest-Neighbor)
  - 프레임 단위 넘기기 및 일시정지 제어
  - 재생 속도 조절 (0.25x 슬로우 모션 ~ 2.0x)
  - 투명 체크무늬, 단색, 크로마키 배경 전환
  - 16x32 / 16x16 픽셀 그리드 격자 토글
  - 실시간 스프라이트 시트 위치 트래커
- **4개 국어 실시간 전환 (i18n)**: 영어, 한국어, 중국어, 일본어 실시간 즉각 변경 지원.
