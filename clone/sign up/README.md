
# Clone Join Page


#### :calendar: 기한: ~ 2021.03.02
#### :globe_with_meridians: 원본 페이지: 네이버 회원가입 페이지
#### :globe_with_meridians: Clone 페이지:
![image](https://user-images.githubusercontent.com/33407191/109660234-f978ce00-7bab-11eb-801f-31a0733ca285.png)

설명: 입력받는 form의 구조만 구현한 페이지로, 가입버튼을 눌러도 입력이 받아지거나, 이벤트 동작이 이루어지지 않는다.

------------------------------------------

### 구현 1. header
설명: NAVER logo 보여주기, logo를 클릭하면 해당 페이지 갱신
* a로 link 기능 구현, text-decoration : none, css로 이미지 링크 넣기

![image](https://user-images.githubusercontent.com/33407191/109660308-07c6ea00-7bac-11eb-8874-7a0f82982daf.png)


<br>

### 구현 2. form

#### 2-1. 아이디 & 비밀번호(+재확인)
설명: 아이디와 비밀번호를 입력하고 비밀번호를 재확인한다.
* 아이디 칸 안에 url(@naver.com) 넣기 >> sapn에 text 설정
* 비밀번호 칸 안에 자물쇠 이미지 넣기 >> span에 배경 설정
![image](https://user-images.githubusercontent.com/33407191/109660360-19a88d00-7bac-11eb-8f16-1d4e437744d1.png)

<br>

#### 2-2. 이름 & 생년월일 & 성별
설명: 이름과 생년월일을 입력한다.
* 년: input >> text
* 월: select >> option >> value: months(1~12)
* 일: input >> text
* 성별: select >> option >> value: M, F
* 입력 칸에 placeholder로 입력칸 고정 글자 보여주기


![image](https://user-images.githubusercontent.com/33407191/109660398-2927d600-7bac-11eb-893b-d2654dcece1d.png)


<br>

#### 2-4. 가입버튼
설명: 입력을 완료하면 가입버튼을 클릭한다.
* 버튼: button >> type: button

![image](https://user-images.githubusercontent.com/33407191/109660433-36dd5b80-7bac-11eb-845a-0c9946148f97.png)


<br>

### 구현 3. footer
설명: 회사정보, 권한 및 법률 명시
* ui안의 li 요소를 가로 및 가운데 정렬
* 네이버 로고 및 글자 굵기 조절

![image](https://user-images.githubusercontent.com/33407191/109660479-42c91d80-7bac-11eb-837c-098a4f602ea1.png)


<br>
