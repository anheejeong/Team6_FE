# 🧑‍💻 Team6_FE_Week 4 & 5

## 4주차 개발 내용


### 📌 주요 기능

    Issue#22 레이아웃 UI 구현
    
프로젝트에서 공통으로 사용되는 레이아웃 UI 구현

- 사이드 네비게이션, 그룹 섹션, 페이지, 친구 섹션

- 반응형 디자인 적용 x

- overflow-y scroll 적용은 #23 에서 해결


    Issue#29 폰트 적용
  
프로젝트에서 공통으로 사용되는 폰트를 IBM Plex Sans KR로 적용

- 200: light
  
- 300: medium(기본)
  
- 600: bold


    Issue#23 멤버 목록 UI 구현
  
공통 레이아웃의 우측 사이드 섹션인 멤버 목록을 보여주는 UI 구현

- 멤버 타입 zustand로 state 관리
  
- 친한 친구 선택 구현


    Issue#27 쿠키 주기 페이지 UI 구현
  
메인 섹션 메인 페이지 쿠키 주기 섹션 UI 구현

- 질문 텍스트, 선택 버튼 구현
  
> **PR 해결**

> [x] 질문 / 프로필 컴포넌트 분리 해결

> [x] 하드코딩 변수화 해결

> [x] dummy data api response 형식 맞출 것

> [x] 기능에 따라 파일 분리 후 메인 index.tsx 파일에서 import 할 것

> [ ] 프로필 보여주는 코드 하나로 묶어서 중복 코드 제거할 것



    Issue#24 마이페이지 UI 구현
    
메인 섹션 마이페이지 UI 구현

- 프로필 : 배경이미지, 프로필이미지, 이름, 설명, 편집, 포인트, 투데이 visit, 토탈 visit 구현
  
- 오븐메뉴 : 나의 오븐 메뉴 섹션 구현
  
- 네비게이트 : 마이페이지 타이틀과 뒤로가기 구현
  
- 메인 섹션 overflow-y scroll 지정


### 🛠️ 수정 사항

    Issue#11 프로젝트 세팅 추가
    
react-router-dom 추가, alias 절대경로 @/ 세팅


    Issue#36 카드 버튼 컴포넌트 수정
    
화면에 맞게 컴포넌트 크키와 아이콘 위치 수정

> **PR 해결**

> [x] 규칙 비활성화 자체에서 코드 구조 변경

> [x] props spread에서 destructuring 형식으로 변경

> [x] emotion css 작성 형태 가독성 고려하여 변경


 Issue#21 props 타입 지정 interface로 통일
 
props의 타입 지정시에 type과 interface가 혼용되어 interface로 통일


## 5주차 개발 내용


### 📌 주요 기능


    Issue#40 그룹 섹션 구현
    
프로젝트에서 공통으로 사용되는 좌측 사이드 레이아웃 그룹 섹션 UI 구현

- 선택 그룹 store 저장

- hover tooltip 적용


    Issue#28 채팅 컴포넌트 구현

프로필 질문에서 사용할 채팅 박스 컴포넌트 구현

- left, right 선택 가능

- 채팅, 날짜 띄우기


    Issue#51 그룹 페이지 UI 구현

그룹 페이지 UI를 구현

- leader, member에 따라 UI 적용


### 🛠️ 수정 사항


    Issue#45 페이지 레이아웃 리팩토링

프로젝트에서 공통으로 사용되는 페이지 레이아웃 UI 리팩토링

- 프로필 질문 레이아웃 구현
 
- 레이아웃 선택 가능
 

    Issue#43 프로필 버튼 그리드 재사용하도록 수정

코드 재사용성을 위해 분리

- Issue#27 PR comment 해결

- 코드 중복성 제거


    Issue#49 컬러 팔레트 수정

필요 색상 추가

- 색상 추가 및 수정

- 컬러 모듈화


    Issue#47 페이지 레이아웃 컴포넌트 분리

페이지 레이아웃에서 공통으로 사용되는 UI를 모듈화

- 활성/비활성 유무 전달

- navigate 적용


    Issue#56 카드 컴포넌트 설명 부분 수정

카드 컴포넌트의 description 줄바꿈을 추가

- max-width를 지정
