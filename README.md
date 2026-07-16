# 이지용 프로젝트 설명서 — 전체 목차

GitHub 저장소 두 곳에 들어 있는 **모든 프로젝트의 설명서 색인**이다.
프로젝트마다 **폴더별로 설명서가 따로** 있고, 각 설명서는 **`1챕터.md`, `2챕터.md` …**
파일로 나뉘어 그 프로젝트의 **코드 구조를 교과서처럼** 풀어 놓았다.

**[🌐 웹 서버 + DB 연동 기초](웹서버%20DB%20연동%20기초/README.md)만 성격이 다르다** —
기존 코드 해설이 아니라 **새로 만든 학습 실습**이고, **실제로 돌아가는 코드 3벌**이 들어 있다.

---

## 📚 프로젝트별 설명서

| 프로젝트 | 무엇인가 | 챕터 | 설명서 |
|---|---|---|---|
| 🤖 **광명테크 제스처 인식** | 키오스크를 손짓으로 조작 (MediaPipe + RTMPose) | **15챕터** | [광명테크/](광명테크/README.md) |
| 📦 **라즈베리파이 객체인식** | 박스 크기·불량 판정 → 아두이노 분류 | **15챕터** | [2025 2학기 라즈베리파이 객체인식 아두이노 분류 동장/](2025%202학기%20라즈베리파이%20객체인식%20아두이노%20분류%20동장/README.md) |
| 🦾 **젯슨 나노 + 르로봇** | 듀얼 카메라 + TensorRT + 로봇팔 (캡스톤 최종) | **15챕터** | [2026 1학기 젯슨나노 객체인식 분류+르로봇/](2026%201학기%20젯슨나노%20객체인식%20분류+르로봇/README.md) |
| 🏥 **메디컬 머신러닝 대회** | ICU 위험도·수술시간 예측 + SHAP 설명 | **15챕터** | [메디컬 머신러닝 대회/](메디컬%20머신러닝%20대회/README.md) |
| 💻 **개인 프로젝트** | **하위 프로젝트 6개** — 각각 따로 ↓ | **59챕터** | [개인 프로젝트/](개인%20프로젝트/README.md) |
| 🌐 **웹 서버 + DB 연동 기초** | **새로 만든 학습 실습** — 돌아가는 코드 3벌 포함 | **15챕터** | [웹서버 DB 연동 기초/](웹서버%20DB%20연동%20기초/README.md) |

### 💻 개인 프로젝트 — 하위 6개

| 프로젝트 | 무엇인가 | 챕터 | 설명서 |
|---|---|---|---|
| 🧹 고클린 alpha.ver | Windows 최적화 GUI (**대표작**) | **15챕터** | [개인 프로젝트/project고클린_alpha.ver/](개인%20프로젝트/project고클린_alpha.ver/README.md) |
| ⌨️ 고클린 초기.ver | 같은 도구의 **배치 원형** | **8챕터** | [개인 프로젝트/project고클린_초기.ver/](개인%20프로젝트/project고클린_초기.ver/README.md) |
| 📚 Express 지역 도서관 | MDN 튜토리얼 (2020, **미완성**) | **10챕터** | [개인 프로젝트/2020_express-locallibrary-tutorial/](개인%20프로젝트/2020_express-locallibrary-tutorial/README.md) |
| 🗄️ ASP + Access DB | 클래식 ASP CRUD (2024) | **10챕터** | [개인 프로젝트/2024년 2학기ASP_DB연동/](개인%20프로젝트/2024년%202학기ASP_DB연동/README.md) |
| 🌐 XAMPP 웹 자기소개서 | HTML/CSS (**15점 만점**) | **8챕터** | [개인 프로젝트/xampp 웹 자기소개서 간단하게/](개인%20프로젝트/xampp%20웹%20자기소개서%20간단하게/README.md) |
| 📷 임베디드 리눅스 | 바디캠 + 배달 감지 (2024) | **8챕터** | [개인 프로젝트/2024년 2학기 임베디드 연습/](개인%20프로젝트/2024년%202학기%20임베디드%20연습/README.md) |

**총 134챕터**

---

