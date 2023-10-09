# :tada: Biscuit_teamProject
## :memo: 프로젝트 개요

* 프로젝트 기간 : 2023.08.01 ~ 2023.08.31

* 배포 주소 : http://ec2-3-39-189-163.ap-northeast-2.compute.amazonaws.com/biscuit-project

* 데모비디오 주소 : https://youtu.be/MqECvmNpCtI

* 프로젝트 PPT : https://github.com/anjxxyi/Biscuit_teamProject-Public/blob/develop/process/file/Biscuit_final-project_PPT.pdf

* 프로젝트 참여 인원
  > 안재이(팀장) : https://github.com/anjxxyi <br />
  > 김성은 : https://github.com/chickencoc <br />
  > 박종빈 : https://github.com/Jonville <br />
  > 권은지 : https://github.com/xxnjx <br />
  > 최현정 : https://github.com/hyungeongchoi2 <br />
 
* 프로젝트 소개

  > 비스킷은 누구나 간편하게 사용할 수 있는 도서 블로그 네트워크 서비스 웹 사이트입니다.
  > 단순히 책이나 글 등을 읽는 행위를 넘어 감상과 생각을 기록하고 공유하며
  > 풀리지 않았던 의문들을 독자끼리 함께 대화로 풀어내는 소통하는 광장을 만들고자 했습니다.

## :hammer: 사용 기술 스택

* 프론트엔드
  * <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5t&logoColor=white"/> <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  
* 백엔드
  * <img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white"/> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/spring_security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge"/> <img src="https://img.shields.io/badge/json_web_tokens-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/> <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  
* 개발 환경
  * <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"/> <img src="https://img.shields.io/badge/amazon_aws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  
* 협업 툴
  * <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"/>
  
* UI
  * <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/> <img src="https://img.shields.io/badge/adobephotoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white"/> <img src="https://img.shields.io/badge/adobeillustrator-FF9A00?style=for-the-badge&logo=adobeillustrator&logoColor=white"/>

## :wrench: 프로젝트 구성

### 아키텍처
![Biscuit_Architecture](https://github.com/chickencoc/Biscuit_teamProject-Public/assets/74812739/a9aea1d8-ada8-4be0-8f4b-c62151393c6f)

### ERD
![Biscuit_DB_ERD](https://github.com/chickencoc/Biscuit_teamProject-Public/assets/74812739/cbc6065f-bc8c-4b45-a242-cac5fe356648)

## :sparkles: 주요기능

### books
   Python crawling 기능을 이용해 책 정보 저장 
   bookclip 기능을 이용해 mypage 에서 저장한 책 정보 확인 및 삭제
### booklog
   CRUD 구현
   서로의 booklog 구독 및 취소 기능 
   글과 booklog search 기능 
### bookclass
   bookclass 참여 및 참여취소 기능 
   bookclass 개설 기능 
   admin : 개설한 bookclass 관리기능 
### Us, Earth
   중고도서 구매 
   중고도서 신청 
   admin : 신청한 중고도서 승인 
### goods
   goods 구매 
   admin : goods 등록 및 수정 및 상태 변경 
### event
   참여 및 취소 
   admin : event 등록 및 참여자 리스트 엑셀 파일다운로드 
### 회원
   회원가입, 로그인, 아이디, 비밀번호 찾기, 정보수정, 탈퇴 
   mypage bookclip, bookclass 현황, 주문내역 확인 
   admin : user 관리(탈퇴 및 복구, 권한) 



   
