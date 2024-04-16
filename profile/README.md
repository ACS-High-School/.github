# 연합 학습을 위한 AI 플랫폼

![home](https://github.com/ACS-High-School/.github/assets/84767822/90f7fca8-8c8b-4c31-80a4-7af3411fa6d4)

- 배포 URL : https://www.bthreeo.com
  
- [발표자료](https://docs.google.com/presentation/d/1FbxS0mgk8EbnpBwkMGZ-PL0NbhPwwf63lWoJE7GWC70/edit?usp=sharing)
  
- [보고서](https://docs.google.com/document/d/1kFjMnBKZznUJAotCoSB4mtgbNWxHKEsq/edit?usp=sharing&ouid=106790920303116051702&rtpof=true&sd=true)

<br>

## 프로젝트 소개 
- 다수의 클라이언트는 연합학습을 통해 모델 성능 개선 및 SOTA 모델 배포
- 서비스 사용자들은 배포된 모델 기반으로 codeless Inference 수행

## 프로젝트 목적
- AWS 기반 3 Tier Web Application 구축
- CI/CD 파이프라인을 사용하여 Amazon EKS에 Java 애플리케이션 자동 구축 및 배포 
- Inference pipeline 구축 및 Real-time prediction 서비스 구현
- Federated Learning workflow 구축 및 서비스 구현

## 요구 사항 정의
### 인프라
1. 가용성을 보장하기 위해, 업데이트 시에도 서비스가 중단되지 않도록 하는 CI/CD 파이프라인 구축 
2.  웹 서비스를 운영하기 위한 안정적이고 확장 가능한 컨테이너 오케스트레이션 환경 구성
3.  인프라 구성을 코드로 관리하여, 인프라의 배포와 변경을 자동화
4.  시스템의 건강 상태와 성능을 실시간으로 모니터링하고, 문제 발생 시 빠르게 대응할 수 있는 시스템

### 서비스
1.  사용자 친화적인 웹 인터페이스와 사용자 경험(UX) 제공
2.  사용자 등록, 인증, 프로필 관리 등의 기능을 포함한 안정적인 회원 관리 시스템 구현 
3. 머신 러닝 모델을 활용한 결과를 제공하는 API를 구현

### ML
1. 다수의 클라이언트가 동시에 학습할 수 있는 연합학습 시스템 구축 
2. 학습된 모델을 기반으로 실시간 추론이 가능한 서비스 제공
3.  연합학습을 시뮬레이션이 가능한 시스템 구축

<br>

## 기술 스택
<img width="1113" alt="기술스택" src="https://github.com/ACS-High-School/.github/assets/84767822/bc49e20b-6ca2-4cae-ab1b-2c2267286387">

<br>

## 아키텍처
<img width="1096" alt="아키텍처" src="https://github.com/ACS-High-School/.github/assets/84767822/81dddbbb-e80d-49fd-a378-77b4ac79c49d">

<br>

## FlowChart
<img width="1047" alt="FlowChart" src="https://github.com/ACS-High-School/.github/assets/84767822/86ff1dc3-97fb-4d3a-952a-26c635e2aa6d">

<br>


## 주요 기능
### 인프라
1. 무중단 배포를 위한 CI/CD 구축
2. 웹 서비스 배포를 위한 EKS 클러스터 구성 
3. IaC를 활용한 인프라 구축 
4. 옵저빌리티 & 모니터링

### 서비스 
1.  웹 UI, UX 제공 & 회원관리 시스템
2.  ML 서비스를 제공하는 API 구현 

### ML 
1.  연합학습 Workflow 구축 및 서비스 구현 
2.  Inference Workflow 구축 및 서비스 구현 
3.  Client를 위한 연합학습 Simulation 구축

<br>

## 시연 영상
### CI/CD
// B3O-CICD-최종.mp4 첨부

### 모니터링
// B3O-모니터링-최종.mp4 첨부

### 서비스 & ML
// B3O-서비스-최종.mp4 10MB 밑으로 해서 첨부

<br>

## 팀 소개
<img width="1879" alt="팀소개" src="https://github.com/ACS-High-School/.github/assets/84767822/744166b7-7b67-43ab-96f9-4c00ab00f509">

<br>

## 팀원 구성

<div align="center">

| **김선우** | **이승준** | **정다영** | **홍준표** |
| :------: |  :------: | :------: | :------: |
| [<img src="https://github.com/ACS-High-School/.github/assets/84767822/2d501185-d56d-49a6-8acc-b1bf68028dfd" height=150 width=150> <br/> @sw801733](https://github.com/sw801733) | [<img src="https://github.com/ACS-High-School/.github/assets/84767822/b109bf6d-c76b-4531-a8bd-62dcdc31ca67" height=150 width=150> <br/> @tmdwnsdl](https://github.com/tmdwnsdl) | [<img src="https://github.com/ACS-High-School/.github/assets/84767822/c7da73ee-b6db-474a-98fc-e07f36570ff0" height=150 width=150> <br/> @Dayoung-Jung](https://github.com/Dayoung-Jung) | [<img src="https://github.com/ACS-High-School/.github/assets/84767822/d1581bb4-3022-4552-a15c-b3ef4156db53" height=150 width=150> <br/> @hjp1016](https://github.com/hjp1016) |
| Full-stack Developer |  DBA | PM | Full-stack Developer |
| Deveops Engineer |  Data Engineer | MLOps Engineer | Deveops Engineer |

</div>

<br>

## 개발 기간

![개발기간png](https://github.com/ACS-High-School/.github/assets/84767822/5911c075-3449-4433-9b7f-f0fc18c6832d)

<br>
