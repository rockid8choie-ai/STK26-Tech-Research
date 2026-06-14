# STK26 Master Index

> `STK26-Tech-Research` 레포의 **레포지토리 수준 단일 진실 공급원(Source of Truth)**.
> Smart Tech Korea 2026 (2026-06-10 ~ 06-11) 컨퍼런스 노트 **25개 세션**을 개별 분석한 마스터 인덱스이며, 이후 모든 트렌드/분석 리포트의 기반 문서로 사용한다.
> 근거는 레포 내 컨퍼런스 자료만 사용. 수치는 발표자 주장 기반(독립 검증 권장). 표기 `S##` = 세션 ID.

- 세션 수: **25** · 테마 도메인: **9** · 식별 기업: 21곳(+미기재 2, 파일명 이슈 1)

---

# Executive Summary

Smart Tech Korea 2026의 25개 세션을 전수 인덱싱한 결과, 이 컨퍼런스는 **“AI를 공통 기반으로, 에이전트화·보안·하이브리드 세 힘이 동시에 작용하는 2026년 기술 지형”** 을 보여준다.

- **AI는 단일 트랙이 아니라 기반 레이어다.** 25개 중 다수 세션에 AI가 깔려 있으며, 그 위에서 ① 에이전트화(자율 실행, S01·S02·S05·S09·S23) ② 비전/VLM(공간·의미 이해, S03·S04·S22) ③ 보안 거버넌스로 분화된다.
- **보안이 가장 빈번한 횡단 주제(6세션).** 사이버 → 에이전트 행동권한(Mandate, S05) → 영상/출입(S19·S22) → 물리 봉인(S24) → 양자내성(S08)으로 외연이 확장됐다.
- **양자는 ‘이중 트랙 + 지금 대비’.** 컴퓨팅(S06·S07)과 보안(S08, S05의 PQC) 양쪽에 동시 등장. **PQC는 3세션 반복으로 최다 단일 세부기술**이다.
- **하이브리드가 지배적 설계 원칙.** 사람+AI 80:20(S01·S03·S05), GPU+QPU(S07), PQC+QKD(S08), AI+전문가(S03), 현실+가상 순환(S10).
- **최빈 비즈니스 문제 두 축:** (a) 수작업·휴먼에러 제거(7세션) (b) 신뢰·보안 확보(7세션). 전자가 자동화의 동기, 후자가 도입의 조건.
- **벤더 전략은 플랫폼·IP·생태계로 이동.** API/SDK 공급(S04), 통합 R&D 사업화(S15), 협력형 생태계·진출지원(S11~S13).

> 한 문장: 2026년은 “AI를 더 똑똑하게”가 아니라 **“AI를 자율 실행시키되 신뢰·보안·하이브리드로 길들이는”** 해다.

---

# Session Catalog

## A. 요약 카탈로그 (전 세션 일람)

