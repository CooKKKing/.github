# 쿡킹
<p align="center">
  <img src="https://github.com/user-attachments/assets/5f9699ed-8da4-4a3f-bdfc-3165668a34a3" alt="쿡킹_로고" />
</p>

<p align="center">
  <strong>CookKing</strong>은 사용자가 직접 레시피를 작성하고 공유하며,<br />
  도감 기능을 통해 나만의 요리 기록을 쌓아갈 수 있는 <strong>참여형 레시피 커뮤니티 플랫폼</strong>입니다.<br />
  단순한 정보 제공을 넘어, <strong>도전과제와 칭호 시스템</strong>으로 성취감과 재미를 더했고,<br />
  요리 초보부터 고수까지 모두가 즐길 수 있는, 따뜻하고 즐거운 요리 공간을 지향합니다.
</p>

## 🚩 개요
- **프로젝트 이름** : CookKing  
- **프로젝트 기간** : 2025.04.02 ~ 2025.05.01  
- **배포 주소** : 

<br><br>

## 🛠️ 기술 스택
### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=React%20Query&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=Tailwind%20CSS&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20Web%20Tokens&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)

### Infra & DevOps
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=white)

### Common
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black)

### Tools
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-8C4FFF?style=for-the-badge&logo=IntelliJ%20IDEA&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-F5F5F5?style=for-the-badge&logo=Notion&logoColor=black)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white)

<br><br>
## 📄 사용자 요구사항 정의서
[Cookking-요구사항_정의서](https://docs.google.com/spreadsheets/d/1I9c54LodUJKi1B3isNZSlxxLfGQ1CkP495pvu_4wkRo/edit?gid=0#gid=0)
<br><br><br>
## 📄 API 문서 (Swagger)
[Cookking-API문서_Swagger](http://ec2-54-180-8-125.ap-northeast-2.compute.amazonaws.com:8080/swagger-ui/index.html#)
<br><br><br>
## 🧩 ERD
![Cookking_ERD](https://github.com/user-attachments/assets/7af842d8-b7e4-4907-a705-c5cf503cb006)

<br><br>

## ✨ 주요 기능

**1. 회원가입 및 로그인**  
- 이메일 인증 기반 회원가입 (인증번호 전송 및 검증)  
- 닉네임 중복 체크 기능  
- JWT를 이용한 로그인 및 토큰 기반 인증 처리  
- 로그인 실패 및 인증 실패 시 사용자 알림 제공

**2. 레시피 작성 및 공유**  
- 요리 제목, 재료, 순서, 대표 이미지 업로드 기능  
- 레시피 카테고리 설정 및 상태 관리 (공개/비공개)  
- 레시피 수정 및 삭제 기능  
- 북마크(즐겨찾기), 좋아요 기능 지원

**3. 도감 기능**  
- 사용자가 직접 만든 레시피로 도감 카테고리 구성  
- 카메라 디자인 및 색상 선택하여 커스터마이징  
- 도감 메뉴별로 음식 이름 및 이미지 등록 가능  
- 도감 공개/비공개 설정

**4. 도전과제 및 칭호 시스템**  
- 조건을 만족하면 자동으로 도전과제 달성 및 칭호 획득  
- 칭호 장착 및 변경 가능  
- 마이페이지에서 도전과제 진행 현황 확인 가능

**5. 마이페이지**  
- 프로필 이미지, 닉네임, 포인트, 칭호 정보 확인  
- 내가 작성한 레시피, 북마크한 레시피 목록  
- 내가 획득한 도전과제 및 도감 메뉴 확인

**6. 결제 시스템 (밥풀)**  
- Toss Payments 연동으로 포인트(밥풀) 충전 가능  
- 10밥풀 = 1000원 기준 결제 시스템 구축  
- 충전 내역 확인 및 포인트 잔액 조회 가능

**7. 재료 기반 메뉴 추천 기능**  
- 사용자가 보유한 재료를 선택하거나 입력  
- 입력된 재료가 포함된 레시피들을 분석하여 관련 메뉴 추천  
- 추천된 메뉴 클릭 시 해당 메뉴의 전체 레시피 게시글 목록 확인 가능

<br><br>

## 🤝 프로젝트 인원

|![]()|![]()|![]()|
|------|---|---|
|채현후|홍성민|권택현|
|<팀장><br>-FrontEnd|<팀원><br>-FrontEnd|<팀원><br>-BackEnd|
