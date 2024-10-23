# 🏃Health-coach
**멀티 클라우드 아키텍처를 활용한 건강관리 통합 플랫폼**
- 개인 운동 기록 관리, 건강 및 운동 관련 커뮤니티 기능, 운동 물품 중고 거래 서비스를 제공
- NHN Cloud와 AWS를 활용하여 사용자에게 안전하고 확장 가능한 서비스를 제공하며, 안정적으로 작동하도록 설계

<br />

## **📝 프로젝트 개요**
<br>
<br>

> **프로젝트:** 멀티 클라우드 기반 건강관리 플랫폼 Health Coach 웹 사이트
>
> **개발:** 홍성재(팀장), 유현지, 이동호, 이동균, 이성현
> 
> **분류:** 협업 프로젝트
>
> **제작 기간:** 2024.08.05 ~ 2024.08.31 ※ 클라우드 비용 문제로 운영 중단
>
> **주요 기능:** 개인 운동 기록 관리, 건강 및 운동 관련 커뮤니티, 운동 물품 중고 거래
>

<br />

### 👉 주요 기능

- **멀티 클라우드 아키텍처:** NHN Cloud와 AWS를 통합하여 고가용성, 확장성, 그리고 장애 대응 능력을 극대화하였습니다. 하나의 클라우드에서 장애가 발생하더라도 다른 클라우드를 통해 서비스가 지속적으로 제공됩니다.

- **데이터 동기화:** 두 클라우드 환경에서 MySQL 복제를 통해 데이터의 일관성을 유지합니다. 각 클라우드의 데이터베이스가 상호 동기화되어 사용자의 데이터가 안전하게 보관됩니다.

- **로드 밸런싱 및 자동 확장:** AWS와 NHN Cloud의 자동 확장(Auto Scaling) 기능을 활용하여 트래픽 증가 시에도 시스템이 원활하게 작동할 수 있습니다. 로드 밸런서를 통해 사용자의 요청이 적절하게 분산됩니다.

- **보안 강화:** Site-to-Site VPN을 사용해 두 클라우드 간 안전한 데이터 통신을 보장합니다. 각 클라우드의 방화벽 규칙과 접- 근 제어 목록(ACL)을 통해 보안을 강화합니다.

- **CDN(Content Delivery Network) 및 Route 53:** 클라이언트는 CDN을 통해 웹 콘텐츠를 빠르게 전송받을 수 있으며, Route 53을 통해 DNS 관리와 로드 밸런싱이 이루어집니다.

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
소스코드는 비공개로 유지되며, 이 레포지토리에서는 프로젝트 정보 및 아키텍처 다이어그램만을 제공합니다. 
소스코드에 대한 접근이 필요하신 경우, 별도의 문의를 통해 협의가 가능합니다.