| ID | 기업 | 카테고리 | 핵심 기술 | 주요 비즈니스 문제 |
|----|------|----------|-----------|--------------------|
| S01 | BI Matrix | AI/Agents | 의사결정 준비 자동화, Trinity Prism | 데이터 과잉, 의사결정 준비 과부하 |
| S02 | SK Shieldus·Check Point | AI/Agents | Agentic AI, 멀티에이전트, OWASP Agentic | 에이전트 권한↑ → 신규 보안위협 |
| S03 | (제조 솔루션사) | Manufacturing | XAI, 예지정비, SEF 4.0, 비전 QC | 블랙박스 AI·육안검사·현장안전 |
| S04 | Foresight Coop. | Robotics/Vision | 스테레오 비전, 3D 인식, API/SDK | 단일카메라·라이다비용·비정형환경 |
| S05 | 한국퀀텀컴퓨팅 | AI/Agents (Sec) | Mandate, 에이전트 인증, HSM, PQC | RBAC/장수명토큰의 에이전트 통제 불가 |
| S06 | AWS | Quantum | Amazon Braket, QPU, 하이브리드 | 양자 진입장벽·비용·ROI 불확실 |
| S07 | NORMA | Quantum | QML/최적화, Pado-Pauli(GPU+QPU) | 양자 비용·불안정·긴 학습시간 |
| S08 | ID Quantique | Quantum (Sec) | Q-Day, HNDL, PQC+QKD, QRNG | RSA/ECC 위협, 장기데이터 HNDL |
| S09 | BI Matrix | AI/Agents | SCM 멀티에이전트, 온톨로지, ReAct | SCM 복잡 의사결정·단순보고 한계 |
| S10 | Pollux | Logistics/PhysicalAI | Physical AI 파이프라인, 디지털트윈 | SI 의존·정보손실·공급망 변동성 |
| S11 | Quebec Delegation | Innovation Ecosystem | 협력형 혁신생태계 | 글로벌 공동R&D 파트너 확보 |
| S12 | Invest Québec | Innovation Ecosystem | AI허브(MILA)·클린에너지·인센티브 | 글로벌 기술기업·투자 유치 |
| S13 | Investissement Québec | Innovation Ecosystem | 북미진출 원스톱 지원 | 북미 진출 네트워크·시행착오 비용 |
| S14 | Creaform | Manufacturing | 3D 스캐닝, 역설계, AQC | 수작업 측정·인력부족·품질요구↑ |
| S15 | Luccia | Manufacturing | 포토닉스+AI, 레이저, 양자포토닉스 | R&D→산업가치 전환 |
| S16 | Mecademic | Robotics/Vision | 초소형 정밀로봇(5μm), 광학정렬 | 정밀자동화 비용·공간·장비종속 |
| S17 | Mecasys | Construction/Layout | Projected Reality, CAD/BIM 투영 | 건설 수작업 마킹·재작업·인력부족 |
| S18 | Mecasys | Construction/Layout | 레이저 프로젝션, 실시간 동기화 | 설계-시공 불일치·언어장벽 |
| S19 | (영상보안사) | Security/Surveillance | 클라우드 CCTV VMS, CSAP | CCTV 구축비·유지보수·글로벌 관제 |
| S20 | XBrush | Generative AI Media | AI 영상생성, 워터마크, 본인인증 | 얼굴업로드 악용·프라이버시 우려 |
| S21 | DevDive | Generative AI Media | 블록형 생성, 저작권, AX 교육 | AI 생성물 저작권·상업활용·보안 |
| S22 | Dexma | Security/Surveillance | VLM 영상분석, 안티스푸핑 | 얼굴인식 스푸핑·객체탐지 한계 |
| S23 | Uracle | AI/Agents | Athena(온프레미스, RAG, Workflow) | 보안민감 조직 AI 도입 데이터보안 |
| S24 | SWSP | Logistics/PhysicalAI | 보안봉인, Tamper Evidence, 추적성 | 의약품·고가품 운송 위변조·규제 |
| S25 | SWSP ⚠️ | Logistics/PhysicalAI | (영문) 보안봉인·추적성 포장 | (S24와 동일) |

> ⚠️ **S25 데이터 이슈:** 파일명 `Genetec_Unification_Physical_Security_Platform` ↔ 내용 SWSP(영문)로 **S24와 중복**, Genetec 실제 내용 누락(원본 측 오류). 빈도 집계 시 S24와 1개로 계상.

## B. 세션별 개별 분석 (Per-Session Detail)

### S01 — 기업용 AI·의사결정 준비 자동화
- **Company:** BI Matrix (배은영 팀장) · **Category:** AI/Agents (Enterprise AI)
- **Core Technologies:** 의사결정 준비 자동화 · Trinity Prism(DB 연결→테이블관계·컬럼의미·유의어→ERD 자동 생성)
- **Business Problem:** 데이터는 많아졌지만 의사결정 "준비"(조회·분석·정리·보고)가 업무시간 대부분 소모
- **Key Insights:** AI 성공=답변품질 아닌 업무 시간 단축(AX 본질) · 의사결정 "준비" 자동화(대행 아님) · 80:20 인간 검수 모델
- **Keywords:** `EnterpriseAI` `AX` `DecisionAutomation` `DataAnalytics` `HumanInTheLoop`

### S02 — 에이전트 AI 개념·구조·보안
- **Company:** SK Shieldus & Check Point · **Category:** AI/Agents (Security)
- **Core Technologies:** Agentic AI(Reasoning·Memory·Tool) · 멀티에이전트+오케스트레이션 · OWASP Agentic LLM Top 10
- **Business Problem:** 에이전트 자율성·권한↑ → 공급망·프롬프트인젝션·권한상승·메모리오염·정보유출
- **Key Insights:** 행동 권한 설정이 최우선 · 성능보다 권한관리·보안·거버넌스 선설계 · 간접 프롬프트 인젝션 방어 난이도 높음
- **Keywords:** `AgentAI` `MultiAgent` `Orchestration` `AISecurity` `OWASP` `PromptInjection`

