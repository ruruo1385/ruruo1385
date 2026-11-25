## 👋 안녕하세요, 온디바이스 AI SW 개발자를 준비하는 엄태웅입니다

Jetson에서 카메라 영상으로 제품 품질을 판정하고, STM32로 컨베이어와 분류 장치를 제어하는 프로젝트를 진행했습니다. 카메라의 판정 결과가 장치 제어와 데이터 기록으로 이어지는 과정에 관심이 있습니다.

- **관심 분야** — 임베디드 리눅스 및 소프트웨어 개발, 엣지 비전 추론, 펌웨어, bsp

### 🛠 기술 스택

| 분야 | 사용 기술 |
| --- | --- |
| 엣지 비전 | Python · OpenCV · Ultralytics YOLO · NVIDIA Jetson |
| 임베디드 | C · STM32F411RE · STM32 HAL · UART |
| 통신·데이터 | TCP 소켓 · MySQL |
| 데스크톱 GUI | PySide6 , Qt|
| 개발 도구 | Git · CMake |
| 프론트엔드 | Svelte · React.js |
| 백엔드 | express.js | 
### 🧠 프로젝트

| 프로젝트 | 내용 | 기술 |
| --- | --- | --- |
|[Project DriveKind](https://github.com/TeamProto501/DriveKind-Frontend) | svelte를 이용한 dashboard 풀스택 웹 애플리케이션 | svelte |
|[Project DriveKind](https://github.com/TeamProto501/DriveKind-API) | express.js 및 supabase를 이용한 백엔드 api | express.js · supabase |
|[레이저 타겟 트래킹 모듈](https://github.com/tuna1025/kccistc_Embedded_TeamProject)| STM32 f411RE 보드를 이용하여 조도 센서의 수치에 따라 부저를 울리는 타겟을 제작. | STM32 · C|
| [Jetson·STM32 컨베이어 품질 검사](https://github.com/ruruo1385/kccistc_jetson_stm_project) | 카메라 영상으로 지우개의 품질을 판정하고, 결과에 따라 컨베이어와 서보를 제어해 제품을 분류하는 팀 프로젝트. 검사 결과는 MySQL에 기록합니다. | Jetson · YOLO · OpenCV · STM32 · C · MySQL |
| [MoviePosterQuiz](https://github.com/ruruo1385/mini_proj_one) | 포스터의 일부 조각을 보고 영화 제목을 맞히는 데스크톱 게임. 난이도에 따라 조각 크기가 달라지며, 문항별 제한 시간과 힌트가 있습니다. | Python · PySide6 |

### 📚 실습 기록

- [C_basic](https://github.com/ruruo1385/C_basic) — 포인터, 비트 연산과 Win32 UART 통신을 다룬 C 실습
- [codingPrac](https://github.com/ruruo1385/codingPrac) — Python과 Java로 풀이한 프로그래머스 문제 기록
