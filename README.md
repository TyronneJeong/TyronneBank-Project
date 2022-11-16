# Tyronne Bank Project (TBP)
  <a href="https://github.com/ionic-team/ionic-framework/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Ionic Framework is released under the MIT license." />
  </a>
  <a href="https://github.com/ionic-team/ionic/blob/main/.github/CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>

시스템 안전성을 위해 오래전 부터 한국의 뱅킹 시스템은 오픈스택의 기술보다는 개별 솔루션 중심의 시스템 구축을 이어져 왔다. 이러한 On-Prem 방식의 뱅킹 시스템은 최근 화두가 되는 Scale Out 방식의 확장에 유연하지 못하고, 고성능 하드웨어에 의존하는 시스템 구성상 사용자수 증가에 따른 Scale Up 비용이 기하 급수적으로 증가하는 형태를 보이고 있다. 

때문에, 최근 유행하는 MSA 설계방식과 메모리 캐싱 및 메세지 브로커 등을 이용한 트랜잭션 분산 전략을 이용하여, 결합도(Coupling)을 줄이고 클라우드 컴퓨팅을 통한 대규모 분산 처리를 통해 저비용 고효율의 시스템 구성을 시도해볼 충분한 가치가 있다고 판단했다.

이를 위해, 기존 도메인 기능은 유지하되 최근 화두가 되는 기술 셋을 어떤 형태와 방식으로 적용할지에 대해 논의 할 것이고, 설득력 있는 데이터에 기반 하여 시스템을 구성, 본격적 활용이 가능한 다양한 기술 셋의 적용으로 기존 뱅킹 시스템을 한 단계 더 업그레이드 시키고자 한다. 

해당 작업을 통해, 보수적인 스킬 셋에서 벗어나 조금 더 유연하고 기술 활용도가 높은 도구 사용으로 트랜드에 충실하고, 그 과정에서 미처 생각하지 못한 장애상황과 난관을 극복하는 과정을 통해 미래 시스템의 발전 방향에 대해서도 모색해 보고자 한다.

## Getting Started
    [installation 작업 후 기술]
    $ 


## System Architecture
###### Infra Strctures
- [writting]

###### ER-Diagrams
- [writting]

## Features
###### 주요 기능
* 회원 가입 (비대면 회원 가입 및 인증)
* 고객 예금 계좌 개설
* 고객 신규 대출 신청
* 일별 예금 이자 지급 배치
* 일별 대출 이자 계산 배치
* 상품등록관리
* 일별마감처리
* 일별정산처리
* ETL
* 마트테이블구성
* OLAP구성
* 충당금적립
* 리스크분석

###### 기술 목표
* 대용량 트래픽에 적합한 아키텍쳐 구축
* 동기/비동기 처리를 이용한 경제적인 시스템 구성
* JPA 및 SQL을 사용한 쿼리 작성 및 튜닝
* 웹소켓을 이용한 실시간 푸쉬 구성
* 테스트 자동화 및 CI/CD 빌드 구성
* ETL을 이용한 데이터 마트 구성
* ML을 이용한 데이터 분석 모델 구성 및 데이터 산출
* SSR기반의 프레임워크를 이용한 화면 구성


## Technologies
###### Backend
* Java Spring Boot
* Redis
* Kafka
* MyBatis, JPA
* Jenkins
* Docker
* PostgreSQL
* MySQL

###### Frontend
* Node
* React

## Change Log
* v0.1 - Initial release.