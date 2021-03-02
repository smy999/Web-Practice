
# Clone Join Page


#### :calendar: 기한: ~ 2021.03.02
#### :globe_with_meridians: 원본 페이지: 네이버 회원가입 페이지
#### :globe_with_meridians: Clone 페이지:
![1](/uploads/8d160297736da04415662f06e7ba2aa6/1.PNG)

설명: 입력받는 form의 구조만 구현한 페이지로, 가입버튼을 눌러도 입력이 받아지거나, 이벤트 동작이 이루어지지 않는다.

------------------------------------------

### 구현 1. header
설명: NAVER logo 보여주기, logo를 클릭하면 해당 페이지 갱신
* a로 link 기능 구현, text-decoration : none, css로 이미지 링크 넣기

![header](/uploads/c0bfb6d13aa222355835c52b11ed6e70/header.PNG)

<br>

### 구현 2. form

#### 2-1. 아이디 & 비밀번호(+재확인)
설명: 아이디와 비밀번호를 입력하고 비밀번호를 재확인한다.
* 아이디 칸 안에 url(@naver.com) 넣기 >> sapn에 text 설정
* 비밀번호 칸 안에 자물쇠 이미지 넣기 >> span에 배경 설정
![id_pwd](/uploads/4b040e2186362382e2d44c1c35596c34/id_pwd.PNG)

<br>

#### 2-2. 이름 & 생년월일 & 성별
설명: 이름과 생년월일을 입력한다.
* 년: input >> text
* 월: select >> option >> value: months(1~12)
* 일: input >> text
* 성별: select >> option >> value: M, F
* 입력 칸에 placeholder로 입력칸 고정 글자 보여주기


![image](/uploads/6b3cba3a4dc84e1920a60e6ce8b02b38/image.png)

<br>

#### 2-4. 가입버튼
설명: 입력을 완료하면 가입버튼을 클릭한다.
* 버튼: button >> type: button

![image](/uploads/3cd2a77b692802d21266d87a3859c787/image.png)

<br>

### 구현 3. footer
설명: 회사정보, 권한 및 법률 명시
* ui안의 li 요소를 가로 및 가운데 정렬
* 네이버 로고 및 글자 굵기 조절

![image](/uploads/0818edfaaf4ff036b960f5c285571cf4/image.png)

<br>
