![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorlist=100&height=300&section=header&text=Noah's%20GitHub&fontSize=80&animation=twinkling)
# 🚀 Identity
> **"작은 변화일지라도 명확한 근거를 기반으로 개발합니다. 애매한 의도를 담은 코드보다 틀리더라도 명확한 의도가 담긴 코드를 작성하는 것을 선호합니다."**

## 🛠 Tech Stack
- **Backend**
<p>
	<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white" alt="Java" />
	<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Boot" />
	<img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Cloud" />
	<img src="https://img.shields.io/badge/JPA-6DB33F?style=flat-square&logo=hibernate&logoColor=white" alt="JPA" />
	<img src="https://img.shields.io/badge/Querydsl-2F9AE0?style=flat-square&logoColor=white" alt="Querydsl" />
	<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
	<img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit5" />
	<img src="https://img.shields.io/badge/Mockito-4B32C3?style=flat-square&logo=mockito&logoColor=white" alt="Mockito" />
</p>

- **Infra**
<p>
	<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
	<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white" alt="GCP" />
	<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
	<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
    	<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
	<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
	<img src="https://img.shields.io/badge/Sentry-000000?style=flat-square&logo=sentry&logoColor=white" alt="Sentry" />
</p>

- **Database**
<p>
	<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
	<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
	<img src="https://img.shields.io/badge/Redis-D82C20?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
</p>

## 📂 Featured Projects
### 1. [MyMeal](https://github.com/gratisreise/mymeal)
- **Description**: RAG를 이용한 개인화 식단 추천 서비스
- **Summary**:
    - **RAG**: 벡터검색을 이용한 문맥주입으로 **개인화된 식단 추천**
	- **AI식단분석**:  Spring Ai를 이용하여 gemini-2.5-flash를 연결하고 **사진을 분석하여 식단 자동저장**
    - **배치처리**: gemini의 호출제한을 피하기 위해 배치 설정
    - **Redis ZSet**:주기적인 DB의 반복조회를 피하기 위해 Redi ZSet을 이용하여 알림예약
	- **FCM**: FCM 토큰을 이용하여 **푸시알림 구현**
	

### 2. [Rebook](https://github.com/gratisreise/rebook)
- **Keyword**: 다중 서버를 고려한 확장성 있는 아키텍처 설계
- **Summary**:
    - **Netfilx Passport**: API Gateway 기반 요청 흐름에서 “JWT 외부 인증”과 “내부 Passport 인증”을 분리
    - **Outbox Pattenr & DLQ**:Outbox Pattern과 DLQ 기반설계로 **데이터 일관성**과 **메시지 안정성 강화**
    - **Redis Pub/Sub**:Redis Pub/Sub을 이용해 메세지 처리 불일치를 해결하고 알림서비스 **확장성 개선**
	- **AI거래묶음등록**: LLM을 이용하여 도서를 추출하고 거래자동등록
	- **MSA**:  Spring Cloud를 이용하여 6개의 서비스를 가지는 **MSA 아키텍처 구축**


### 3. [MyLog](https://github.com/gratisreise/mylog)
- **Keyword**: 데이터 기반 성능 최적화
- **Summary**:
	- **N+1 문제**: QueryDSL을 이용한 쿼리 최적화로 N+1문제 해결 후 **90ms -> 45ms**로 **50% 개선**
    - **CI-CD 파이프라인**: GitHUb Actions를 이용한 CI-CD 파이프 라인 구축으로 배포시간 **40분 -> 8분 80% 감소**
	- **JWT 토큰처리**: Access 토큰을 블랙리스트 처리하여 토큰 무단도용 방지
    - **AI 문체변환**: LLM을 이용하여 작성한 글을 원하는 문체로 변경
    - **AI 요약**: 게시글의 내용을 요약하여 사용자의 글자 피로도 감소 
	
    



## ✍️ Code Contribute
[eclipse-colecctions](https://github.com/eclipse-collections/eclipse-collections/pull/1844)

## 📈 Stats
[![Noah's GitHub stats](https://github-readme-stats.vercel.app/api?username=gratisreise&theme=gotham&show_icons=true)](https://github.com/gratisreise/github-readme-stats)

[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=pray00)](https://solved.ac/pray00)




### ✉️ Contact Me
- email: jeonghogim318@gmail.com