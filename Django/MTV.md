개발은 혼자 하지 않는다

보안

개발자는 반드시 실수한다

Front End HTML // CSS

Back End 데이터처리

장고는 좀더 세분화돼서 3파트로 나눠서 작업할 수 있도록 디자인 돼있다.

이러한 디자인 패턴을 MTV라고한다. 

Model Template View

쉽게말해서 T는 프론트앤드 M과 V는 백앤드라고 생각하면됨.

1. Template

→ 사용자가 보이는 영역 html css 템플릿 언어 .. js로 동작 컨트롤 가능

2. Model

→ DataBase(DB)

에브리타임 계정, 게시물, 광고 데이터

3. View

→사용자로부터 요청받아 데이터를 처리하는 곳 MTV중에거 핵심

당근 입력하면 템플릿에 입력된거고 엔터 누르면 템플릿에 있는 당근이 뷰로 넘어가고 뷰는 모델에서 당근이라는 모델을 검색해서 다시 뷰로 가져옵니다. 그리고 뷰에서는 가져온 정보들을 중고거래, 동네정보 같은 세부적인 분류를 해주고 이렇게 분류해준 데이터를 템플릿으로 보내줍니다. 그리고 템플릿은 사용자인 저에게 이러한 페이지를 보여준다.