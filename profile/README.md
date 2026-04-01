
# Alpha30000

<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=260&color=0:0F172A,45:1E3A8A,100:22C55E&text=Alpha30000&fontColor=F8FAFC&fontSize=64&fontAlignY=38&desc=%EC%95%8C%ED%8C%8C%EC%B0%BE%EC%95%84%EC%82%BC%EB%A7%8C%EB%A6%AC%20%7C%20%ED%81%AC%EB%A6%BD%ED%86%A0%20%ED%80%80%ED%8A%B8%20%EC%97%B0%EA%B5%AC%20%EB%B0%8F%20%EC%8B%9C%EC%8A%A4%ED%85%9C%20%ED%8A%B8%EB%A0%88%EC%9D%B4%EB%94%A9&descAlignY=58&descSize=18)

<p align="center">
  <img src="https://img.shields.io/badge/Quant%20Research-Crypto%20Long%2FShort-0F172A?style=for-the-badge&logo=bitcoin&logoColor=F7931A" />
  <img src="https://img.shields.io/badge/Multi--Exchange-Binance%20%7C%20OKX%20%7C%20Upbit-1E3A8A?style=for-the-badge&logo=binance&logoColor=F0B90B" />
  <img src="https://img.shields.io/badge/Focus-Execution%20%26%20Infrastructure-22C55E?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,git,github,linux&perline=7" />

</div>

---

## 소개

**Alpha30000**은 “알파를 끝까지 찾는다”는 이름 그대로,  
분절된 시장 구조 속에서 반복 가능한 **퀀트 알파**를 탐색하고 구현하는 연구 조직입니다.

우리는 감(感)에 의존한 단발성 매매보다, 아래와 같은 문제를 더 중요하게 봅니다.

- 시장 데이터를 어떻게 **일관된 스키마**로 수집할 것인가
- 거래소마다 다른 API와 제약을 어떻게 **공통 인터페이스**로 추상화할 것인가
- 시그널, 포트폴리오, 주문, 체결, 리스크를 어떻게 **재현 가능한 시스템**으로 연결할 것인가
- 아이디어를 어떻게 백테스트에서 끝내지 않고 **실행 가능한 전략**으로 바꿀 것인가

---

## 우리가 하는 일

### 1. 크립토 퀀트 리서치
- 거래소별 상위 유니버스를 기반으로 한 **cross-sectional long-short alpha** 연구
- 팩터, 랭킹, 리밸런싱, 거래비용 반영을 포함한 **시스템 전략 개발**
- 비차익거래 관점에서의 상대가치, 모멘텀, 리버설, 마이크로스트럭처 시그널 탐색

### 2. 멀티 거래소 데이터 엔지니어링
- Binance, OKX, Bitget, Gate.io, Upbit, Bithumb 등 거래소 통합
- 과거 분봉 및 실시간 데이터 수집
- Raw / Normalized 레이어 분리 및 canonical symbol 체계 구축

### 3. 실행 시스템 개발
- 거래소 비종속적 OMS 설계
- 포지션, 주문, 체결, 리스크 상태 추적
- Paper trading에서 live trading으로 이어지는 실행 파이프라인 구축

---

## 핵심 프로젝트

### CrossAlpha
> Cross-exchange crypto long-short alpha research and execution framework

- Binance 선물 기준 MVP 설계
- 향후 OKX / Bitget / Gate / Upbit / Bithumb 확장
- Pydantic 기반 도메인 모델
- FastAPI 기반 control plane
- OMS / 데이터 파이프라인 / 백테스트 / 리서치 프레임워크 통합

---

## 기술 방향

<div align="center">

| 영역 | 방향 |
|---|---|
| Data | 과거 분봉 적재, 실시간 스트리밍, 정규화 스키마 |
| Research | 팩터 연구, 크로스섹셔널 랭킹, 포트폴리오 구성 |
| Execution | OMS, 주문 라우팅, 체결/포지션 상태관리 |
| Infra | API, 스케줄링, 스토리지, 모니터링 |
| Principle | 재현성, 확장성, 운영 가능성 |

</div>

---

## 철학

> **Alpha is not prediction. Alpha is structure.**

우리는 “정확히 맞히는 모델”보다  
**반복 가능하고 검증 가능하며 운영 가능한 시스템**을 더 높게 평가합니다.

- 예측보다 구조
- 아이디어보다 실행
- 일회성 성과보다 재현성
- 복잡한 말보다 명확한 데이터 흐름

---

## 관심 있는 주제

- Crypto Long/Short
- Multi-Exchange Infrastructure
- Market Microstructure
- OMS Design
- Portfolio Construction
- Minute-Level Data Engineering
- Backtesting & Live Execution

---

## 참여 방식

이 조직은 단순히 전략 아이디어를 모아두는 공간이 아니라,  
**리서치와 시스템 구현이 함께 가는 저장소**를 지향합니다.

관심 있는 분들은 아래 주제에서 함께할 수 있습니다.

- 거래소 API 연동
- 데이터 파이프라인 구축
- 팩터 리서치
- 백테스트 엔진 개선
- 실행 시스템 및 리스크 관리
- 문서화 및 운영 자동화

---

<div align="center">

![footer](https://capsule-render.vercel.app/api?section=footer&type=waving&height=140&color=0:0F172A,45:1E3A8A,100:22C55E)

</div>
