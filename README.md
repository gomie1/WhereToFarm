
# 어디가농? 🌽

> **"데이터 기반 맞춤형 귀농 지역 추천 서비스"**  
우아한 자매들이 만드는 스마트한 귀농 가이드 🚜✨  

📽️ [시연 영상 바로가기](https://drive.google.com/file/d/1nhuQVSqwYE_Bl4Ter0TAZ4RBhGhQi_vt/view) 
📝 [회의록 보기](https://cloud-ice-455.notion.site/1d515a2ee9308155bc00c09a12c43fbe?pvs=4)


## 목차

🌱 어디가농? 서비스 소개
<br>
⏰ 개발 기간
<br>
💡 기획 배경
<br>
🎯 목표 및 주요 기능
<br>
🔧 기능 소개
<br>
📢 기술 스택 소개
<br>
🔍 시스템 아키텍처
<br>
💾 ERD 다이어그램
<br>


## 👥 팀 소개 및 역할

### ⏰ 개발 기간 (6주)
2025.03.03 ~ 2025.03.14 (2주) 기획, 설계
<br>
2025.04.15 ~ 2025.04.11 (4주) 개발

### 💡 기획 배경

귀농을 고려하는 사람들은 지역 선택에 많은 어려움을 느낍니다. <br>환경, 비용, 인프라 등 다양한 요소를 고려해야 하지만, 이러한 정보를 종합적으로 제공하는 서비스가 부족합니다.<br>
또한 귀농 후 실패율이 높은 이유 중 하나는 충분한 정보와 준비 없이 결정하는 경우가 많기 때문입니다. <br>귀농 희망자가 더 현명한 선택을 할 수 있도록 데이터에 기반한 맞춤형 추천과 경험자와의 소통 기능을 결합한 서비스를 기획했습니다.


### 🎯 목표 및 주요 기능

**데이터 기반 의사결정 지원**

공공 빅데이터와 데이터 분석을 통한 객관적인 지역 정보 제공
사용자 우선순위를 반영한 맞춤형 추천 알고리즘 적용


**귀농 커뮤니티 활성화**
실제 귀농인과 예비 귀농인을 연결하는 멘토-멘티 시스템 구축



### 🔧 기능 소개

서비스의 주요 기능들을 소개합니다.

#### ✅ 메인

메인화면에서 모든 서비스를 이용할 수 있음 

![image](/uploads/03a9b270aada745ab15c17af36628163/image.png){width=2137 height=1146}
![image](/uploads/9a41466e94dc97a3bdce77ae49947404/image.png){width=2136 height=975}
![image](/uploads/66f1f6d47409f2439d1ec4a90f4881b9/image.png){width=2126 height=883}

#### ✅ 회원가입

이메일과 비밀번호로 회원가입

![image](/uploads/4c1317059de606343e7b2e02608ab081/image.png){width=1377 height=1038}

#### ✅ 설문조사

맞춤형 리포트를 제공받기 위한 설문조사 

![image](/uploads/c8795bf729c2cc813dd44c6cc5acb176/image.png){width=1424 height=1014}
![image](/uploads/b32bca384034555c15e3002bf895012b/image.png){width=1275 height=582}


#### ✅ 지역 추천 리포트 

사용자가 한 설문조사를 기반으로 우선순위(환경, 교통, 인프라, 생활)에 따른 개인화된 지역 추천

![image](/uploads/8715edbef3b6ea7ff88d39a9ef02b6b2/image.png){width=1422 height=1131}
![image](/uploads/6a311e986ee41ada564f7cbfecdff4f8/image.png){width=1422 height=1131}


#### ✅ 작물 예상 수익 계산기

총 경지 면적과 작물을 선택하면 연간 예상 수확량과 월별 1kg당 매출 추이 및 예측 그래프 확인

![image](/uploads/66741214da58e878296f628e3bd241ed/어디가농_-_영상포폴_시연.mp4_snapshot_01.27__2025.06.04_15.13.19_.jpg)
![image](/uploads/eeff58827064c5328621e247264dea90/어디가농_-_영상포폴_시연.mp4_snapshot_01.31__2025.06.04_15.13.36_.jpg)


#### ✅ 마이페이지 
제공된 귀농 리포트, 예상 수익 리포트 조회 
회원 정보 수정 및 정보 조회 
![image](/uploads/52e7c52a2ae001f935ce4030f04b4b86/image.png){width=1212 height=830}
![image](/uploads/9abb4ac39fd8a2c275ef5cf7bfb33e9b/image.png){width=1220 height=824}

#### ✅ 멘토 & 멘티 
지도에서 지역 선택 후 멘토 조회
<img width="1212" alt="mentor1" src="https://github.com/user-attachments/assets/9ccadcf2-09a7-4d48-ada5-7d96c1cbb38f" />
<img width="1212" alt="mentor2" src="https://github.com/user-attachments/assets/6e95482b-f982-400d-b71a-4b0369712b0e" />

#### ✅ 실시간 채팅
실시간 채팅과 실시간 알림 조회 
<img width="1326" alt="chat" src="https://github.com/user-attachments/assets/497282b6-f61f-4314-8c08-51f029d84f48" />
<img width="1387" alt="alarm" src="https://github.com/user-attachments/assets/0f033784-9565-4c10-b7eb-d7a1555519ae" />

#### ✅ 멘토 등록
회원가입한 멘티는 멘토로 등록 가능
<img width="1142" alt="create" src="https://github.com/user-attachments/assets/e536a5f2-1574-46cf-b4c2-620ee4c1fa7c" />

#### ✅ 뉴스
Naver API로 실시간 뉴스 조회 
<img width="1362" alt="news" src="https://github.com/user-attachments/assets/12b166bf-9766-4838-b48a-fce1f6559049" />

#### ✅ 지원 정책 
웹 크롤링으로 데이터 수집 후 지역별 지원 정책 조회
<img width="1364" height="1478" alt="11-1" src="https://github.com/user-attachments/assets/235dfa8a-cabc-451a-b934-8ebbee4d68fc" />
<img width="1308" height="1086" alt="11-2" src="https://github.com/user-attachments/assets/84f5f4ed-d83e-41c2-bdd7-4c90b4c80ce4" />
<br>
<br>

## 📢 기술 스택 소개
#### Big-data distribution
![Hadoop](https://img.shields.io/badge/Hadoop-3.3.6-66CCFF?logo=apachehadoop)
![Spark](https://img.shields.io/badge/Apache%20Spark-3.5.0-E25A1C?logo=apachespark)
![Zeppelin](https://img.shields.io/badge/Zeppelin-0.10.1-2D2D2D?logo=apachezeppelin)
![Zookeeper](https://img.shields.io/badge/Zookeeper-3.7.1-7E3794?logo=apachezookeeper)

#### Frontend
![React](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-6.0.5-646CFF?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=000)
![Redux](https://img.shields.io/badge/Redux-Toolkit-764ABC?logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.3.3-38B2AC?logo=tailwindcss)

#### Backend 
![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.3-brightgreen?logo=springboot)
![JPA](https://img.shields.io/badge/JPA-Hibernate-59666C?logo=hibernate)
![JWT](https://img.shields.io/badge/JWT-Authentication-000000?logo=jsonwebtokens)
![Gradle](https://img.shields.io/badge/Gradle-7.6-02303A?logo=gradle)

#### Data Processing & ML
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.24-013243?logo=numpy)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4.1-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-11557C?logo=matplotlib)
![Jupyter](https://img.shields.io/badge/Jupyter-Lab-orange?logo=jupyter)

#### Build & Deployment
![EC2](https://img.shields.io/badge/AWS%20EC2-t3.medium-FF9900?logo=amazonaws&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker--Compose-2496ED?logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-Automation-D24939?logo=jenkins)
![Nginx](https://img.shields.io/badge/Nginx-1.27.4-009639?logo=nginx)

#### Database & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-336791?logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-7.2-DC382D?logo=redis)

#### Infrastructure
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?logo=ubuntu)
![Prometheus](https://img.shields.io/badge/Prometheus-Metrics-orange?logo=prometheus)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?logo=grafana)
<br>
<br>

## 🔍 시스템 아키텍처
<img width="792" alt="architect" src="https://github.com/user-attachments/assets/599d4f6d-6cea-45e0-9a98-2b62370fd9c7" /><br>
<br>

## 💾 ERD Diagram
<img width="903" alt="erd" src="https://github.com/user-attachments/assets/63473387-dfc6-4930-b6a0-abaa49beead3" /><br>
<br>

## 👥 우아한 자매들
우아한 자매들은 프론트엔드 3명, 백엔드 3명으로 구성된 팀입니다.
<img width="700" alt="Image" src="https://github.com/user-attachments/assets/67158e6e-08f1-4587-ac20-57be5e497968" /><br>
| Frontend | Frontend | Frontend | Backend | Backend | Backend |
|--------------|--------------|--------------|--------------|----------|--------------|
| 순화 👑 | 가영 | 미연 | 수비 | 시윤 | 나금 |

