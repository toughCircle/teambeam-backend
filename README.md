# 팀글벙글
팀글벙글은 프로젝트 일정 관리를 효율적으로 할 수 있도록 도와주는 협업 툴입니다.   
다양한 기능을 통해 팀원 간의 소통과 작업 관리를 원활하게 진행할 수 있습니다. 

## 기술 스택
### 백엔드
- Spring boot
- Spring Security
- Redis
- Socket io

### 프론트엔드
- React
- Next js
- TypeScript
- Socket io

## 프로젝트 구조
<p align="center">

  <img src="https://github.com/toughCircle/teambeam/assets/150303834/9fc958e1-3761-4d57-8bc5-2eb9ba16b17a" width="100%">
</p>

# 기능
## 메인페이지
### 1. 소셜 로그인 기능
https://github.com/toughCircle/teambeam/assets/150303834/96606333-a97a-44d1-a94a-83d51604b301
- 카카오 소셜 로그인 기능
- 이메일 가입은 인증코드를 통한 가입
- JWT 사용

### 2. 프로젝트 생성 & 참여
https://github.com/toughCircle/teambeam/assets/150303834/645299f9-cfc6-4f6c-9f9b-72a29f0f3856
- 프로젝트 생성 가능

https://github.com/toughCircle/teambeam/assets/150303834/76b596c1-51bc-45c9-9c3b-b00a315b350e
- 프로젝트에 초대 코드를 받으면 참여 가능

## 팀페이지
### 1. 투두리스트 만들기
https://github.com/toughCircle/teambeam/assets/150303834/77adc674-2264-426f-b658-178d679f67dd
- 투두리스트 만들기 가능
- 투두리스트는 상위, 중위, 하위로 구성됨

### 2. 캘린더 기능
https://github.com/toughCircle/teambeam/assets/150303834/1516495a-05ac-442f-b988-9e09a593b3b9
- 스케줄 생성 가능
- 캘린더에는 상위 투두의 일정들과 스케줄들이 표시됨

### 3. 채팅 기능
https://github.com/toughCircle/teambeam/assets/150303834/5757cb8e-e018-4b5d-8db4-603769e59a01
- 채팅 페이지에서 채팅 가능
- 특정 채팅에 답글을 달 수도 있음

### 4. 게시물 업로드 기능
https://github.com/toughCircle/teambeam/assets/150303834/18d5c124-cd3d-40d3-a8d9-ebc49d4f3ba3
- 게시물은 표, 게시물 두 형태로 업로드 가능

https://github.com/toughCircle/teambeam/assets/150303834/819a17bf-094b-4ff2-b080-abf15939dc36
- 게시물에 댓글 달 수 있음

https://github.com/toughCircle/teambeam/assets/150303834/913fb456-6aae-4bbb-8edc-66445153a7a4
- 게시물을 북마크 할 수도 있음

## 개인페이지
### 1. 개인페이지
https://github.com/toughCircle/teambeam/assets/150303834/b4ccc53f-cbd1-4eb6-ad6c-e26f4f00fb6a
- 내가 속한 프로젝트들에서 투두리스트와 스케줄을 가져와서 렌더링 해줌

### 2. 메모 기능
https://github.com/toughCircle/teambeam/assets/150303834/80042aa5-1751-49e9-bddb-c5d881dfc31f
- 개인적인 메모를 할 수 있음

### 3. 북마크 기능
https://github.com/toughCircle/teambeam/assets/150303834/e7c752cb-b86a-4918-ae03-404ba0a56532
- 내가 다른 프로젝트에서 북마크한 게시물들을 보여줌

## 알림
### 1. 공지 생성 알림
https://github.com/toughCircle/teambeam/assets/150303834/34860ea8-eb91-445c-80b8-3b78bc63396f
- 참여한 프로젝트의 공지가 생성되면 알림 생성
- 알림 클릭 시 해당 공지 조회 가능
- 조회 후 읽음 처리
- 알림 전체 삭제 기능

### 2. 하위 투두 알림
https://github.com/toughCircle/teambeam-backend/assets/150303834/7c5a23cb-d726-43d4-98cf-8a39b1fb6174
- 매일 자정 오늘 마감인 하위 투두를 조회하여 알림 생성

## 환경설정
### 1. 사용자 정보 수정
https://github.com/toughCircle/teambeam/assets/150303834/2bfbbe0d-a962-4eca-a9e1-8c49fa94b9cf
- 사용자 정보 수정 기능
- 이메일의 경우 인증 코드를 통해 사용자 이메일 정보 수정

### 2. 탈퇴 기능
https://github.com/toughCircle/teambeam/assets/150303834/2e814cbb-6cf3-490d-b8e8-56398dc73efb
- 탈퇴 클릭 시 탈퇴 처리 후 메인 페이지로 이동
