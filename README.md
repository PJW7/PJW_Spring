
# 프로젝트 소개
온라인으로 강의를 등록하거나 수강할 수 있는 웹사이트.
강사로 등록한 회원은 강의를 등록하거나 수강할 수 있고 일반 회원은 수강만 가능하며, 관리자계정으로는 공지사항의 작성/수정/삭제를 할 수 있다.

* 개발기간: 2021.13 ~ 2021.02.19

* 개발환경
  + OS: Windows10
  + Tool: Spring Tool Suite 3
  + FrameWork: Spring, Maven, MyBais
  + Library: jQuery, ajax
  + DB: OracleDB
  + Language: HTML, CSS3, JSP, JavaScript, Java

#### 프로젝트 조원
+ 이○○(조장): 프로젝트 통합, 검색, 카테고리, 메인화면
+ 이○: 회원 가입/정보수정/탈퇴, 로그인, OT동영상 페이지, OT정보 등록/수정/삭제
+ 임○○: 강의 등록/수정/삭제, 로고 디자인, 강의 상세페이지
+ 박지원: 댓글&대댓글 작성/수정/삭제, 선호도, 강의 내 공지사항(커뮤니티), 공지사항
+ 조○○: 인기 강의, 오늘 본 강의, 강의 정렬 필터, 메인화면


# 프로젝트 페이지 별 기능 설명

### 메인페이지
![main](https://user-images.githubusercontent.com/59616321/109962501-9cf1ec00-7d2e-11eb-9c00-a99a4a417cac.png)
+ 강의를 인기순/오픈예정/최근 개설/오늘 본 목록으로 표시
+ 로그인/회원가입하기
+ 강의 카테고리 별로 이동
+ 공지사항으로 이동

### 강의소개 페이지
![classInfo](https://user-images.githubusercontent.com/59616321/109963087-5781ee80-7d2f-11eb-8e64-0c63bf5ec68e.png)
+ 강의 수강 신청
+ 강의 내 공지사항(커뮤니티) 작성(강의를 개설한 회원만 가능)
+ 댓글&대댓글
+ 좋아요&싫어요

### 마이 페이지
![mypage](https://user-images.githubusercontent.com/59616321/109962508-9ebbaf80-7d2e-11eb-9e26-845316216afa.png)
+ 개설(강사 회원만)/수강 중/최근 본/좋아요 누른 강의 목록 표시
+ 회원정보 수정/탈퇴
+ 강의등록/관리(강사회원만)

### 검색/카테고리 페이지
![cate](https://user-images.githubusercontent.com/59616321/109963030-4802a580-7d2f-11eb-933c-df8a72079f34.png)
+ 카테고리 분류 별 필터
+ 최신순/인기순/조회수순 정렬

### 공지사항 페이지
![noticeList](https://user-images.githubusercontent.com/59616321/109963043-4a64ff80-7d2f-11eb-9d9c-8001abc20e0e.png)
+ 공지사항 목록/작성
+ 공지사항 수정/삭제



# 구현 기능 설명
### 댓글 & 대댓글
![reply](https://user-images.githubusercontent.com/59616321/109964620-3f12d380-7d31-11eb-869c-cd04288839ba.png)
1. 댓글 목록을 불러올 때 버튼 태그의 onclick에 번호키를 매개로 함수를 호출하도록 설정.
2. ajax를 이용하여 비동기 방식으로 댓글&대댓글의 작성/수정/삭제 기능 구현.
3. 대댓글 작성 시 원댓글의 키번호를 가져와 그룹번호로 설정하여 묶어줌.

### 좋아요 & 싫어요
![pref](https://user-images.githubusercontent.com/59616321/109964626-41752d80-7d31-11eb-8272-e9a1fd46d642.png)
1. ajax를 이용하여 비동기 방식으로 강의에 대한 선호도(좋아요&싫어요) 기능 구현

### 강의 내 공지사항(커뮤니티)
![comu](https://user-images.githubusercontent.com/59616321/109964631-433ef100-7d31-11eb-9729-97758d4bca88.png)
1. 자신이 개설한 강의에만 커뮤니티를 작성할 수 있도록 구현.


### 공지사항 
![noticeList](https://user-images.githubusercontent.com/59616321/109964634-44701e00-7d31-11eb-8c89-b48eb80e5f01.png)
![noticeWrite](https://user-images.githubusercontent.com/59616321/109964638-45a14b00-7d31-11eb-8f1b-d3a63c06ee60.png)
![noticeCont](https://user-images.githubusercontent.com/59616321/109964644-476b0e80-7d31-11eb-9101-ac14ab6341d0.png)
1. 관리자로 공지사항 작성/수정/삭제가 가능하도록 구현.
2. 공ㅈ사항 게시글 별로 첨부파일 업로드&다운로드 구현.

------

