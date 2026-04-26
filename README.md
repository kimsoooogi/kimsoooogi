<div align="center">

```
██╗  ██╗██╗███╗   ███╗    ███████╗██╗   ██╗ ██████╗ ██╗
██║ ██╔╝██║████╗ ████║    ██╔════╝██║   ██║██╔════╝ ██║
█████╔╝ ██║██╔████╔██║    ███████╗██║   ██║██║  ███╗██║
██╔═██╗ ██║██║╚██╔╝██║    ╚════██║██║   ██║██║   ██║██║
██║  ██╗██║██║ ╚═╝ ██║    ███████║╚██████╔╝╚██████╔╝██║
╚═╝  ╚═╝╚═╝╚═╝     ╚═╝    ╚══════╝ ╚═════╝  ╚═════╝ ╚═╝
```

### 데이터로 사용자 경험을 바꾸는 AI 엔지니어, 김수기입니다.

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sg990926@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kimsoooogi)

</div>

---

## 🧠 About Me

```python
class KimSugi:
    def __init__(self):
        self.name       = "김수기 (Kim Su-gi)"
        self.education  = "상명대학교 휴먼지능정보공학과 (부전공: 문헌정보학)"
        self.experience = "신입"
        self.interests  = ["LLM 기반 시스템", "AI 파이프라인", "사용자 중심 개발"]

    def motto(self):
        return "개발 과정에서 항상 사용자의 입장을 생각합니다."
```

---

## 🛠 Tech Stack

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

**AI / ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![librosa](https://img.shields.io/badge/librosa-005571?style=flat-square&logoColor=white)

**Backend / DB**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Mobile / DevOps**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Projects

### 🎨 어조 대응형 AI 음성비서 서비스 [두부] `2024.03 ~ 2024.11`
> 사용자의 음성 톤(속삭임·일반·외침)을 실시간 분류하여 맞춤 응답하는 AI 음성비서

- 161차원 피처 엔지니어링(MFCC·Spectral Contrast·Tonnetz)으로 어조 분류 정확도 **94%** 달성
- `FastAPI` 비동기 파이프라인으로 Whisper(STT) → GPT-4(LLM) → TTS 간 지연 시간 **약 40% 단축**
- 공통 데이터 명세서 제작·배포로 2인 협업의 데이터 규격 오류 근절

`Python` `FastAPI` `Whisper` `GPT-4` `librosa` `Scikit-learn` `Flutter`

---

### 😴 운전자 생체 신호 기반 졸음운전 방지 시스템 `2026.04`
> MediaPipe 안면 랜드마크 기반 실시간 졸음 감지 엔진 (바이브 코딩)

- EAR / MAR / PERCLOS 지표를 결합한 3단계 상태 머신(AWAKE → DROWSY → SLEEPING)으로 **상태 판별 신뢰도 90%+** 확보
- 연속 프레임 윈도우 도입으로 단순 눈 깜빡임과 실제 졸음을 정교하게 구분, 오탐율 최적화
- 단위 테스트(Unit Test) 환경 구축으로 하드웨어 없이 로직 무결성 사전 검증

`Python` `MediaPipe` `OpenCV` `NumPy`

---

### 🚌 졸음운전 방지 시스템 기획 및 아키텍처 설계 `2024.04 ~ 2024.06` `팀 프로젝트`
> 특허 분석·시장 조사 기반 멀티모달 졸음운전 방지 서비스 기획

- 경찰청 통계(5년간 12,000건) 기반 타겟(버스 운전기사) 선정 및 페르소나 설계
- 특허 3종 분석으로 안면 특징 + 심박 결합 알고리즘 로직 수립
- 기존 기술(현대모비스 엠브레인) 벤치마킹 → 애프터마켓 설치형 + 핸들 진동 피드백 차별점 도출

`Market Research` `Patent Analysis` `System Architecture` `Documentation`

---

### 🤖 Transformer & Generative Models 딥러닝 구현 스터디 `2024.05 ~ 2024.06`
> 논문(Attention is All You Need) 기반 Transformer 풀구현 + 생성 모델 4종 비교 실험

- Positional Encoding · Multi-Head Attention · Encoder/Decoder 직접 구현 → 한국어 챗봇 학습
- AE → VAE → GAN → Stable Diffusion 순차 구현 및 생성 원리 비교 분석
- VAE 2D 잠재 공간 시각화로 표현 학습 원리 체득

`TensorFlow` `Keras` `PyTorch` `HuggingFace` `Google Colab`

---

## 📜 Certifications

| 자격증 | 취득일 |
|--------|--------|
| SQL 개발자 (SQLd) | 2025.06 |
| 데이터분석 준전문가 (ADsP) | 2025.11 |
| 컴퓨터활용능력 2급 | 2026.04 |
| 준사서 | 2025.02 |

---

<div align="center">

*"꾸준하게 책을 읽으며 항상 성장하려고 노력합니다."*

</div>