### S03 — 제조 현장 설명가능 AI(XAI)·자율제조
- **Company:** (미기재 제조 AI 솔루션사) · **Category:** Manufacturing
- **Core Technologies:** XAI(근본원인·위치·시점·조치) · 예지정비(온도·자기장·3축진동, Azure) · SEF 4.0 안전(소프트웨어 LOTO·PLC/DCS) · 비전 품질검사
- **Business Problem:** 블랙박스 AI는 확률만 제시→활용 제한 · 육안검사 누락 · 작업자 안전
- **Key Insights:** 예측보다 "설명" · AI+전문가 협업 · 디지털 전환=지식(작업표준서·암묵지)의 디지털화
- **Keywords:** `XAI` `PredictiveMaintenance` `IndustrialSafety` `VisionInspection`

### S04 — 스테레오 비전 자율주행
- **Company:** Foresight Coop. · **Category:** Robotics/Vision
- **Core Technologies:** 스테레오 비전 · 3D 공간인식(100~150m, 주야간) · API/SDK·IP 공급 · 포트홀 탐지 · GPS-free 매핑
- **Business Problem:** 단일카메라 한계 · 라이다 비용 · 비정형(농기계·군수·건설) 환경
- **Key Insights:** 비전→공간인식으로 진화 · 자동차 넘어 드론·중장비·인프라 확장 · 하드웨어 아닌 플랫폼(API/SDK) 전략
- **Keywords:** `StereoVision` `3DPerception` `ADAS` `AutonomousDriving` `SDK`

### S05 — 에이전트 AI 인증·권한 관리(Mandate)
- **Company:** 한국퀀텀컴퓨팅 (오상근 부사장) · **Category:** AI/Agents (Security)
- **Core Technologies:** Mandate(행동허가증=최소권한) · 의도↔API 강결합 · HSM · 단기 자격증명 · Zero Trust(PDP/PAP) · PQC · 표준(Google AP2·FIDO·OpenID)
- **Business Problem:** 로그인·RBAC·장수명 토큰으로는 에이전트 세부행동 통제 불가
- **Key Insights:** 신원확인보다 행동 통제 · 장수명 토큰 위험 · Mandate=새 권한 단위 · HSM=마지막 방어선 · PQC 필수
- **Keywords:** `Mandate` `ZeroTrust` `HSM` `PQC` `AgentSecurity` `FIDO`

### S06 — Amazon Braket 클라우드 양자컴퓨팅
- **Company:** AWS (조상만) · **Category:** Quantum
- **Core Technologies:** 클라우드 양자컴퓨팅 · QPU(이온트랩·초전도·중성원자) · 시뮬레이터 · 하이브리드 워크플로우 · 사용량 과금 · Braket Direct · Quantum Embark
- **Business Problem:** 양자 진입장벽·고비용·ROI 불확실
- **Key Insights:** 클라우드로 접근성↑ · 실험·검증 단계 · 다양한 HW 비교 중요 · 하이브리드 현실적
- **Keywords:** `QuantumComputing` `AmazonBraket` `QPU` `HybridWorkflow` `Cloud`

### S07 — 양자컴퓨터 활용·Pado-Pauli
- **Company:** NORMA (정현철 대표) · **Category:** Quantum
- **Core Technologies:** QML vs 양자최적화 · Pado-Pauli(GPU 학습+QPU 샘플링) · 양자 클라우드 · PQC
- **Business Problem:** 양자 비용·상태 불안정·긴 학습시간·큐빗 확장 어려움
- **Key Insights:** 문제유형별 분화(QML/최적화) · AI가 진입장벽↓ · 단기 적용=신약·신소재·금융·최적화 · 하이브리드 현실적
- **Keywords:** `QML` `QuantumOptimization` `PadoPauli` `DrugDiscovery` `PQC`

### S08 — 하이브리드 양자보안
- **Company:** ID Quantique (IDQ, 엄상윤 대표) · **Category:** Quantum (Security)
- **Core Technologies:** Q-Day · HNDL · PQC+QKD 하이브리드(심층방어) · QRNG · 신뢰 인프라
- **Business Problem:** 양자컴퓨터가 RSA/ECC 위협, 장기보관 데이터 HNDL 노출
- **Key Insights:** 지금부터 대비 · PQC(알고리즘)+QKD(키분배) 보완관계 · 국가 양자보안망 시작(국가융합망·NQSN+)
- **Keywords:** `QuantumSecurity` `QDay` `HNDL` `PQC` `QKD` `QRNG`

