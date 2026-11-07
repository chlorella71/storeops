# StoreOps

**Store Operations Management Platform**

프랜차이즈 매장의 반복적인 운영 업무를 효율화하고, 데이터 기반 의사결정을 지원하기 위한 웹 애플리케이션입니다.

## 프로젝트 배경

실제 프랜차이즈 매장 근무 경험을 바탕으로, 엑셀을 이용한 근무표 작성 과정에서 발생하는 반복 작업과 인력 배치의 어려움을 개선하고자 시작했습니다.

## 주요 기능

### 1차 개발 - 근무 스케줄 관리

- 직원 및 근무 유형 관리
- 고정 근무 패턴 자동 입력
- 엑셀형 월간 근무표 편집
- 근무표 저장 및 엑셀 다운로드

### 향후 확장

- 근무 규칙 검증 및 자동 편성
- 인력 운영 및 매출 분석
- 재고 및 발주 관리
- AI 기반 운영 의사결정 지원

## Tech Stack

- Frontend: React, TypeScript
- Backend, Java 21, Spring Boot
- Database: MySQL
- Infrastructure: Docker, GitHub Actions (예정)

## Documentation

- [Requirements](docs/requiremnts.md)

## Commit Convention

This project follows [Conventional Commits](https://www.conventionalcommits.org/).

**Format:**

<type>[(scope)]: <description>

| Type | Description |
|------|-------------|
| feat | New feature |
| fix | Bug fix |
| docs | Documentation |
| refactor | Code refactoring |
| test | Tests |
| chore | Maintenance |
| build | Build and dependencies |
| ci | CI/CD |
