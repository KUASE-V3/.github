# OOAD(T5, T6), V&V (T3) Organization

| 최종 업데이트: 2025-05-08

## 개발자 필수 도구

### 개발 환경

- Docker: 컨테이너 기반 개발 환경. Ubuntu를 기반으로 한 리눅스 환경에서 동작

  - WSL (Windows Subsystem for Linux) **2** 혹은 Mac 환경 필요

  - docker 컨테이너 실행 여부 확인 필수

    - docker run hello-world

- VSCode: 코드 편집 및 원격 개발을 위한 주요 에디터

### 소통 도구

- Discord: 팀원 간 실시간 소통 채널로 사용

## 검증팀 사용 도구

### 자동화 도구

- Github Actions: 코드 빌드, 테스트 등 자동화된 CI/CD 파이프라인 구축

### 빌드 도구

- CMake: 크로스 플랫폼 빌드 시스템으로 프로젝트 빌드

### 검증 환경

- 개발팀과 동일한 컨테이너

- CPU Architecture: x86_64

- Host OS: Ubuntu 22.04.5

## Unit Test & Static Analysis

### Unit Test

- GoogleTest: C++ 단위 테스트 프레임워크를 사용합니다.

### Static Analysis

- cppcheck: C/C++ 코드 정적 분석 도구

- gcovr: Test 코드 커버리지 측정 도구

- SonarCloud: 클라우드 기반 코드 품질 및 보안 분석 도구

## 참고

- 개발 및 검증 환경은 Docker 컨테이너 내에서 일관되게 제공됩니다.

- 모든 자동화 및 품질 관리는 Github Actions 워크플로우에서 실행됩니다.

- 추가 문의는 Discord 채널을 통해 진행해 주세요.