### S09 — AI 에이전트 기반 SCM 최적화·온톨로지
- **Company:** BI Matrix (원유표 상무) · **Category:** AI/Agents
- **Core Technologies:** SCM 멀티에이전트(수요·공급·재고·생산·오케스트레이션) · 온톨로지(ODP 6패턴) · React 엔진(Plan·Think·Execute·Check)
- **Business Problem:** SCM 복잡 동시 의사결정 · 단순 보고의 한계
- **Key Insights:** AI=디지털 팀원("AI가 수행하는 SOP 회의") · 기술보다 비즈니스 문제 정의 먼저 · 온톨로지=업무구조 정리
- **Keywords:** `MultiAgent` `SCM` `Ontology` `ReActEngine`

### S10 — 물류센터 Physical AI 재설계
- **Company:** Pollux · **Category:** Logistics/Physical AI
- **Core Technologies:** Physical AI E2E 파이프라인 · 디지털트윈(NVIDIA Omniverse) · NOMOS(레이아웃) · Oper-V(실시간 재계획) · Ergon(데이터플랫폼) · Pinz(물리모델) · AI 코딩에이전트
- **Business Problem:** 외주 SI 의존→요구 왜곡·비용·지연 · 공급망 변동성
- **Key Insights:** 물류센터=지속 재설계 시스템 · 디지털트윈=운영 검증 플랫폼 · 예측보다 반응 속도
- **Keywords:** `PhysicalAI` `DigitalTwin` `Omniverse` `Logistics` `Simulation`

### S11 — 퀘벡 혁신 생태계
- **Company:** Quebec Government Delegation · **Category:** Innovation Ecosystem
- **Core Technologies:** 협력형 혁신생태계(정부·대학·기업·투자자) · 전략산업: AI·로보틱스·전동화·원격의료
- **Business Problem:** 글로벌 기술협력·공동 R&D 파트너 확보
- **Key Insights:** 지역홍보 아닌 "생태계 수출" · 한국=공동개발 파트너
- **Keywords:** `InnovationEcosystem` `Quebec` `AI` `Robotics` `R&D`

### S12 — 퀘벡 투자 생태계·인센티브
- **Company:** Invest Québec · **Category:** Innovation Ecosystem
- **Core Technologies:** AI 허브(MILA·Responsible AI) · 인재 · 게임(Ubisoft) · 클린테크 · 배터리 · Hydro-Québec(99.9% 청정) · 인센티브
- **Business Problem:** 글로벌 기술기업·투자 유치
- **Key Insights:** AI 국가전략화 · 친환경 전력=ESG 경쟁력 · 장기 R&D 파트너십
- **Keywords:** `Quebec` `MILA` `Cleantech` `Battery` `Investment`

### S13 — 북미 진출 원스톱 지원
- **Company:** Investissement Québec (조승현) · **Category:** Innovation Ecosystem
- **Core Technologies:** 원스톱 지원(타당성·부지·금융·네트워크·인재·수출)
- **Business Problem:** 북미 진출 초기 네트워크·시행착오 비용
- **Key Insights:** 투자유치 넘어 성장 전과정 지원 · 무료 · 해외 모기업도 동일 지원
- **Keywords:** `NorthAmericaExpansion` `OneStop` `Investment` `ExportSupport`

### S14 — 3D 스캐닝·자동화 품질검사
- **Company:** Creaform · **Category:** Manufacturing
- **Core Technologies:** 3D 스캐닝 · 역설계 · 품질검사(ISO 17025, ~20μm) · AQC(로봇+MetraSCAN, Fanuc/Yaskawa) · OLP · 턴키
- **Business Problem:** 수작업 측정 한계 · 인력 부족 · 품질 요구 증가
- **Key Insights:** 디지털전환=데이터 빠른 확보 · 3D 스캐닝=역설계·QC 기본 인프라 · 로봇+스캐너 결합
- **Keywords:** `3DScanning` `ReverseEngineering` `QualityControl` `AQC`

### S15 — 포토닉스 + AI 혁신
- **Company:** Luccia (CRIM+INO 통합) · **Category:** Manufacturing (Photonics)
- **Core Technologies:** 포토닉스/광학+AI · 레이저·광섬유·IR·테라헤르츠 · 통합/양자 포토닉스(TFLN) · Laser Engine 40 Mini
- **Business Problem:** R&D를 산업적 가치로 전환 · 복합문제 통합 해결
- **Key Insights:** 포토닉스+AI 융합 · 연구기관의 사업화 진화 · 광학=반도체·국방·우주 전략기술
- **Keywords:** `Photonics` `Laser` `AI` `QuantumPhotonics` `Semiconductor`

