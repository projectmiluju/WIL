WIL   
항해99 8기 1주차의 끝과 2주차의 시작

2022/07/11 ~ 2022/07/17

KEYWORDS

JWT / API / TIL / WIL / Git_Github

항해를 시작했다. 아직 TIL도 제대로 쓰지 않았고 GITHUB에 글을 올리는 방법도 잘 모른채 첫 WIL을 쓰고 있다. 이렇게 쓰는 건 맞는건지 의문을 가득 가지고...

Beach Festival
http://sparta-rio.shop/

첫 풀스택 웹미니 프로젝트를 시작했다. 우리 팀원들은 곧 다가올 휴가 기간 해수욕장으로 여행을 가려는 갔다온 그런 사람들을 위해 해수욕장 사이트를 만들기로 했다.

기술 구현

회원가입 및 로그인, 프로필 수정 기능(모달 활용) JWT 공공데이터 open api 사용 리뷰 및 좋아요 기능 카카오 지도 삽입 검색 기능 paging 기능

문제 해결

공공 데이터 Open API 데이터 불러오고 Mongo DB에 저장

해결 : 각 지역의 데이터를 MongoDB에 json 형식으로 처음에 저장해서 DB에서 데이터를 불러와서 활용

Modal 기능에서 Input 태그가 focus가 안되는 현상

해결 : 중복으로 Modal이 뜨는 부분 때문에 생기는 문제라고 확인해서 이벤트가 발생하면 기존 Modal을 닫고 새로운 Modal을 여는 방법으로 해결

메인 페이지에 각각의 종목(해변)을 클릭하면 각각의 상세페이지가 열리고, 종목별로 리뷰를 다는 기능 구현에서 데이터 처리 고민

해결 : 각 Comment에 해당 게시글의 Key(상세페이지 Url 경로)값을 부여해서 조건식으로 게시글과 Comment가 일치하는 것만 상세페이지에서 보이도록 구현

홈페이지가 메인 페이지로 처음 들어가고, 로그인이 안된 상태이면 기능 제한 사항 부여

해결 : 쿠키에 Token키가 있으면, 기능 제한 풀어주는 방법으로 해결

로그인, 프로필 수정의 기능 Modal 구현

해결 : Bootstrap 기능 활용하여 Modal 구현

Local에서 작업한 파일이 AWS에 올리면 페이지 이동이 안되는 이슈

해결 : html 파일 내의 링크 경로 수정(기존 : "localhost:5000/detail~") -> (수정 : "/detail~")

한마디

token과 session 그리고 JWT...API...JSON....JINJA

처음엔 강의만으론 개념을 이해하기 어려운게 사실이었다

많은 구글링과 팀원들의 도움으로 그래도 무사히 프로젝트를 마칠 수 있었다

알고리즘
1주차가 끝나고 2주차의 시작은 알고리즘이었다...

대학을 다닐떄 이미 다른 언어로 경험이 있었기에 조금은 가벼운 마음으로 시작했지만

자바의 언어 특성상 막상 시작하니 마음은 어느새 무거워져 있었다...

아직 2주는 중간도 지나지 않았음으로 다믐 WIL에서 자세한 내용을 다루도록 하겠다..

돌아보기
항해를 한다..매일 이 스파르타라는 커다란 배에서 떨어지면 위험할까봐 구명조끼를 확인한다...

정신없는 한주를 보냈고 이제 새로운 한주를 맞이한다.

TIL과 WIL을 작성하기위해 많은 시간을 쓰진 않을 것이다.

하지만 원래 글을 쓰는 것에 관심이 있던 사람으로서 이런 가독성이 떨어지는 글을 쓰는 것이 용납되지 않는다

GITHUB을 다루는 법을 공부한다는 생각으로 다음 WIL을 쓰기전까지 README.MD를 어떻게 다루는지 공부해서

남들처럼 글을 써보도록 하겠다.