# Final-report

https://raon-studio.tistory.com/4

위 링크로 이동해서 코드를 실행하시고 RUN이나 LOGCAT에서 키해시를 찾아서 저희에게 보내주시면 그걸 저희 계정 카카오api에 넣어야만 교수님 컴퓨터에서 동작이 가능합니다.

### 1. 제작동기<br>
  &nbsp; 브레인 스토밍을 하던 중 여느 카페에서 일하고 있는 팀원의 일담을 들어보았을 때, 키오스크가 많이 비치되어있지않아 줄을 서던 손님이 나가는 경우가 있었다고 한다.  이를 듣고  키오스크를 어플로 대체할 수 있으면 좋지 않을까 하는 생각을 하게 되었고 매장에 있는 키오스크의 회전율을 높이기 위한 앱을 제작하기로 하였다.<br>
 ##### &nbsp; <앱의 이름은 ‘카페in’으로, 커피의 성분인 카페인과 '카페 안에서'라는 이중적인 의미를 가지고 있다.><br> 

### 2. 앱의 기능<br>
 앱의 기능은 크게 세가지로 나눌 수 있다.<br>
  ####  &nbsp; 자사의 앱을 사용한 주문이 아닌 모든 카페를 손안에서 주문할 수 있는 기능<br>
      -카페에서 앱으로 주문시 자사의 앱을 설치해야되는 불편함을 줄여 따로 설치없이 한 개한 앱에서 다양한 카페를 주문할 수 있다. 
  ####  &nbsp; 랜덤으로 가게를 추천해주는 기능<br>
      -요즘 선택의 대한 고민을 하는 사람들이 많다. 이를 해결하면서 자그마한 재미를 줄 수 있는 랜덤 기능을 넣었다.
      랜덤으로 선택된 가게가 나오면 그 가게의 주문서로 연결해준다.
  ####  &nbsp; 가게에 문의를 할 수 있는 기능<br>
      -단층으로 되어있는 가게가 아닌 여러 층으로 구성되는 카페에서 문의를 위해 이동하는 번거로움을 줄여줄 수 있는 편리함을 준다.         앉아서 카운터로 문의하는 편리함을 느낄 수 있을 것이다.


### 3. 사용법<br>
 &nbsp; 이 앱은 카카오톡을 연동하여하는 앱인만큼 카카오톡 연결이 필요하다.<br>
 <img src = "https://user-images.githubusercontent.com/75411735/121114645-03ffcf00-c84f-11eb-99fa-3158c6febde3.png" width="300" height="500"><br>
카카오톡으로 로그인 후 주문이 가능하다. 주문을 하기 위해 카페를 먼저 선택해야한다. 카페선택을 클릭 후 여러 매장 중 원하는 매장에 들어간다. 주문할 메뉴를 선택 후 요청사항(필수 아닌 선택)을 입력하면 주문이 포스기로 들어간다. 주문한 내역은 주문내역에서 확인 가능하다. 랜덤, 문의 기능도 버튼클릭으로 사용가능하다.

### 4. 아쉬운 점<br>
  #### -비용의 문제<br>
  &nbsp; 앱의 실행 순서에서 가장 마지막 단계인 알림을 받는 기능을 구현하고자 하였다. 하지만 카카오톡 알림을 가져와 프로그래밍하는 과정에서 알림 사용을 위해서는 비용을 지불해야된다. 비용지불의 문제로 앱에 알림을 실행시키지못한 것이 아쉬웠다. 
  #### -머신러닝 시도 중 성공하지 못함<br>
  &nbsp; 또 다른 아쉬운 점은 사용자가 특정 음료를 자주 주문하면 그 음료와 비슷한 종류의 음료들을 추천해주는 기능을 넣으려하였다. 하지만 머신러닝을 하는 과정에서 음료에 대한 대량의 데이터을 모으지 못하였다. 결국 영화데이터를 다운받아 돌려보게 되었다. 데이터를 많이 모아 카페음료로 돌려보지 못한 것에 대한 아쉬움이 남는다.

### 5. 앱의 수익창출방향<br>
이 앱은 여러 브랜드가 모여있어서 많은 기업, 가게들과의 연결이 필요하다. 이 앱을 가게에 연결하여 중개수수료를 통하여 수익일 낼 생각이다. 또한 앱 하단에 광고를 넣어 광고수익도 낼 계획이다.