### S16 — 초소형 정밀 산업용 로봇
- **Company:** Mecademic · **Category:** Robotics/Vision
- **Core Technologies:** 초소형 고정밀 로봇(~5μm) · 광학 정렬 · Hexapod 대체(약 1/3 비용) · 시스템 통합 정밀 모듈
- **Business Problem:** 정밀 자동화 비용·공간 제약 · 전용장비 종속
- **Key Insights:** 로봇 소형화·정밀화 · 마이크로 자동화 수요↑ · 유연 로봇이 전용장비 대체
- **Keywords:** `PrecisionRobot` `OpticalAlignment` `MicroAutomation`

### S17 — Projected Reality 디지털 시공 레이아웃
- **Company:** Mecasys · **Category:** Construction/Digital Layout
- **Core Technologies:** Projected Reality · CAD/BIM 현장(벽·바닥·천장) 직접 투영
- **Business Problem:** 건설 수작업(줄자·먹줄·마킹)→휴먼에러·재작업·인력 부족
- **Key Insights:** 설계정보 현실 공간 구현→시공정확도·공정단축 · 마킹 대체
- **Keywords:** `ProjectedReality` `BIM` `ConstructionTech` `DigitalLayout`

### S18 — 레이저 프로젝션 시스템·글로벌 협업
- **Company:** Mecasys · **Category:** Construction/Digital Layout
- **Core Technologies:** 레이저 프로젝션 · 서버 기반 설계변경 실시간 동기화 · (Vinci 협업)
- **Business Problem:** 설계-시공 불일치 · 언어장벽 · 책임 공방
- **Key Insights:** 실시간 동기화로 본사-현장 커뮤니케이션 해결 · 글로벌 건설 협업 확장
- **Keywords:** `LaserProjection` `ConstructionLayout` `RealtimeSync`

### S19 — 클라우드 CCTV 통합관제(VMS)
- **Company:** (미기재 영상보안사) · **Category:** Security/Surveillance
- **Core Technologies:** 클라우드 CCTV 통합관제(VMS) · NVR/서버 불요 · 글로벌 다거점 단일 관제 · CSAP 인증 · 구독형 과금
- **Business Problem:** CCTV 구축비·유지보수 부담·글로벌 통합 관리 어려움
- **Key Insights:** 인프라 경량화 · 다국가 통합 관제 · 공공급 보안 인증
- **Keywords:** `CloudVMS` `CCTV` `CSAP` `Surveillance`

### S20 — AI 영상생성·전시 전환 전략
- **Company:** XBrush · **Category:** Generative AI Media
- **Core Technologies:** AI 영상생성(사진·스크립트·템플릿) · 본인인증 업로드 제한 · 비가시 워터마크
- **Business Problem:** 얼굴 업로드·AI 생성물 악용·프라이버시 우려가 도입 장벽
- **Key Insights:** 생성형 AI는 기능보다 신뢰·보안이 전환 핵심
- **Keywords:** `GenerativeAI` `VideoGeneration` `Watermark` `Trust`

### S21 — AI 영상제작 플랫폼·AX 교육·저작권
- **Company:** DevDive · **Category:** Generative AI Media
- **Core Technologies:** 블록형 생성(텍스트·이미지·음성·음악·영상) · 권리 제작자 귀속 · AX 교육·실습·멘토링
- **Business Problem:** AI 생성물 저작권·상업적 활용·보안
- **Key Insights:** 결과물 권리 제작자 귀속 · AX 전환은 교육과 함께
- **Keywords:** `GenerativeAI` `Copyright` `AX` `ContentCreation`

### S22 — VLM 영상분석·안티스푸핑 출입보안
- **Company:** Dexma · **Category:** Security/Surveillance
- **Core Technologies:** VLM(Vision Language Model) 상황이해 분석 · 안티스푸핑(라이브니스) 얼굴인증 · 온프레미스/클라우드/엣지
- **Business Problem:** 얼굴인증 스푸핑 · 단순 객체탐지 한계 · 구축환경 상이
- **Key Insights:** 객체탐지→VLM 상황이해 · 안티스푸핑 필수 · 멀티 환경 지원
- **Keywords:** `VLM` `AntiSpoofing` `VideoAnalytics` `Edge`

