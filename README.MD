# Royale (주짓수대회 자동화 서비스)


📆 **프로젝트 진행기간 : 2022/10/10 - 2022/11/25** 

🎈 **팀원소개**

| 이름  | 역할                 |
| --- | ------------------ |
| 조찬홍 | Backend & Frontend |
| 안세영 | Backend & Frontend |
| 민경대 | Backend & Frontend |
| 이태엽 | UCC 제작 & 서류정리|


![image](https://user-images.githubusercontent.com/62234293/204180303-6d30643e-0713-4db5-a00a-431acfeed5c8.png)

---

## 01 서비스 소개

> #### 주짓수 대회 자동화 서비스
> 
> "Royale"은 아날로그로 진행되면서 발생하는 불편함들을 자동화한 서비스이다.

---

## 02 주요 기능

**❗ 스태프**

&nbsp;&nbsp;✔ 대회 생성

&nbsp;&nbsp;✔ 대회 참가 마감

&nbsp;&nbsp;✔ 대진표 생성

&nbsp;&nbsp;✔ 스코어보드 관리

&nbsp;&nbsp;✔ 선수 계체 관리

<br/>

**❗ 선수**

&nbsp;&nbsp;✔ 대회 참가 신청

&nbsp;&nbsp;✔ 스코어보드 조회

&nbsp;&nbsp;✔ 대회 현황 조회

---

## 03 담당 기능

✔ 대진표 알고리즘을 통한 자동 대진표 생성 및 조회

✔ 선수 개체 통과 구현

✔ Jenkins를 활용한 CI CD

✔ Docker와 Docker-compose로 컨테이너화

---

## 04 "Royale" 서비스 화면

#### **회원가입 및 로그인**

✨ **회원가입**
![image](https://user-images.githubusercontent.com/62234293/204178650-520fd7d3-0404-460f-a74d-53fc63230937.png)

✨ **로그인**
![image](https://user-images.githubusercontent.com/62234293/204178670-7d1beaf3-1bee-4f72-a1c1-8a526ea55376.png)

---

#### 메인페이지

![image](https://user-images.githubusercontent.com/62234293/204178700-45994e5a-d62d-43f6-ab3a-ec1527bb94c9.png)

---

#### 대회

✨ **대회신청**
![image](https://user-images.githubusercontent.com/62234293/204178789-cf4eceac-dc7e-46aa-8e99-d2e98b54e1eb.png)

✨ **개체통과**
![image](https://user-images.githubusercontent.com/62234293/204178927-241ab4b1-47d8-4fc5-862e-69009f4168eb.png)

✨ **대진표**
![image](https://user-images.githubusercontent.com/62234293/204178989-7fbf509d-f86b-419a-b328-b8310f81ba28.png)

✨ **스코어보드**
![KakaoTalk_20221128_114025927](https://user-images.githubusercontent.com/62234293/204180126-37cc8289-14eb-46cf-8ced-1a90c5e1fa32.gif)


---

## 05 개발환경

📌 **Backend**
- spring-boot 2.7.3
- spring-security 2.7.3
- docker 20.10.18
- docker-compose 2.1.0
- mysql 5.7
- nginx 1.23.1

📌 **Frontend**
- "npm": "8.19.3"
- "react": "18.2.0"
- "zustand": "4.1.4"
- "socket.io": "4.5.3"

---

## 06 서비스 아키텍처

![image](https://user-images.githubusercontent.com/62234293/204178568-c591e119-fc6f-4ae2-b8f5-8e10babf2837.png)

---


## 07 협업 툴

- **Notion**

![image](https://user-images.githubusercontent.com/62234293/204177389-eb8d3278-6ef7-462a-a40a-613c47118636.png)

- **Zira**
![image](https://user-images.githubusercontent.com/62234293/204180730-ca96a930-4088-4900-a37e-195ccf79654c.png)

---

## 08 서비스 설계

- **ERD**
  
  ![image](https://user-images.githubusercontent.com/62234293/204178034-a7bf3270-5a97-4bd3-a49a-f124e07f0ec7.png)

- **기능 명세서**

![image](https://user-images.githubusercontent.com/62234293/204178124-96e86a5a-bd1a-4d3e-bbb4-55361342b845.png)

- **Figma**

![image](https://user-images.githubusercontent.com/62234293/204178246-11e3b3ca-b81b-417d-aa69-ad005a669e6a.png)

- **Rest API**

![image](https://user-images.githubusercontent.com/62234293/204180205-7a0aafda-34d7-4345-8d3f-a39f8d5f601a.png)
