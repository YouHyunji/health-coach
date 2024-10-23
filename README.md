# 🏃Health-coach
**멀티 클라우드 아키텍처를 활용한 건강관리 통합 플랫폼**
- 개인 운동 기록 관리, 건강 및 운동 관련 커뮤니티 기능, 운동 물품 중고 거래 서비스를 제공
- NHN Cloud와 AWS를 활용하여 사용자에게 안전하고 확장 가능한 서비스를 제공하며, 안정적으로 작동하도록 설계

<br />

## **📝 프로젝트 개요**

> **프로젝트:** 멀티 클라우드 기반 건강관리 플랫폼 Health Coach 웹 사이트
> 
> **팀명:** SimpleNet
> 
> **팀원:** 홍성재(팀장), 유현지, 이동호, 이동균, 이성현
> 
> **분류:** 협업 프로젝트
>
> **제작 기간:** 2024.08.05 ~ 2024.08.31 ※ 클라우드 비용 문제로 운영 중단
>
> **주요 웹 서비스:** 개인 운동 기록 관리, 건강 및 운동 관련 커뮤니티, 운동 물품 중고 거래
>

<br />

### 👉 주요 기능 (인프라)

- **멀티 클라우드 아키텍처:**  <br />
**NHN Cloud**와 **AWS**를 통합하여 고가용성과 확장성을 갖춘 인프라를 구축 <br />
각 클라우드는 **MySQL 복제**를 통해 데이터를 동기화하여, 장애 발생 시에도 서비스를 지속할 수 있도록 보장 <br />

- **장애 조치 및 트래픽 관리:** <br />
**Route 53**을 사용하여 DNS 관리를 수행하고, <br />
  장애 발생 시 자동으로 다른 클라우드로 트래픽을 전환하는 장애 조치 기능을 통해 서비스의 안정성을 보장 <br />
**CDN**을 활용하여 클라이언트가 웹 콘텐츠를 빠르고 안정적으로 제공받을 수 있도록 설계 <br />

- **로드 밸런싱 및 자동 확장:** <br />
NHN Cloud와 AWS에서 각각 **로드 밸런서**와 **자동 확장(Auto Scaling)** 기능을 사용하여 <br />
사용량이 급증하더라도 안정적으로 서비스가 유지되도록 지원 <br />

- **보안 강화:** <br />
**Site-to-Site VPN**을 사용해 NHN Cloud와 AWS 간 안전한 네트워크 통신을 보장


<br />

### 👉 웹 서비스 소개

##### 개인 운동 기록 관리

 - 사용자가 수행한 운동을 기록할 수 있으며 각 운동 시간을 그래프를 통해서 시각적으로 확인할 수 있습니다.

![마이페이지 운동기록](https://github.com/user-attachments/assets/097240bc-7950-4ffc-811d-57828077a104)

##### 건강 및 운동 관련 커뮤니티

- 사용자들이 서로의 운동 및 식단 노하우를 공유하고, 건강한 라이프스타일을 지향하는 다양한 정보를 교류할 수 있는 커뮤니티 공간을 제공합니다.

![게시글 작성](https://github.com/user-attachments/assets/06ec599a-1b67-49fd-a424-3ae9ce1b70a1)
![게시글 목록](https://github.com/user-attachments/assets/8cc8f137-6625-410b-a7af-3978eaef9dde)

##### 운동 물품 중고 거래

- 운동 용품을 필요로 하는 사용자들이 저렴하게 구매하거나, 사용하지 않는 물품을 판매할 수 있는 중고 거래 기능을 제공합니다.

![경매 게시판](https://github.com/user-attachments/assets/38f8f3eb-7c55-4111-9e4a-55d802a1a49a)

---

<br />

### 👉 기술 스택
<div align=center> 
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/MYSQL-003545?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/redis-E34F26?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"> 
</div>

---

<br />

### 👉 ERD

![Untitled](https://github.com/user-attachments/assets/1396f9e4-1148-441b-a521-c04e863139cc)

---

<br />

### 👉 클라우드 아키텍처

![3차 프로젝트 아키텍처](https://github.com/user-attachments/assets/187551c3-cd8a-4ef5-b1b0-183cb1b8700f)


---

<br />

 ### 👉 레포지토리 정보
소스코드는 비공개로 유지되며, 이 레포지토리에서는 프로젝트 정보 및 아키텍처 다이어그램만을 제공합니다. <br />
소스코드에 대한 접근이 필요하신 경우, 별도의 문의가 필요합니다.