### S23 — Athena 온프레미스 엔터프라이즈 AI 자동화
- **Company:** Uracle (유라클) · **Category:** AI/Agents
- **Core Technologies:** Athena(AI Agent Builder·RAG·Workflow Automation·앱 개발) · 온프레미스/폐쇄망 최적화
- **Business Problem:** 보안 민감 기업·공공의 AI 도입 시 데이터 보안 · 비정형(영상) 내부망 처리
- **Key Insights:** 온프레미스 최적화가 차별점 · 폐쇄망 지원 · RAG 내부문서 검색
- **Keywords:** `EnterpriseAI` `OnPremise` `RAG` `AIAgent` `Workflow`

### S24 — 제약·물류 보안봉인·추적성 포장
- **Company:** SWSP (서우에스피) · **Category:** Logistics/Physical AI (Security)
- **Core Technologies:** 보안봉인(Seal) · Tamper Evidence · 추적성 · Drum/Container/Plastic/Bio Seal
- **Business Problem:** 의약품·고가품 운송 분실·위변조 · GMP/GxP 규제
- **Key Insights:** 보안=사이버 넘어 물리 포장·운송 검증·추적성으로 확장 · 감사 대응
- **Keywords:** `SecuritySeal` `TamperEvidence` `Traceability` `PharmaLogistics`

### S25 — (영문) 보안봉인·제약물류 포장 ⚠️
- **Company:** SWSP *(파일명: Genetec — 불일치)* · **Category:** Logistics/Physical AI (Security)
- **Core Technologies:** security seal · tamper-evident · traceability packaging (S24 영문판)
- **Business Problem:** (S24 동일) high-value/pharma 운송 리스크·규제
- **Key Insights:** physical packaging·transport verification이 현대 물류보안 핵심
- **Keywords:** `SecuritySeal` `Traceability` `PhysicalSecurity`
- **⚠️ 이슈:** 파일명(Genetec)≠내용(SWSP), S24 중복. 원본 정정 필요.

---

# Technology Frequency Ranking

> 기술/개념이 등장한 **세션 수** 기준. (S25는 S24와 중복 → 보안봉인 계열 1로 계상)

| 순위 | 기술 / 개념 | 등장 세션 | 빈도 |
|:--:|------|------|:--:|
| 1 | 보안(횡단: 에이전트·영상·물리·양자) | S02,S05,S08,S19,S22,S24 | 6 |
| 2 | AI 에이전트 / 엔터프라이즈 AI 자동화 | S01,S02,S05,S09,S23 | 5 |
| 3 | 컴퓨터 비전 / 3D·VLM | S03,S04,S14,S22 (+S16) | 4~5 |
| 3 | 양자 기술(컴퓨팅·보안) | S05,S06,S07,S08 | 4 |
| 3 | 로봇 / 정밀 자동화 | S04,S10,S14,S16 | 4 |
| 3 | 포토닉스 / 레이저 / 광학 | S15,S16,S17,S18 | 4 |
| 7 | **PQC (단일 세부기술 최다)** | S05,S07,S08 | 3 |
| 7 | 온프레미스 / 엣지 AI | S19,S22,S23 | 3 |
| 7 | Human-in-the-Loop / 80:20 | S01,S03,S05 | 3 |
| 7 | 지식 구조화(온톨로지·ERD·암묵지) | S01,S03,S09 | 3 |
| 7 | 혁신 생태계 / 투자(퀘벡) | S11,S12,S13 | 3 |
| 12 | 디지털 트윈 / 시뮬레이션 | S10 (+S03,S14) | 1~3 |
| 12 | 생성형 AI(영상·콘텐츠) | S20,S21 | 2 |
| 12 | 클라우드 플랫폼 | S06,S19 | 2 |

---

# Company Index

