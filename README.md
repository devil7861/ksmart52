# **Online Mock Exam Platform**  
온라인 모의고사 플랫폼  

---

## 📖 목차
1. [프로젝트 소개](#프로젝트-소개)  
2. [팀원 소개](#팀원-소개)  
3. [프로젝트 일정](#프로젝트-일정)  
4. [기술 스택](#기술-스택)  
5. [개발 환경](#개발-환경)  
6. [프로젝트 구조](#프로젝트-구조)  
7. [주요 기능 설명](#주요-기능-설명)  
8. [역할 분담](#역할-분담)  
9. [페이지별 기능](#페이지별-기능)  
10. [개발 중 고려 사항](#개발-중-고려-사항)  
11. [문서 저장 및 관리 방식](#문서-저장-및-관리-방식)  
12. [프로젝트 후기](#프로젝트-후기)  
13. [문의](#문의)  

---

## 📖 프로젝트 소개
이 프로젝트는 학생들이 온라인으로 모의고사를 보고 학습 성과를 평가할 수 있도록 돕기 위해 개발된 웹 플랫폼입니다.  
**주요 기능:**
- 사용자 회원가입 및 로그인 (학생 및 관리자)
- 다양한 과목별 문제 제공
- 시험 결과 분석 및 피드백 제공
- 관리자 페이지를 통한 문제 및 시험 관리

---

## 🧑‍💻 팀원 소개
| 이름   | 역할          | GitHub                                   | 이메일                |
|--------|---------------|------------------------------------------|-----------------------|
| 홍길동 | 팀장 / Backend | [GitHub](https://github.com/honggildong) | honggildong@example.com |
| 김철수 | Frontend      | [GitHub](https://github.com/kimchulsoo)  | kimchulsoo@example.com |
| 이영희 | DB 설계       | [GitHub](https://github.com/leeyeonghee) | leeyeonghee@example.com |

---

## 📈 프로젝트 일정
1. **요구사항 분석**: YYYY.MM.DD ~ YYYY.MM.DD  
2. **개발**: YYYY.MM.DD ~ YYYY.MM.DD  
3. **테스트 및 배포**: YYYY.MM.DD ~ YYYY.MM.DD  

---

## 🛠️ 기술 스택
### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![STS](https://img.shields.io/badge/STS-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Version Control
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Deployment
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

---

## 💻 개발 환경
- **IDE**: Spring Tool Suite (STS)  
- **운영체제**: Windows 10, macOS  
- **서버**: Tomcat 9  
- **DBMS**: MySQL 8.0  

---

## 📂 프로젝트 구조


```bash
📦 src/main 
┣ 📂 java/com/example/projectname 
┃ ┣ 📂 controller 
┃ ┣ 📂 service 
┃ ┣ 📂 repository 
┃ ┗ 📂 model 
┣ 📂 resources 
┃ ┣ application.yml 
┃ ┗ static 
┗ 📂 webapp 
┣ 📂 WEB-INF 
┃ ┗ views 
┗ index.html
```

- **controller**: 요청 처리 및 API 매핑  
- **service**: 비즈니스 로직  
- **repository**: 데이터베이스와의 상호작용  
- **model**: 도메인 클래스 및 DTO  

---

## ✅ **주요 기능 설명**
### **학생 기능**
- **회원가입 및 로그인**: JWT 기반 인증 및 사용자 권한 관리  
- **모의고사 보기**: 과목 선택 및 문제 풀이 기능  
- **시험 결과 확인**: 점수와 정답/오답 피드백 제공  

### **관리자 기능**
- **문제 관리**: 문제 추가/수정/삭제 가능  
- **시험 관리**: 시험 일정 설정 및 관리  
- **결과 분석**: 학생들의 시험 결과 데이터를 시각적으로 분석  

---

## 🛡️ **역할 분담**
- **홍길동 (팀장)**: 
  - Backend 개발 (Spring Framework 기반 API 설계 및 구현)  
  - CI/CD 파이프라인 구성  
- **김철수**: 
  - Frontend 개발 (HTML, CSS, JavaScript 기반 화면 설계 및 구현)  
  - 사용자 인터페이스 및 반응형 디자인 구현  
- **이영희**: 
  - DB 설계 및 데이터 모델링  
  - MyBatis 연동 및 SQL 최적화  

---

## 📄 **페이지별 기능**
| 페이지          | 주요 기능                                                              |
|------------------|-----------------------------------------------------------------------|
| **로그인**       | 사용자 로그인 및 인증, JWT 토큰 발급                                 |
| **회원가입**     | 학생 및 관리자 회원가입 기능                                         |
| **시험 목록**    | 과목별 시험 리스트 조회, 시험 시작 버튼                               |
| **문제 풀이**    | 문제 풀기 UI, 정답 선택 및 제출 기능                                  |
| **시험 결과**    | 시험 점수 및 정답/오답 분석 제공                                     |
| **관리자 페이지** | 문제 추가/수정/삭제, 시험 일정 관리                                  |

---

## 🌟 **개발 중 고려 사항**
1. **보안**:
   - 사용자 비밀번호 암호화 (BCrypt 사용)
   - 관리자와 학생의 권한 구분 및 접근 제어
2. **성능 최적화**:
   - MySQL에서 복잡한 쿼리를 사용해 데이터 조회 최적화
   - RESTful API의 응답 속도 개선
3. **에러 핸들링**:
   - 글로벌 에러 핸들러로 일관된 에러 메시지 제공
   - 클라이언트와 서버 간 명확한 상태 코드 반환  

---

## 📂 **문서 저장 및 관리 방식**
- **문서 형식**: PDF, Google Docs, Markdown  
- **저장 위치**: GitHub Repository 내 `/docs` 디렉토리  
- **관리 규칙**:
  - 프로젝트 설계 문서: `/docs/design/`  
  - 데이터베이스 스키마: `/docs/db/`  
  - API 명세서: `/docs/api/`  
  - 기타 개발 문서: `/docs/misc/`

---

## 💬 **프로젝트 후기**
- **홍길동**: *"처음으로 Jenkins를 사용해 CI/CD를 구성하며 배포 과정을 자동화해 보는 소중한 경험을 얻었습니다."*  
- **김철수**: *"프론트엔드 개발 시 사용자 경험을 개선하는 방법에 대해 고민할 수 있었던 뜻깊은 프로젝트였습니다."*  
- **이영희**: *"효율적인 데이터베이스 설계와 SQL 최적화의 중요성을 배우는 기회가 되었습니다."*

---

## 📧 **문의**
- 프로젝트 관리자: [홍길동](mailto:honggildong@example.com)  
- GitHub Repository: [Repository 링크](https://github.com/username/repository-name)