## 두 저장소의 관계 (가장 먼저 알아야 할 것)

| | **저장소 1** | **저장소 2** |
|---|---|---|
| 주소 | `github.com/kakabab12/My_project` | `github.com/gmt-internship-2026/yong` |
| 성격 | **개인 포트폴리오 모노레포** | **광명테크 인턴십 제출용** |
| 브랜치 | `main` | `main` |
| 파일 수 | **6,852개** | **35개** |
| 커밋 | 7개 (2026-06-28 ~ 07-16) | 2개 (2026-07-13 ~ 07-15) |
| 프로젝트 | **5개** | **1개** (`광명테크/gesture_model`) |

### ⚠ 두 저장소는 `광명테크/gesture_model`이 겹친다 — 그리고 같지 않다

| | 저장소 1의 광명테크 | 저장소 2의 광명테크 |
|---|---|---|
| 날짜 | 2026-07-13 | **2026-07-15 (최신)** |
| 제스처 | 4종 (`move_left`/`move_right`/`select`/`go_home`) | **1종** (`next_item`) |
| 판정 | 손가락 폄·핀치 거리 | **손등 방향(외적 부호)** |
| 추가 파일 | — | 자체 학습 분류기 가중치 3개 |

> **광명테크 작업을 볼 때는 저장소 2를 봐야 한다.** 저장소 1의 광명테크 폴더는
> 이틀 전 스냅샷이라 낡았다. → [광명테크/README.md](광명테크/README.md)

---

## 🗺 저장소 1 전체 지도

```
My_project/
├── 2025 2학기 라즈베리파이 객체인식 아두이노 분류 동장/   572개
├── 2026 1학기 젯슨나노 객체인식 분류+르로봇/            416개  (376개가 lerobot 라이브러리)
├── 메디컬 머신러닝 대회/                                58개
├── 개인 프로젝트/                                    5,773개  (5,676개가 node_modules)
└── 광명테크/                                           32개  ← 저장소 2가 최신
```

> **파일 수에 속지 말 것.** 6,852개 중 **6,052개가 남의 코드(node_modules + lerobot)**이거나
> 데이터셋 이미지다. 실제로 읽을 본인 코드는 **200개 남짓**이다.

### 프로젝트 계보 — 하나의 흐름이 있다

```
2020  Express 도서관 (학교)
2024  ASP + Access (학교)
2024  임베디드 — 배달 감지 카메라 (주야간 검증)   ← 비전의 시작
2025  XAMPP 웹 자기소개서 (학교)
2025  라즈베리파이 — YOLO + 아두이노 분류         ← 엣지 AI
2026  젯슨 나노 — TensorRT + 듀얼카메라 + 로봇팔  ← 캡스톤
2026  메디컬 ML 대회 — LightGBM + SHAP           ← 정형 데이터 AI
2026  광명테크 인턴십 — 제스처 인식              ← 현재
      + 고클린 (개인, 배치 → GUI → exe)
```

---

## 🚀 공통 준비 — 저장소 받기

### ⚠ 저장소 1은 Windows에서 그냥 클론하면 **실패한다**

실제로 확인한 에러다:

```
error: unable to create file 2025 2학기 라즈베리파이 .../frame_0001_jpg.rf.9de610c3....jpg: Filename too long
fatal: unable to checkout working tree
warning: Clone succeeded, but checkout failed.
```

**원인**: Windows의 260자 경로 제한(MAX_PATH). 한글 폴더명이 길고
(`2025 2학기 라즈베리파이 객체인식 아두이노 분류 동장`) 그 아래 Roboflow가 만든
긴 해시 파일명이 깊게 들어가 있다. 가장 긴 경로는 **176자**지만 내려받는 위치
(`C:\Users\...\Desktop\...`)가 더해지면 한도를 넘는다.

**해결 — 클론 전에 반드시 실행:**

```bash
git config --global core.longpaths true
```

그다음 클론:

```bash
git clone https://github.com/kakabab12/My_project.git
git clone https://github.com/gmt-internship-2026/yong.git
```