| 기업 | 세션 | 주요 기술 / 포지셔닝 | 국적 |
|------|------|----------------------|------|
| BI Matrix | S01, S09 | 엔터프라이즈 AI, Trinity Prism, SCM 멀티에이전트·온톨로지 | KR |
| SK Shieldus & Check Point | S02 | 에이전트 AI 구조·보안, OWASP Agentic | KR/IL |
| (미기재 제조사) | S03 | XAI 예지정비·안전·비전검사 | KR(추정) |
| Foresight Coop. | S04 | 스테레오 비전·3D 인식(API/SDK) | KR |
| 한국퀀텀컴퓨팅 | S05 | 에이전트 인증·Mandate·HSM·PQC | KR |
| AWS | S06 | Amazon Braket 클라우드 양자컴퓨팅 | US |
| NORMA | S07 | 양자 클라우드·Pado-Pauli 하이브리드 | KR |
| ID Quantique (IDQ) | S08 | 양자보안 PQC·QKD·QRNG (IonQ 계열) | CH/KR |
| Pollux | S10 | Physical AI 물류·디지털트윈(Omniverse) | KR |
| Quebec Delegation | S11 | 협력형 혁신 생태계 | CA |
| Invest Québec | S12 | AI허브(MILA)·클린에너지·투자 인센티브 | CA |
| Investissement Québec | S13 | 북미 진출 원스톱 지원 | CA |
| Creaform | S14 | 3D 스캐닝·역설계·자동검사(AQC) | CA |
| Luccia | S15 | 포토닉스+AI 통합 R&D·레이저 | CA |
| Mecademic | S16 | 초소형 정밀 산업로봇·광학정렬 | CA |
| Mecasys | S17, S18 | 건설 디지털 레이아웃·레이저 프로젝션 | KR |
| (미기재 영상보안사) | S19 | 클라우드 CCTV VMS·CSAP | KR(추정) |
| XBrush | S20 | AI 영상생성·워터마크 | KR |
| DevDive | S21 | AI 영상제작 플랫폼·AX 교육 | KR |
| Dexma | S22 | VLM 영상분석·안티스푸핑 | KR |
| Uracle | S23 | 온프레미스 엔터프라이즈 AI(Athena·RAG) | KR |
| SWSP (서우에스피) | S24, S25 | 보안봉인·추적성 포장(제약·물류) | KR |
| Genetec | (S25 파일명 only) | ⚠️ 내용 누락 — 원본 확인 필요 | CA(브랜드) |

> 국적은 발표 정보 기반 추정. 미기재/추정은 표기.

---

# Business Problem Index

| 문제 유형 | 등장 세션 | 빈도 |
|------|------|:--:|
| 수작업 의존·휴먼에러·재작업 비용 | S01,S03,S14,S16,S17,S18,S19 | 7 |
| 신뢰·보안·프라이버시가 도입 장벽 | S02,S05,S08,S20,S22,S23,S24 | 7 |
| 높은 초기비용·불확실 ROI | S06,S10,S16,S19 | 4 |
| 통합·상호운용·벤더 종속 | S04,S06,S19,S25 | 4 |
| 숙련 인력 부족 | S03,S14,S17 | 3 |
| 글로벌 진출·파트너/투자 확보 | S11,S12,S13 | 3 |
| 규제·감사·추적성 | S08,S24 | 2 |
| 데이터 과잉 vs 활용 어려움(준비 과부하) | S01,S09 | 2 |
| 반응 속도·공급망 변동성 | S09,S10 | 2 |
| 글로벌 다거점·언어 장벽 | S18,S19 | 2 |
| 블랙박스 AI(설명 불가) | S03 | 1 |

---

# Technology Category Map

| 도메인 | 세션 | 세션 수 |
|------|------|:--:|
| **AI / Agents** | S01, S02, S05, S09, S23 | 5 |
| **Quantum** | S06, S07, S08 (+S05 PQC) | 3~4 |
| **Robotics / Vision** | S04, S16 | 2 |
| **Manufacturing** | S03, S14, S15 | 3 |
| **Logistics / Physical AI** | S10, S24, S25 | 3 |
| **Security / Surveillance** | S19, S22 | 2 |
| **Generative AI Media** | S20, S21 | 2 |
| **Construction / Digital Layout** | S17, S18 | 2 |
| **Innovation Ecosystem** | S11, S12, S13 | 3 |

---

# Cross-Reference Matrix

## A. 세션 ↔ 기업 ↔ 기술 ↔ 산업 ↔ 문제 (통합 매트릭스)

