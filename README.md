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


 ## 거래 플로우
 
 <img width="500" alt="스크린샷 2023-05-07 오후 6 17 45" src="https://user-images.githubusercontent.com/121158293/236668841-92202a4a-31ab-4610-bf53-4c8b0d5229ca.png">


 ## 구현 페이지
 

### 1. 로그인
  
![Login](https://user-images.githubusercontent.com/126956430/246335675-b8b45999-a95a-4a93-932a-0790dcf0eca2.gif)

- KaKao에서 제공하는 API를 활용하여 user 로그인 기능을 구현했습니다.
  
<br>
  
### 2. 메인페이지
  
![Main](https://user-images.githubusercontent.com/126956430/246346154-6173812f-27e1-47df-8a3f-f9881292b668.gif)

- 메인 페이지 최상단 대배너는 캐러셀 기능을 사용하여 여러 이미지 또는 콘텐츠를 순환하면서 보여주는 슬라이드 형태로 구현했습니다. 사용자는 자동으로 변경되는 콘텐츠를 볼 수 있으며, 필요에 따라 이전 및 다음 버튼을 눌러 이동할 수도 있습니다.
  <br>
- 메인 페이지에서 상품 리스트를 보여주는데 상품 리스트를 한 번에 모두 보여주는 대신, 스크롤을 이용한 페이지네이션을 구현하여 로딩 속도를 향상시켰습니다. 이를 통해 사용자는 초기 상품 목록을 보고 필요에따라 추가 데이터를 스크롤하여 가져올 수 있습니다.
  <br>
- 상품 리스트를 효과적으로 보기 위해 쿼리스트링을 사용하여 필터 및 정렬 조건을 포함해 서버에 GET 요청을 보냅니다. 사용자는 상품 카테고리, 연령, 난이도와 같은 필터를 적용하고 좋아요 개수, 즉시 구매가, 즉시 판매가, 리뷰 수, 프리미엄 가격 등 다양한 방식으로 상품을 정렬할 수 있습니다. 특히 레고 제품 특성상 연령 및 난이도 가격 등을 고려할 일이 많은데 원하는 기준을 쉽게 필터링 할 수 있으며, 빠르고 간편하게 찾을 수 있습니다.

<br>
    
### 3. 검색 페이지
  
![Search](https://user-images.githubusercontent.com/126956430/246346060-9aee11e0-8c37-44c4-a326-66748ff09246.gif)

- 제품명에 포함된 키워드나 제품 카테고리명을 입력하여 검색하는 기능을 구현했습니다. 사용자가 입력한 키워드와 일치하는 제품을 찾아서 결과로 보여줍니다. 또한 검색시 키워드별 검색량을 누적하여 인기 검색어 순위를 실시간으로 업데이트하고, 검색창 하단에 상위 10개의 인기 검색어가 노출되도록 구현했습니다.
  
<br>

### 4. 제품 상품 페이지
  
![Detail](https://blog.kakaocdn.net/dn/bd5eNF/btsesb2eTIL/nWKBIPHfckqLnHw4MUEYm1/img.gif)

- 동적 라우팅을 구현하여 useNavigate 훅과 useParams 훅을 사용해 path parameter에 productId를 포함시켜 서버에 요청을 보내고 서버로부터 상품의 상세 정보를 받아오고, 해당 정보를 사용하여 제품 상세 페이지에 상품 정보를 표시합니다.
  <br>
- 사용자가 스크롤을 내리면 구매나 판매 버튼이 안보이게 되는데 이때 스크롤을 다시 위로 올려서 구매나 판매 버튼을 클릭하기 위한 번거로움을 덜어주기 위해 모달창을 활용하여 간단한 제품 정보와, 구매와 판매 버튼 등을 표시해줍니다. 이를 통해 화면 아래에서도 번거로운 스크롤 업 동작 없이도 구매 또는 판매 버튼을 누를 수 있으며, 모달창은 일시적으로 화면을 가리는 형태로 표시되기 때문에 사용자의 주의를 집중시켜 구매나 판매를 유도시킬 수 있도록 구현했습니다.
  
<br>

### 5. 구매/판매 동의 페이지
  
![Purchase](https://user-images.githubusercontent.com/126956430/246590599-f72fbf91-c0e8-48dc-870a-6617bad26149.gif)
![sale](https://user-images.githubusercontent.com/126956430/246590594-b036da4e-9665-4450-9b0b-0b11c4df62aa.gif)

- 사용자가 구매 또는 판매 버튼을 클릭하는 경우, 하나의 컴포넌트에서 구매 동의 페이지와 판매 동의 페이지를 각각의 UI로 표시하는 기능을 구현했습니다. 이를 통해 컴포넌트 재사용을 활용하여 중복 코드를 최소화했으며, 코드의 가독성을 높이고 유지 보수성을 개선했습니다. 코드의 재사용을 통해 개발 시간을 단축하고, 일관된 사용자 경험을 제공하는 것에 초점을 맞추었습니다.
- 구매 동의 페이지와 판매 동의 페이지에서는 사용자가 거래를 신중하게 결정할 수 있도록 첫 번째 동의에 체크하면 모달 창이 나타나고, 사용자에게 주의 메시지를 한 번 더 알려줍니다. 또한, 사용자가 모든 내용에 동의해야만 다음 페이지로 진행할 수 있는 버튼을 활성화하여 사용자가 명확한 동의 의사를 표시하도록 구현했습니다.
  
<br>

### 6. 즉시 구매/판매 및 입찰 페이지
  
![Purchase](https://user-images.githubusercontent.com/126956430/246592368-cf1774fd-9bb9-467a-9c3b-7d72d516e474.gif)
![sale](https://user-images.githubusercontent.com/126956430/246592372-bcd4107b-24f1-4df2-b85a-2b1f8879e9b8.gif)

- 해당 페이지에서는 "즉시 구매/판매", "구매/판매 입찰" 중에서 선택할 수 있는 간단한 버튼이 제공됩니다. 입찰을 선택한 경우, 사용자는 입찰가를 입력하고 입찰 기한을 설정할 수 있습니다. 입찰 기한은 오늘 날짜를 기준으로 몇 일 동안 입찰이 유효한지를 설정할 수 있으며, 기본적으로 30일로 설정되어 있습니다.
- 판매 입찰의 경우, 사용자는 입찰가를 입력하고 해당 입력 필드에서 포커스 아웃할 때 자동으로 수수료가 계산됩니다. 또한, 최종 정산 금액은 입찰가에서 수수료가 차감된 금액으로 표시됩니다.
  
<br>
  

  
   ## 6. 느낀점/회고
 > 2차 프로젝트 회고록: https://youngwoonkim.tistory.com/11
  <br>
  
 ## Reference

- 이 프로젝트는 [KREAM](https://kream.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
 
