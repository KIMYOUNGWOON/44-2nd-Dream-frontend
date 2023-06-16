# 📍Dream - Frontend

<br>

• 위코드 44기 2차 프로젝트
<br>
한정판 리셀 거래 중개 플랫폼 KREAM을 모델링하여 레고 리셀 거래 중개 플랫폼 웹서비스 개발<br>
[결과물 시연 영상 링크](https://www.youtube.com/watch?v=UFuS91VcVp8)**

> 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.<br>
개발은 초기 세팅부터 전부 직접 구현했으며, 위 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

<br>

## 📍프로젝트 기간 & 인원
* 프로젝트 기간: 2주 (2023.04.20 ~ 2023.05.04)   
* 개발 인원:  
  `Frontend`: 최선영(Product Manager), 김영운, 조건호 <br>
  `Backend`: 박세익(Project Manager), 장다희, 김민서, 송석준 <br>
* [백엔드 Github 저장소](https://github.com/wecode-bootcamp-korea/44-2nd-Dream-backend)
* 모델링한 사이트: [KREAM](https://kream.co.kr/)
<br>

## 📍사용 기술

* FrontEnd   

 |React|JavaScript|styledcomponents|Rest|Prettier|
|---|---|---|---|---|
|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="52" height="52" /></div>| <div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" /></div>| <div style="display: flex; align-items: flex-start;"><img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white"> </div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/prettier-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="icon" width="65" height="65" /></div>|<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="icon" width="65" height="65" /></div>|
<br>



</div>

* 협업 <br>
<div style="display: flex; align-items: flex-start;">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/trello-0055cc?style=for-the-badge&logo=trello&logoColor=yellow">
<img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=Slack&logoColor=wihte">
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<br>
<br>


 ## flow
 
 <img width="500" alt="스크린샷 2023-05-07 오후 6 17 45" src="https://user-images.githubusercontent.com/121158293/236668841-92202a4a-31ab-4610-bf53-4c8b0d5229ca.png">


 ## 구현 페이지
 

### 1. 로그인
  
![Login](https://user-images.githubusercontent.com/126956430/246335675-b8b45999-a95a-4a93-932a-0790dcf0eca2.gif)

- KaKao에서 제공하는 API를 활용하여 user 로그인 기능을 구현했습니다.
  
<br>
  
### 2. 메인페이지
  
![Main](https://user-images.githubusercontent.com/126956430/246346154-6173812f-27e1-47df-8a3f-f9881292b668.gif)

- 메인 페이지 최상단 대배너는 캐러셀 기능을 사용하여 여러 이미지 또는 콘텐츠를 순환하면서 보여주는 슬라이드 형태로 구현했습니다. 사용자는 자동으로 변경되는 콘텐츠를 볼 수 있으며, 필요에 따라 이전 및 다음 버튼을 눌러 이동할 수도 있습니다.
- 메인 페이지에서 상품 리스트를 보여주는데 상품 리스트를 한 번에 모두 보여주는 대신, 스크롤을 이용한 페이지네이션을 구현하여 로딩 속도를 향상시켰습니다. 이를 통해 사용자는 초기 상품 목록을 보고 필요에따라 추가 데이터를 스크롤하여 가져올 수 있습니다.
- 상품 리스트를 효과적으로 보기 위해 쿼리스트링을 사용하여 필터 및 정렬 조건을 포함하여 서버에 GET 요청을 보냅니다. 사용자는 상품 카테고리, 연령, 난이도와 같은 필터를 적용하여, 좋아요 개수, 즉시 구매가, 즉시 판매가, 리뷰 수, 프리미엄 가격 등 다양한 방식으로 상품을 정렬할 수 있습니다. 특히 레고 제품 특성상 연령 및 난이도 가격 등을 고려할 일이 많은데 원하는 기준을 쉽게 필터링 할 수 있으며, 빠르고 간편하게 찾을 수 있습니다.
  


### 2. 로그인(Kakao Social Login)

<br> 
 
### 3. Search
 
 **상품 검색**
 
 **인기상품 검색**
 
<br>
 
### 4. 제품 필터

 
 <br>
 
### 5. Payment
 
 **구매 입찰**
 
 **즉시 구매**
 
 **판매 입찰**
 
 **즉시 판매**
 
 <br>
 
### 6. Likes
 
 <br>
 
 ### 7. Reviews
 
 **CREATE :**
 
 **READ :**
 
 **UPDATE :**
 
 **DELETE :**
  
   ## 6. 느낀점/회고
 > 2차 프로젝트 회고록: https://youngwoonkim.tistory.com/11
  <br>
  
 ## Reference

- 이 프로젝트는 [KREAM](https://kream.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
 
