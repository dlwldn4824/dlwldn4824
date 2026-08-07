# 이지우 | Lee-Jiwoo

> AI가 답을 던지는 시대에 <strong>왜?</strong>를 묻는 개발자  
> 광운대학교 인공지능융합대학 정보융합학부 비주얼테크놀로지전공 · GPA **4.32 / 4.5**

## 👤 About Me

- 🎓 광운대학교 정보융합학부 재학 (2024.03~)
- 🛠 문제 정의 → 검증 → 제품화 → 회고 루프 · [@due_study_archive](https://www.instagram.com/due_study_archive/)
- 📬 Email: **dlwldn4824@naver.com** · GitHub: **[dlwldn4824](https://github.com/dlwldn4824)**

## 🛠️ Tech Stacks

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
</p>

## 🏆 주요 수상 · 프로젝트 연결

| 수상 | 시기 | 프로젝트 |
|------|------|----------|
| **소원 H.O.P.E 창의보조공학 경진대회 장려상** | 2026.07.22 | [또박또박](https://github.com/dlwldn4824/HOPE_organization) |
| **HUSS AI 경진대회 장려상** (본선 07.01–07.03) | 2026.07 | [또박또박](https://github.com/dlwldn4824/HOPE_organization) |
| **파이썬 SW 활용 경진대회 심화 우수상** | **2026.08.07** | [Smart Icheon Care](https://github.com/dlwldn4824/smart_icheon_care) |
| **지능형 로봇 컨소시엄 대상** | 2026.06.26 | [Smart Icheon Care](https://github.com/dlwldn4824/smart_icheon_care) |
| 마이크로모듈 초급 SS급 | 2025.12 | 지능형로봇사업단 |
| 매치업 심화과정 우수상 (실무보고서·포스터) | 2025.05.29 | 광운대 |
| Dean’s List | 2024.12 | 광운대 |
| 창업 동아리 경진대회 장려상 | 2024.12 | 광운대 |
| 글쓰기 대회 가작(산문) | 2024.05 | 광운대 |
| 성적 우수 장학금 | 2024.09 · 2025.06 · 2025.12 | 광운대 |

## 🚀 프로젝트

> 카테고리별. 각 행은 **문제 정의 → AI를 어디에 썼는지 → 수치로 무엇이 나아졌는지**.  
> `†` = 타 계정/조직 레포 **contributor**. 수치 없는 항목은 정직하게 범위만 적음.

### 제품 · 배포
| 시기 | 프로젝트 | 문제 | AI 활용 | 수치·개선 |
|------|----------|------|---------|-----------|
| 2026– | [PinTime](https://github.com/dlwldn4824/pintime) · [live](https://pintime.vercel.app) | 톡방마다 가능시간 재입력·확정 후 캘린더 재등록으로 **조율 핸드오프가 끊김** | LLM 없이 **규칙 에이전트**로 제약 파싱→후보→**사람 승인 후** 같은 저장소 캘린더 등록 (확정은 AI 단독 X) | 프로토타입 **라이브 배포**. KPI를 추천 수가 아니라 **확정·충돌·도구 전달**로 재정의 · **서비스화 진행 중** |
| 2025– | [band](https://github.com/dlwldn4824/band) · [Band-Info](https://github.com/dlwldn4824/Band-Info) | 공연 예약·체크인·셋리스트가 채널별로 흩어져 운영 비용↑ | AI 핵심 아님 — **운영 워크플로를 웹 제품**으로 닫음 | **커밋 320+** 주 기여자 · 동아리 **실사용** 단일 진입점 |

### AI · ML · CV · 음성
| 시기 | 프로젝트 | 문제 | AI 활용 | 수치·개선 |
|------|----------|------|---------|-----------|
| 2026 | [또박또박 (HOPE)](https://github.com/dlwldn4824/HOPE_organization) | 치료실 ~1% 시간 외 가정에 **객관 발음 피드백 공백** | STT 보정 한계를 피하고 **Wav2Vec2-CTC·음소 정렬·PCC/PER**로 ‘어떻게 발음했는지’ 평가 · 게임 UX | 문제검증(TF-IDF/LDA)→기능 매핑 · **소원 H.O.P.E 창의보조공학·HUSS AI 장려×2** · 팀장 · 임상 KPI는 후속 |
| 2026 | [Smart Icheon Care](https://github.com/dlwldn4824/smart_icheon_care) | 넓은 구역·소수 인력 → 전수 순찰 불가 · **탐지≠행정 확정** | YOLO11s+ByteTrack로 **존재 탐지** · Risk로 줄 세움 · OCR 보조 · **확정은 HITL** | A/B all **0.4913**>filtered · test **F1 0.591 / mAP50 0.439** · ~**15.7 FPS** · 컨소시엄 **대상** · 파이썬 SW **심화 우수상** |
| 2026 | † [WJVOX](https://github.com/KWwoojin/project) | 음성 학습·추론·공유 흐름이 제품 UI로 안 이어짐 | 음성 **infer 파이프라인**을 쓰는 프론트/UX 기여 | contributor · UI로 학습→infer→공유 동선 연결 |

### AI × 서비스 (금융 · 신뢰 · 보안)
| 시기 | 프로젝트 | 문제 | AI 활용 | 수치·개선 |
|------|----------|------|---------|-----------|
| 2026 | [답변등기](https://github.com/dlwldn4824/kb_AI_challenge) | AI 상담 초안 위험 vs 전건 사람승인 · **승인≠발송** 사고 | AI는 초안·위험 선별 · **봉인·발송은 결정론**(SHA256/HMAC) | 위험큐 **1,248→39 (3.1%)** · 합성 Recall@39 **81.3%** (실상담 25% 격차 공개) · 게이트 차단·재생 **100%** · vitest **60** |
| 2026 | † [iM Ready](https://github.com/ik-s/iM-Ready) / [iM-Shield](https://github.com/ik-s/iM-Shield) | 보이스피싱 피해↑ · 피해자 **65.3%** ‘판단 틈 박탈’ · 예방·사후 공백 | 모의훈련 + 골든타임에 **규칙/RAG 우선**(원본 미수집) | 사회지표·설문(1,195명) 근거로 제품 정의 · FE 핵심 기여 · 실금융 미연결 데모 |

### 로봇 · HCI (TEMI · CO-SHOW)
| 시기 | 프로젝트 | 문제 | AI 활용 | 수치·개선 |
|------|----------|------|---------|-----------|
| 2025 | [mobile_robot_temi](https://github.com/dlwldn4824/mobile_robot_temi) / † [mobile-robot](https://github.com/yyeonseoo/mobile-robot) | REST만으론 이동·촬영 **즉시성** 부족 · 모듈이 UX로 안 이어짐 | Socket.IO 실시간 명령 · (추천 등에) **Claude API** | **18존** 내비 · 현장 연동 · 팀 레포 기여 |
| 2025 | [TemiTellMe](https://github.com/dlwldn4824/TemiTellMe) / [HCI-UX](https://github.com/dlwldn4824/HCI-UX) 등 | 전시장 길·대기·콘텐츠가 흩어져 **방문 경험 단절** | WebView↔Temi SDK 브리지 · 이벤트 **추천(Claude)** | 현장 설문 **24명**(+Pilot/Post) · 8개 줄서기 프로그램 스케일 |

### 연구 · 교육 · 챌린지
| 시기 | 프로젝트 | 문제 | AI 활용 | 수치·개선 |
|------|----------|------|---------|-----------|
| 2026– | [NeSy-SMP-repro](https://github.com/dlwldn4824/NeSy-SMP-repro) | LLM만으론 부족한 **지식 제약·설명성** · 논문↔코드 간극 | Neuro-Symbolic(LTN·KG) **논문 재현·감사** (독자 신규연구 X) | Phase-3 gate/grounding 문서화 · **재현 진행 중** (완료 수치 미주장) |
| 2026– | [piching_machine](https://github.com/dlwldn4824/piching_machine) | 제구 성공을 감이 아니라 **확률·피처**로 설명·예측해야 함 | Form/Intent/Exec/Clutch 피처 + **CatBoost** 실험 루프 | holdout BSS **E20≈644.04** (E2 CatBoost **633.80** 대비↑) · **진행 중** |
| 2026 | [TM Multi-Agent](https://github.com/dlwldn4824/TM-MultiLayer-MentalHealth) / † [TM](https://github.com/yyeonseoo/TM) | 단일 LLM이 맥락·위험·생성·안전을 한 번에 → **실패 지점 비가시** | 역할 분리 Multi-Agent + RAG · **조건부 Safety Revision** | Three-Agent Safety **4.83** · Empathy **4.31** · Phase2 score **69.40** · Revision **~6%** |
| 2026 | [기계학습](https://github.com/dlwldn4824/machine_learning) | 디저트 소비를 감이 아니라 **상권 데이터**로 예측 | scikit-learn 등 **모델 비교·지표 선택** | 실데이터 기반 비교 실험 · 기계학습 **A+** 학기 산출물 |

### 전공 · 팀플 · 창업
| 시기 | 프로젝트 | 문제 | AI 활용 | 수치·개선 |
|------|----------|------|---------|-----------|
| 2025 | † [Cam-Kit](https://github.com/bhw119/Cam-Kit) | 캠퍼스 소분 구매의 가격·운영 마찰 | 서비스 기획 중심 (AI 핵심 X) · contributor | 기획상 편의점 대비 최대 **60%** 할인 지표 · 창업 경진 맥락 |
| 2025 | † [환불원정대](https://github.com/kw-ic-info/25-team-refund-ranger) | 환불·민원 뉴스 파편화 → 여론·토픽 탐색 어려움 | 키워드·감정·토픽 + **Gemini 챗봇「민심이」** | 팀장 · 이슈를 **시각화+대화형**으로 탐색하는 팀 산출물 |
| 2025 | [opensource_final](https://github.com/dlwldn4824/opensource_final) | 셋리스트를 감으로 짜는 비효율 | **규칙 기반** 추천 (552곡) · FastAPI/Docker | **552곡** 코퍼스 · 배포 가능한 API 형태 |
| 2024–25 | [창의설계·오픈소스 실습](https://github.com/dlwldn4824/creative_py_project) 등 | 수업 단위 구현·협업 연습 | 과제별 (CV/웹 기초 등) | 실습 레포 묶음 (`Open_Source_*` · `future_cv` · `9th_web`) |

## 💻 대외활동

### 진행 중
- **LG AIMERS 9기** (2026.07~) · Phase2 [piching_machine](https://github.com/dlwldn4824/piching_machine) — 투구 제구 성공 확률 · **진행 중**
- **광운대학교 대학혁신 서포터즈** (2025.06 ~ 현재) — 대학 프로그램 홍보·재학생 지원·멘토링

### 완료 · 수상
- **또박또박 (HOPE)** — 소원 H.O.P.E 창의보조공학 경진대회 장려상 (2026.07.22) · HUSS AI 경진대회 장려상 (본선 2026.07.01–07.03) · [레포](https://github.com/dlwldn4824/HOPE_organization)
- **Smart Icheon Care** — 파이썬 SW 활용 경진대회 **심화 우수상** (2026.08.07) · 지능형 로봇 컨소시엄 대상 (2026.06.26) · [레포](https://github.com/dlwldn4824/smart_icheon_care)

## 📚 교육 경력

### KT 희망나눔재단 랜선나눔캠퍼스
**2026.07 ~ 2026.09**
- 중3 대상 **AI 코디네이터** · 머신러닝 등 AI·데이터 교육
- 대학생 멘토로 중학생 AI 기초·실습 지도

### 에듀탑 온라인 화상과외
**2024.09 ~ 2025.12**
- 초·중·고 수학 · 약 10명 맞춤 지도·진도 관리

### 월계 채움학원
**2024.07 ~ 2025.12**
- 수학 조교 · 예비 고3 15~20명 풀이·상담 지원

### 개인 과외 (김과외 · 자란다 멘토)
**2023.08 ~ 2025.06**
- 초등 수학 · 고등 국·수 · 어린이집 영어 보육

## 📫 Contact

- Email : **dlwldn4824@naver.com**
- GitHub : **[github.com/dlwldn4824](https://github.com/dlwldn4824)**

---

# English Version

## About Me
- Visual Technology / Information Convergence, Kwangwoon University
- GPA 4.32 / 4.5 · Asks **why** before shipping AI answers

## Highlights
- Frames work as **problem → appropriate AI → measurable gain** (see Projects tables)
- **또박또박 (HOPE)** — home articulation feedback gap · phoneme eval · Sowon H.O.P.E creative assistive-tech + HUSS AI awards (team lead)
- **Smart Icheon Care** — detect≠confirm HITL · F1 0.591 / mAP50 0.439 · Python SW Advanced Excellence + Consortium Grand Prize
- **Answer Registry** — AI draft risk triage 1248→39 · deterministic seal/dispatch
- **TM Multi-Agent** — Three-Agent Safety 4.83 / Empathy 4.31 · conditional revision ~6%
- **PinTime** — rule agent closes schedule handoff · live prototype · productizing
- **Contributor:** iM-Ready · WJVOX · Cam-Kit · refund-ranger · mobile-robot

## Teaching
- KT Hope Sharing Foundation Online Campus — AI coordinator & ML for 9th graders (2026.07–09)
- EduTop online math tutoring (2024.09–2025.12)
- Wolgye Chaeum Academy TA (2024.07–2025.12)
- Private tutor / Jaranda mentor (2023.08–2025.06)

## Contact
- Email: dlwldn4824@naver.com
