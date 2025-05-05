# 선착순이오

## 프로젝트 주제
한정판매, 경매, 체험단 모집, 쿠폰 발급과 같은 트래픽 집중 이벤트를 안정적으로 처리하는 MSA기반 Spring Boots 프로젝트

## 프로젝트 목표
- MSA 구조의 확장성과 유연성을 통한 안정적인 서비스 제공.
- 대규모 트래픽 처리
    - Redis, Kafka, AWS 사용으로 트래픽 집중 시 캐싱, 스케일 업, 비동기 처리를 통한 안정적인 구조 설계
- 대용량 데이터 처리
    - Kafka의 메시지 큐 기능을 사용하여 대용량 데이터의 순차적인 처리 기능 제공
- 서비스 장애 조기 탐지 및 신속한 대응을 위한 모니터링 시스템 구축
    - Prometheus(수집), Grafana(view 제공)를 활용한 실시간 메트릭 및 로그 모니터링으로 시스템 안정성 확보

## 기술적 의사 결정

## 적용 기술
<div align=center>
	<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
  <img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white">
    <br>
</div>

## 역할

### 조규성
| Leader |
|-------|
| Eureka Server : https://github.com/LIMITED-TEAM25/eureka-server |
| API Gateway : https://github.com/LIMITED-TEAM25/api-gateway |
| Auth Service : https://github.com/LIMITED-TEAM25/auth-service |
| User Service : https://github.com/LIMITED-TEAM25/user-service |
| Coupon Service : https://github.com/LIMITED-TEAM25/coupon-servcie |
| User Coupon Service : https://github.com/LIMITED-TEAM25/user-coupon-service |
| User Coupon Consumer : https://github.com/LIMITED-TEAM25/user-coupon-consumer |
---

### 엄은진
| Sub-Leader |
|-------|
| auction Service : https://github.com/LIMITED-TEAM25/auction-service |
| Order Service : https://github.com/LIMITED-TEAM25/order-service |
---

### 이소현
| Member |
|-------|
| Limited Service : https://github.com/LIMITED-TEAM25/limited-service |
| Product Service : https://github.com/LIMITED-TEAM25/product-service |
---

### 안중건
| Member |
|-------|
| Preuser Service : https://github.com/LIMITED-TEAM25/preuser-service |
| Common Module : https://github.com/LIMITED-TEAM25/common-module |


