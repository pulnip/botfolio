# AI 기반 주가 예측 및 자동매매 서비스 설계 위키

---

## 프로젝트 소개

본 프로젝트는 **BotFolio**라는 가상의 주식 거래(자동 매매) 서비스가 가져야 할 **구성 요소**와 **설계 방법**을 문서화하는 데 목적이 있습니다.
실제 구현 없이, 필요한 기능/구조/요구사항을 체계적으로 정리하여, **설계 단계에서 참고할 수 있는 가이드라인**을 제공합니다.

- *프로젝트*는 본 가이드라인 문서를 가리키고, *서비스*는 **BotFolio**를 가리킵니다.

---

## 대상 독자들

- 주식 거래 시스템을 설계하려는 자
- 주식 거래 관련 지식이 없는 개발자
- 실제 자동 매매 시스템을 탐색하려는 자

본 문서는 독자 레벨(L1~L4)에 따라 **목차/Quick Link**로 원하는 파트를 빠르게 찾아볼 수 있게 구성되어 있습니다.

| 레벨 | 추천 파트 | 설명 |
|------|-----------|------|
| L1(일반 사용자)| 서비스 개요, 요구사항 | 간단한 서비스 이해 |
| L2(파워 사용자)| + 아키텍처, 와이어프레임 | 시스템 사용법/흐름 이해 |
| L3(개발자)| + DB, 상세 기능 | 직접 구현에 필요한 정보 |
| L4(서비스 관리자)| 전체 문서 | 구조+동작 전체 파악 |

--

## Target Scope

- 실존 앱의 기능 설명/비교는 하지 않습니다.
- 특정 프레임워크 혹은 API에 종속된 기술은 배제하여 설명합니다.

---

## Getting Started (문서 활용법)

아래 목차에서 원하는 파트를 클릭해 설계 문서를 탐색하세요!

- **각 단계별 설계 예시**와 분업 방법이 포함되어 있습니다.
- 상세한 다이어그램/표/와이어프레임은 각 문서에서 확인하세요.

---

## 목차

1. [서비스 개요](./Introduction.md)
2. [주요 요구사항 및 유즈케이스](./Requirement.md)
3. [시스템 아키텍처 & 컴포넌트](./Architecture.md)
4. [데이터베이스 설계(ERD)](./Database.md)
5. [상세 기능 설계 & 시퀀스](./FeatureDesign.md)
6. [UI/UX 와이어프레임](./Wireframe.md)
7. [보안/운영/배포 설계](./Operation.md)
8. [참고자료](./References.md)

---

## Quick Link

- [L1~L4 독자별 추천 파트 바로가기](#)
- [Use Case Diagram](./Requirement.md#use-case-diagram)
- [ERD (DB 설계도)](./Database.md#erd-엔터티-관계도)
- [시퀀스 다이어그램](./FeatureDesign.md#sequence-diagram)
- [컴포넌트 구조](./Architecture.md#주요-컴포넌트)

---

## 프로젝트 정보

- 프로젝트명: `BotFolio`
- 문서 형식: Markdown + Image/Diagram

---