| ID | 기업 | 핵심 기술 | 산업/버티컬 | 핵심 문제 |
|----|------|-----------|-------------|-----------|
| S01 | BI Matrix | 의사결정 자동화 | 전산업(BI) | 준비과부하 |
| S02 | SK Shieldus·CheckPoint | Agentic AI 보안 | 사이버보안 | 에이전트 보안위협 |
| S03 | (제조사) | XAI·예지정비 | 제조 | 블랙박스/안전 |
| S04 | Foresight | 스테레오 비전 | 모빌리티/인프라 | 3D 인식 비용 |
| S05 | 한국퀀텀컴퓨팅 | Mandate·PQC | 사이버보안/엔터프라이즈 | 에이전트 권한통제 |
| S06 | AWS | 양자 클라우드 | 클라우드/전산업 | 양자 진입장벽 |
| S07 | NORMA | QML·하이브리드 | 제약·금융·최적화 | 양자 비용·불안정 |
| S08 | IDQ | PQC·QKD | 공공·금융 보안 | Q-Day·HNDL |
| S09 | BI Matrix | SCM 에이전트·온톨로지 | 제조·유통 SCM | 복잡 의사결정 |
| S10 | Pollux | Physical AI·디지털트윈 | 물류 | SI의존·변동성 |
| S11 | Quebec Delegation | 혁신 생태계 | 정부/협력 | 공동R&D 파트너 |
| S12 | Invest Québec | AI허브·클린에너지 | 정부/투자 | 투자유치 |
| S13 | Investissement Québec | 진출 원스톱 | 정부/투자 | 진출 비용 |
| S14 | Creaform | 3D 스캐닝·AQC | 제조(항공·자동차·배터리) | 수작업 측정 |
| S15 | Luccia | 포토닉스+AI | 반도체·국방·우주 | R&D 사업화 |
| S16 | Mecademic | 정밀로봇 | 전자·의료·항공 제조 | 정밀자동화 비용 |
| S17 | Mecasys | Projected Reality | 건설 | 수작업 마킹 |
| S18 | Mecasys | 레이저 프로젝션 | 건설 | 설계-시공 불일치 |
| S19 | (영상보안사) | 클라우드 VMS | 물리보안/감시 | 구축비·글로벌관제 |
| S20 | XBrush | AI 영상생성 | 미디어/콘텐츠 | 악용·프라이버시 |
| S21 | DevDive | AI 영상제작 | 미디어/교육 | 저작권·보안 |
| S22 | Dexma | VLM·안티스푸핑 | 물리보안/출입 | 스푸핑 |
| S23 | Uracle | 온프레미스 AI(RAG) | 엔터프라이즈/공공 | 데이터 보안 |
| S24 | SWSP | 보안봉인·추적성 | 제약·바이오·물류 | 위변조·규제 |
| S25 | SWSP ⚠️ | 보안봉인(영문) | 제약·물류 | 위변조·규제 |

## B. 기술 도메인 ↔ 산업 매핑

| 기술 도메인 \ 산업 | 제조 | 물류 | 보안 | 모빌리티 | 미디어 | 건설 | 공공/투자 |
|------|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| AI/Agents | ● (S03,S09) | ● (S09) | ● (S02,S05,S23) | | | | ● (S23) |
| Quantum | | | ● (S08) | | | | ● (S07 금융) |
| Robotics/Vision | ● (S14,S16) | | ● (S22) | ● (S04) | | | |
| Photonics/Optics | ● (S15) | | ● (S15 국방) | | | | |
| Digital Twin/Physical AI | ● (S10) | ● (S10) | | | | | |
| Generative AI | | | | | ● (S20,S21) | | |
| Security/Surveillance | | ● (S24) | ● (S19,S22) | | | | |
| Construction Tech | | | | | | ● (S17,S18) | |
| Ecosystem/Investment | | | | | | | ● (S11,S12,S13) |

## C. 문제 ↔ 대응 기술 매핑

| 반복 문제 | 대응 기술/접근 | 근거 세션 |
|------|----------------|-----------|
| 수작업·휴먼에러 | XAI·비전검사·3D스캐닝·정밀로봇·디지털 레이아웃 | S03,S14,S16,S17,S18 |
| 신뢰·보안 | Mandate·PQC/QKD·안티스푸핑·온프레미스·워터마크 | S05,S08,S22,S23,S20 |
| 비용·ROI | 클라우드 사용량 과금·Hexapod 대체·구독형 | S06,S16,S19 |
| 통합·종속 | API/SDK·멀티 하드웨어·통합관제 | S04,S06,S19 |
| 의사결정 과부하 | 의사결정 준비 자동화·SCM 멀티에이전트 | S01,S09 |
| 공급망 변동성 | Physical AI 실시간 재계획·디지털트윈 | S09,S10 |
| 규제·추적성 | 보안봉인·Tamper Evidence·추적성 | S08,S24 |

---

## 부록 — 무결성 메모
- 본 인덱스는 레포 내 25개 컨퍼런스 노트만 근거. 외부 추정·특정 조직 내부정보 없음.
- **S25 원본 이슈:** 파일명 `Genetec_Unification_Physical_Security_Platform` ↔ 내용 SWSP(영문) 불일치 → 내용 기준 분류·중복 명시.
- 기업명 미기재 세션(S03, S19)은 "(미기재)"로 표기. 국적·산업 매핑은 발표 정보 기반 추정 포함.
- 본 문서가 향후 트렌드/분석 리포트의 기준(Source of Truth)이다.