> 이 설정으로 **모든 파일이 정상 체크아웃**되는 것을 확인했다.
>
> **이미 실패한 상태로 클론했다면** 폴더를 지우지 말고:
> ```bash
> cd My_project
> git config core.longpaths true
> git restore --source=HEAD :/
> ```
>
> 그래도 안 되면 Windows 자체 제한을 푼다 (관리자 PowerShell):
> ```powershell
> New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" `
>   -Name LongPathsEnabled -Value 1 -PropertyType DWORD -Force
> ```
>
> **저장소 2는 35개 파일뿐이라 이 문제가 없다.**

---

## 📥 저장소에 **없는** 것 — 직접 구해야 하는 파일

`.gitignore`로 일부러 뺀 파일이 있다. 이걸 모르면 "파일 없음" 에러로 막힌다.

저장소 1 루트 `.gitignore`:

```
yolov8_cls_env/    venv/    __pycache__/    *.pyc    .DS_Store    .venv/
*.csv     ← 메디컬 대회 원본 데이터가 통째로 빠진 이유
*.zip     *.sh     *.dll
```

| 없는 것 | 필요한 곳 | 구하는 법 |
|---|---|---|
| `operations.csv`, `diagnosis.csv`, `labs.csv`, `ward_vitals.csv` | 메디컬 학습 | PhysioNet **INSPIRE 1.3** 신청·다운로드 |
| `hand_landmarker.task` (7.8MB) | 광명테크 실행 | [Google 공식 URL](https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task) |
| RTMPose 포즈 모델 (~40MB) | 광명테크 실행 | 첫 실행 시 `rtmlib`이 **자동 다운로드** |
| ACT 체크포인트 (80,000 스텝) | 젯슨 르로봇 | 저장소에 없음 — 직접 학습 필요 |
| 박스 세그멘테이션 **데이터셋** | 라즈베리파이 재학습 | 저장소에 없음 (모델 `.onnx`만 있음) |

---

## ⚡ 빠른 시작 — 지금 당장 되는 것 3개

하드웨어나 빠진 파일 없이 **바로 실행되는 것**:

| 프로젝트 | 명령 | 결과 |
|---|---|---|
| 🏥 **메디컬 서버** | `cd "메디컬 머신러닝 대회/AI"` → `py server.py` | http://localhost:5000 |
| 💻 **고클린 GUI** | `cd "개인 프로젝트/project고클린_alpha.ver"` → `py alpha_test1.py` | 창이 뜸 (UAC 정상) |
| 🤖 **제스처 테스트** | `cd 광명테크/gesture_model` → `py -m unittest discover tests -v` | **36건 통과** |

나머지는 하드웨어(라즈베리파이·젯슨·아두이노·로봇팔)나 위의 빠진 파일이 필요하다.

> **`python`이 아니라 `py`를 쓴 이유**: 이 PC에서 `python`은 Microsoft Store 스텁이라
> 아무것도 하지 않는다. 실제 파이썬은 **`py` 런처**(3.13)로 실행된다.

---

## 📋 전체 실행 요약표

| 프로젝트 | 실행 명령 | 포트 | 바로 되나 |
|---|---|---|---|
| 광명테크 제스처 데모 | `py scripts/run_demo.py` | — | ⚠ 모델 다운로드 필요 |
| 광명테크 테스트 | `py -m unittest discover tests -v` | — | ✅ |
| 라즈베리파이 서버 | `py sucess.py` | 5000 | ⚠ **모델 경로 수정 필요** |
| 라즈베리파이 GPU판 | `py app_ck.py` | 5000 | ⚠ 카메라 없어도 뜸 |
| YOLO 학습 (견과류) | `py train.py` | — | ⚠ GPU 필요 |
| 젯슨 메인 서버 | `py jetson_USB2.py` | 5000 | ⚠ **경로·API키·라벨맵 수정** |
| TensorRT 변환 | `py turnonnx.py` | — | ⚠ 젯슨에서만 |
| LeRobot ACT | `py act_floor1_test.py` | — | ❌ 체크포인트 없음 |
| 메디컬 서버 | `py server.py` | 5000 | ✅ |
| 메디컬 학습 | `py train.py` | — | ❌ CSV 필요 |
| 고클린 | `py alpha_test1.py` | — | ✅ |
| Express 도서관 | `npm install && npm start` | 3000 | ⚠ Node.js 필요 |

---

## 🔍 각 설명서에서 확인한 것들

문서만 읽어서는 알 수 없는, **코드와 모델 파일을 직접 열어 확인한 사실**들이다.
자세한 내용은 각 프로젝트 README에 있다.

| 프로젝트 | 발견 |
|---|---|
| **광명테크** | README가 `hand_landmarker.task`를 "이미 받아뒀다"고 하지만 **`.gitignore`에 걸려 git에 없다** |
| **광명테크** | README 표의 `flip_orientation` 기본값(`false`)이 **실제 config(`true`)와 반대** |
| **광명테크** | 커밋 제목의 "자체 학습 분류기"가 **실행 경로에 연결되어 있지 않다** (스크립트 2개만 import) |
| **광명테크** | `config.yaml`의 `max_infer_fps: 30`은 **코드에서 안 읽는 죽은 설정** |
| **라즈베리파이** | 코드 4개가 **없는 경로**(`yolov5/best.onnx`)를 참조 — 실제 파일은 `best.onnx` |
| **라즈베리파이** | 저장소의 데이터셋(**견과류 3종**)과 실제 배포 모델(**박스 6종 세그멘테이션**)이 무관 |
| **라즈베리파이** | `dataset.yaml`(`nc:1, box`)이 실제 모델(6클래스)과 **불일치하는 잔재 파일** |
| **젯슨** | **`BOX_LABEL_MAP`이 뒤집혀 있다** — 모델은 `0=big_box`인데 코드는 `0="small_box"` → **큰 박스가 소형 라인으로** |
| **젯슨** | 그 버그가 **언제 들어왔는지 계보로 추적됨** (`main1(9)` 맞음 → `USB` 라벨만 틀림 → `USB2` 동작까지 뒤집힘) |
| **젯슨** | `/home/user/project/` 하드코딩 + `CLAUDE_API_KEY` 플레이스홀더 |
| **메디컬** | `op_cutoff`(수술별 cutoff)를 **만들어 놓고 안 쓴다** — 환자별을 써서 재수술 환자에 누수 소지 |
| **메디컬** | 학습된 `.pkl`이 전부 커밋되어 있어 **CSV 없이도 서버가 뜬다** |
| **개인/임베디드** | **`.py`가 없는데 코드는 있다** — `.hwpx`(=ZIP) 안 보고서에 전문이 들어 있다 |
| **개인/Express** | **`Board`가 정의되지 않았다** — `/` 접속 시 500. 폴더명 `복구`가 유실 사건의 증거 |
| **개인/ASP** | **전 파일이 SQL 인젝션에 취약**. `<meta refresh 3초>`로 실시간 게시판 구현 |
| **개인/XAMPP** | **주석이 채점 기준표**. 이미지 5개·YouTube가 **실제로 깨져 있다** |
| **개인/고클린** | 초기.ver의 **게임 모드 Y/N 확인이 alpha.ver에서 사라졌다** |

---

## 📖 저장소에 원래 있는 설명 문서

본인이 직접 쓴 문서들이다. 각 README와 함께 읽으면 좋다.

| 문서 | 위치 |
|---|---|
| 라즈베리파이 파일별 요약 | `2025 2학기.../RPI-Flask-main/코드설명.md` |
| 라즈베리파이 초기판 요약 | `2025 2학기.../sub/코드설명,md` (쉼표는 오타) |
| 라즈베리파이 GPU판 요약 | `2025 2학기.../FastAPI_GPU버전-수정본/코드설명.md` |
| **젯슨 — Plan A/B 서사** | `2026 1학기.../코드설명.md` |
| 메디컬 파일별 요약 | `메디컬 머신러닝 대회/AI  폴더 코드 설명.md` (공백 2개) |
| 고클린 상세 | `개인 프로젝트/project고클린_alpha.ver/코드설명.md` |
| 고클린 배치판 | `개인 프로젝트/project고클린_초기.ver/코드설명.md` |
| 광명테크 사용 설명서 | `광명테크/gesture_model/README.md` |
