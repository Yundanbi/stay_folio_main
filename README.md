# StayFolio site (Team Project - 개인 포트폴리오 정리)

> **팀 프로젝트 중 제가 직접 담당한 부분을 중심으로 정리한 포트폴리오 버전입니다.**  
> 전체 프로젝트 및 팀 PPT는 [팀 레포 바로가기](https://github.com/Spring-team-Project2025/stay_folio_main) 에서 확인 가능합니다.

---

## 📖 프로젝트 개요
StayFolio 사이트를 벤치마킹하여 **숙소 예약 시스템**을 구현한 팀 프로젝트입니다.  
저는 **예약 기능, 비회원 예약 취소, 숙소/객실 검색 및 페이징 처리**를 중심으로 개발했습니다.  

---

## 🛠 Tech Stack
- **Frontend**: JavaScript 
- **Backend**: Spring MVC, MyBatis, Oracle DB  
- **Tools**: Git, GitHub, SourceTree  
- **ETC**: PortOne (결제 API), Selenium (크롤링)

---

## 🔑 담당 기능
### 1. 예약 로직 구현
- 체크인/체크아웃 날짜 처리
- 숙박일수 및 인원별 요금 계산
- 할인율 적용 및 총 결제 금액 산출
- 예약 완료 시 예약번호 자동 생성 (MyBatis `<selectKey>` + Oracle 시퀀스)

### 2. 비회원 예약 조회/취소
- 이메일 인증 기반 비회원 예약 조회 기능
- 비회원 본인 확인 후 취소 처리 로직 구현

### 3. 숙소 검색 
- 카테고리 및 파라미터 기반 검색 (카테고리, 날짜, 인원수)
- 검색 결과에 따른 숙소 리스트 출력
- JSP 기반 페이징 처리 로직 적용

---

## 🖥️ 구현 화면
| 기능 | 화면 |
|------|------|
| 예약 페이지 | ![예약결제](https://github.com/user-attachments/assets/d24139c0-ba2a-4218-a003-5351e384b482)|
| 비회원 예약 취소 | ![cancel](./docs/images/cancel.png) |
| 숙소 검색 결과 |![검색 쿼리 mp4](https://github.com/user-attachments/assets/370199b8-0ec9-4d7a-8c29-6b0360bdc8e3)|

---

## 📚 배운 점
- MyBatis `<selectKey>`와 Oracle 시퀀스를 활용한 **중복 없는 예약번호 생성 방식** 학습  
- AJAX와 JSP/JSTL을 결합해 **검색 파라미터와 페이징을 동적으로 처리하는 방법** 습득  
- 세션과 파라미터를 활용한 **비회원 예약 본인 확인 로직** 구현 경험  
- GitHub 협업 과정에서 **브랜치 충돌 해결** 및 Pull Request 활용법 체득  

---

## 🚀 느낀 점
- 팀 프로젝트에서 제 역할을 명확히 수행하면서도, 다른 파트와의 연동을 위해 **협업의 중요성**을 크게 느꼈습니다.  
- 단순한 기능 구현을 넘어, **실제 서비스에서 필요한 예외 상황 처리**(중복 예약 방지, 본인 확인, 결제 실패 대응 등)에 신경 쓰는 것이 중요하다는 것을 배웠습니다.  
- 프로젝트 이후, **검색 최적화, 테스트 코드 작성, 소셜 로그인** 같은 기능을 더 보완하고 싶다는 생각이 들었습니다.  

---

## 📎 참고
- 전체 팀 프로젝트 레포: [Spring-team-Project2025/stay_folio_main](https://github.com/Spring-team-Project2025/stay_folio_main)  
- 개인 PPT: [docs/개인발표자료.pdf](./docs/개인발표자료.pdf)  


<img width="1280" height="720" alt="슬라이드1" src="https://github.com/user-attachments/assets/b951c5d6-dfa7-4a2c-840f-069e02060ee5" />
<img width="1280" height="720" alt="슬라이드2" src="https://github.com/user-attachments/assets/7b5be27f-f26e-49c5-8ca8-53543ce8e17c" />
<img width="1280" height="720" alt="슬라이드3" src="https://github.com/user-attachments/assets/0fcbefce-1644-4bad-bc1d-989493c14de9" />
<img width="1280" height="720" alt="슬라이드4" src="https://github.com/user-attachments/assets/69426146-0035-4e11-a7bf-eb68e3737f89" />
<img width="1280" height="720" alt="슬라이드5" src="https://github.com/user-attachments/assets/a913e693-62d4-4fe4-b65f-8a7bb418f81f" />
<img width="1280" height="720" alt="슬라이드6" src="https://github.com/user-attachments/assets/d1deaba0-cf64-4c11-909b-d0322548ec00" />
<img width="1280" height="720" alt="슬라이드7" src="https://github.com/user-attachments/assets/4018da94-4930-437d-9fc7-7c4d40a5d516" />
<img width="1280" height="720" alt="슬라이드8" src="https://github.com/user-attachments/assets/63f0b15e-6c84-413f-a53d-56fc9bce70a9" />
<img width="1280" height="720" alt="슬라이드9" src="https://github.com/user-attachments/assets/a2a153cd-3010-4acd-9766-8075972958b4" />
<img width="1280" height="720" alt="슬라이드10" src="https://github.com/user-attachments/assets/87e98d53-bdbd-48f6-a373-f4c9fe04f65b" />
<img width="1280" height="720" alt="슬라이드11" src="https://github.com/user-attachments/assets/b22bbd88-d0ad-4dbe-8aec-cee3b4389e92" />
<img width="1280" height="720" alt="슬라이드12" src="https://github.com/user-attachments/assets/f3b885b6-197a-4d77-802c-1bedde387c7d" />
<img width="1280" height="720" alt="슬라이드13" src="https://github.com/user-attachments/assets/d529a41e-80b5-4d9a-a146-fc6b35417d8f" />
<img width="1280" height="720" alt="슬라이드14" src="https://github.com/user-attachments/assets/95ef722f-b3f4-4cf3-9a60-d18c8ab577dc" />
<img width="1280" height="720" alt="슬라이드15" src="https://github.com/user-attachments/assets/bf806db3-e56b-4d56-9696-46ece9a302df" />
<img width="1280" height="720" alt="슬라이드16" src="https://github.com/user-attachments/assets/c5011244-2a00-4892-b7dd-2df098436c02" />
<img width="1280" height="720" alt="슬라이드17" src="https://github.com/user-attachments/assets/2f4a27d8-a575-4297-a92a-0e6577303b12" />
<img width="1280" height="720" alt="슬라이드18" src="https://github.com/user-attachments/assets/8713cff1-faf1-4b26-a0f5-eb8663ac2477" />
<img width="1280" height="720" alt="슬라이드19" src="https://github.com/user-attachments/assets/84315164-df3b-4119-81b2-8c02281cee16" />
<img width="1280" height="720" alt="슬라이드20" src="https://github.com/user-attachments/assets/a6e7af3a-fd07-489d-a2ee-468765a9edae" />
<img width="1280" height="720" alt="슬라이드21" src="https://github.com/user-attachments/assets/360a277d-b339-4cab-a40a-ffb0310ec923" />
<img width="1280" height="720" alt="슬라이드22" src="https://github.com/user-attachments/assets/2e5964a0-f00c-49fd-98e9-7a0e4290f0b9" />
<img width="1280" height="720" alt="슬라이드23" src="https://github.com/user-attachments/assets/f41b8601-a4c1-43f8-99b1-a10f0d2ff95d" />
<img width="1280" height="720" alt="슬라이드24" src="https://github.com/user-attachments/assets/a28da08e-15b8-4e19-83f2-a0252f7301ef" />
<img width="1280" height="720" alt="슬라이드25" src="https://github.com/user-attachments/assets/625b3d9a-ec59-4115-a26b-3b30d74199f2" />
<img width="1280" height="720" alt="슬라이드26" src="https://github.com/user-attachments/assets/28b26229-d39c-4f3c-8a23-81e30af9129a" />
<img width="1280" height="720" alt="슬라이드27" src="https://github.com/user-attachments/assets/9d2f222a-c443-453d-9fc2-f6a4706f8759" />
<img width="1280" height="720" alt="슬라이드28" src="https://github.com/user-attachments/assets/3250e9de-9d15-4648-83f4-efb4d94f8d52" />
<img width="1280" height="720" alt="슬라이드29" src="https://github.com/user-attachments/assets/c858983a-c2ea-474b-b30b-434189e2145b" />
<img width="1280" height="720" alt="슬라이드30" src="https://github.com/user-attachments/assets/60e799db-4e7d-4e7b-8ba8-5e79681e0ac2" />
<img width="1280" height="720" alt="슬라이드31" src="https://github.com/user-attachments/assets/e7f028a2-cbb3-4184-84cf-49b6f95fd6d1" />
<img width="1280" height="720" alt="슬라이드32" src="https://github.com/user-attachments/assets/b1b523be-5274-4f89-8b07-5445fb4f14e2" />
<img width="1280" height="720" alt="슬라이드33" src="https://github.com/user-attachments/assets/ed4e8333-caef-4648-a8dc-b71a15efccfc" />
<img width="1280" height="720" alt="슬라이드34" src="https://github.com/user-attachments/assets/ad9dccd2-b52c-4ff3-80ee-a7de572591b9" />
<img width="1280" height="720" alt="슬라이드35" src="https://github.com/user-attachments/assets/e3610472-fb58-4878-924d-c29e5913c9a8" />
<img width="1280" height="720" alt="슬라이드36" src="https://github.com/user-attachments/assets/daeafa10-1271-4717-a387-1aab01a56246" />
<img width="1280" height="720" alt="슬라이드37" src="https://github.com/user-attachments/assets/7a0b71ae-2736-4657-a747-03d0b7d39beb" />
<img width="1280" height="720" alt="슬라이드38" src="https://github.com/user-attachments/assets/30553a02-8f43-4617-9c75-6447b8b21715" />
<img width="1280" height="720" alt="슬라이드39" src="https://github.com/user-attachments/assets/c6721951-527f-4be6-bbab-12d4aaf22084" />
<img width="1280" height="720" alt="슬라이드40" src="https://github.com/user-attachments/assets/04870aca-babb-43f6-b738-093c966720ac" />
<img width="1280" height="720" alt="슬라이드41" src="https://github.com/user-attachments/assets/c5fbacdf-647b-4ad5-b966-b4872894ae4f" />
<img width="1280" height="720" alt="슬라이드42" src="https://github.com/user-attachments/assets/d0570bef-96c6-4337-b1b7-9e5af31a360e" />
<img width="1280" height="720" alt="슬라이드43" src="https://github.com/user-attachments/assets/aa077bfc-9070-436a-aa60-e1004dd704ea" />
<img width="1280" height="720" alt="슬라이드44" src="https://github.com/user-attachments/assets/7a82c3f1-6c41-4aba-96c8-b2b98c733611" />
<img width="1280" height="720" alt="슬라이드45" src="https://github.com/user-attachments/assets/29db3b96-0b2a-46de-bbc3-169300e029b9" />
<img width="1280" height="720" alt="슬라이드46" src="https://github.com/user-attachments/assets/dc9f9c15-93be-4a74-9baa-d6e501c973ed" />
<img width="1280" height="720" alt="슬라이드47" src="https://github.com/user-attachments/assets/f93e6725-b7d1-4bc1-8cab-d95923800cf2" />
<img width="1280" height="720" alt="슬라이드48" src="https://github.com/user-attachments/assets/c20d7e3a-0d1a-4fb8-b352-e61f4433ff4c" />
<img width="1280" height="720" alt="슬라이드49" src="https://github.com/user-attachments/assets/a332930e-e6b6-4683-a482-74113a63b1e9" />
<img width="1280" height="720" alt="슬라이드50" src="https://github.com/user-attachments/assets/8ae1c6be-7a10-4f32-8fd9-ccb0bca1bf3c" />
<img width="1280" height="720" alt="슬라이드51" src="https://github.com/user-attachments/assets/1d3561ce-76da-4854-9d0b-21e6d1020f71" />
<img width="1280" height="720" alt="슬라이드52" src="https://github.com/user-attachments/assets/9fcf81b0-3b2c-43f7-ae80-5eb993c6238f" />
<img width="1280" height="720" alt="슬라이드53" src="https://github.com/user-attachments/assets/978e0059-c2f2-445d-912c-686606d4974d" />
<img width="1280" height="720" alt="슬라이드54" src="https://github.com/user-attachments/assets/42508d1f-6656-45a8-aabf-88c92c030cb5" />
<img width="1280" height="720" alt="슬라이드55" src="https://github.com/user-attachments/assets/977ae645-9ae2-4b98-8028-31853b344922" />
<img width="1280" height="720" alt="슬라이드56" src="https://github.com/user-attachments/assets/28d59ecb-1ea9-4848-b0d8-4aa496d503e1" />
<img width="1280" height="720" alt="슬라이드57" src="https://github.com/user-attachments/assets/750d9c96-01d9-4661-8010-513e783e740f" />
<img width="1280" height="720" alt="슬라이드58" src="https://github.com/user-attachments/assets/8f9b507f-f05a-4d8f-8efc-9eb33c592933" />
<img width="1280" height="720" alt="슬라이드59" src="https://github.com/user-attachments/assets/02589eca-354c-4642-97f3-30670f054eed" />
<img width="1280" height="720" alt="슬라이드60" src="https://github.com/user-attachments/assets/f2f16470-7282-46a1-85af-f084dd84bf01" />
<img width="1280" height="720" alt="슬라이드61" src="https://github.com/user-attachments/assets/add4ed29-1525-4a23-9ee7-c9d118cf399d" />
<img width="1280" height="720" alt="슬라이드62" src="https://github.com/user-attachments/assets/c1f853b7-65c5-4cef-9457-0d0ba2bad82d" />
<img width="1280" height="720" alt="슬라이드63" src="https://github.com/user-attachments/assets/eda69e59-130a-4262-9e76-8b1a22a7b543" />
