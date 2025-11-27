# 📚 스타트업 서비스 설계는 처음인데요 - Deep Dive Log
<img width="458" height="539" alt="image" src="https://github.com/user-attachments/assets/131d2d0c-3283-427c-bc39-fb24987afece" />

이 레포지토리는 강대명 저자의 《스타트업 서비스 설계는 처음인데요》를 학습하며, 단순한 지식 습득을 넘어 **실제 서비스 설계 단계에서의 의사결정 과정**을 정리한 공간입니다.

<br>

## 🛑 My Study Principles (학습 원칙)
이 스터디는 실습 코드 작성보다 **설계적 사고(Architectural Thinking)** 함양을 목표로 하며, 다음 4가지 원칙을 따릅니다.

1.  **Focus (몰입):** 텍스트를 읽는 행위와 설계를 고민하는 시간을 분리하여, 각 단계에 온전히 집중합니다.
2.  **Internalization (체화):** 책의 내용을 요약하는 것에 그치지 않고, **"나의 언어와 논리"**로 재구성하여 기록합니다.
3.  **Contextualization (맥락 적용):** 학습한 기술적 개념(MSA, 클라우드 등)을 **나의 타겟 서비스 상황**에 대입해보고, 도입 여부와 그 이유를 구체적으로 정리합니다.
4.  **Simulation (사고 실험):** 코드로 구현하지 못하는 인프라/운영 환경은 **"가상의 시나리오(장애 발생, 트래픽 급증 등)"**를 설정하여 대응 전략을 수립해 봅니다.

<br>

## 🎯 Project Info
* **Target Book:** [스타트업 서비스 설계는 처음인데요](https://www.google.com/search?q=스타트업+서비스+설계는+처음인데요)
* **Target Service:** **[FixAny]**
    * *Goal: 책에서 제시하는 기준들을 내 비즈니스 모델과 리소스 상황에 맞춰 최적화하기*
* **Period:** 2025.11 ~ (진행 중)

<br>

## 🧠 Knowledge Map (Concept & Decision)

| Chapter | Topic | My Insight (Link) | Architecture Decision (Link) | Status |
|:---:|:---|:---:|:---:|:---:|
| **Ch 1** | 스타트업에서 서비스를 구현할 때 고려사항 | [ 초기 기술 전략](./docs/ch01_consideration.md) | - | 🏃 |
| **Ch 2** | 인프라 구성 | [클라우드 비용 효율화](./docs/ch02_infra.md) | [인프라 구성도 초안](./docs/arch/infra_v1.md) | |
| **Ch 3** | 배포와 테스트 | [스타트업의 CI/CD](./docs/ch03_deploy.md) | [배포 전략 기획서](./docs/arch/deploy_strategy.md) | |
| **Ch 4** | 서비스 아키텍처 | [모놀리식 vs MSA](./docs/ch04_arch.md) | [아키텍처 다이어그램](./docs/assets/arch_diagram.png) | |
| **Ch 5** | 단축 URL 서비스 만들기 (실습) | [대용량 트래픽 설계](./docs/ch05_url_shortener.md) | [핵심 로직 설계(Pseudo)](./docs/design/url_logic.md) | |
| **Ch 6** | 코딩 AI 활용 | [AI기반 생산성 향상](./docs/ch06_ai_coding.md) | - | |
| **Appx** | 서비스를 위해 더 고민할 부분 | [확장성/운영 메모](./docs/appendix_more.md) | - | |
<br>



