PhotoNoteBook
=============

이 앱은 iCloud를 마이크로소프트 잡지에 연재하면서 예제로 사용하기 위해서 
만든 앱으로 iCloud 방식 중 Document-Based Storage 방식을 사용 방법을 
보여주고 있다. 



주요 용어
--------

- Page   : 보관한 사진정보, 이 Page들은 Note라는 상위 개념으로 묶인다.
- Note   : 다수의 페이지 정보를 가짐


기능
-----

- 다수의 노트 생성 가능
- 하나의 노트에 다수의 사진 페이지 생성 가능
- 노트 정보들은 사진 아이클라우드를 사용하여 다른 iOS, 맥 장비에 동기화 됨
- 사진 확대/축소 가능
- 카메라, 앨범을 통해서 사진 추가 가능


UI 흐름
-------

![UI흐름도](images/ui_flow.png)

다음과 같은 시나리오대로 사용이 가능하다.

1. 노트를 생성 한다.
2. 생성된 노트를 클릭하면 Page 화면으로 이동
3. 필요한 사진을 Page에 추가한다.
4. 추가된 Page는 따로 크게 볼 수 있다.


빌드 방법
--------

본 앱은 아이클라우드를 사용하고 있기 때문에 실제 아이폰을 통해서만 
테스트가 가능하다. 그리고 iOS 5.0 SDK 이상이 필요하다. 모든 개발
환경이 준비 되었다면 다음과 같이 빌드할 수 있다.

1. 앱 아이디 생성 & AppID 속성에서 클라우드 속성을 활성화 시킴
2. 프로비젼 파일을 생성 혹은 갱신한다.
3. 앱의 앱 아이디를 1번에서 만든 것으로 교체한다.
4. 앱을 빌드한다.




문의 
----

- [10apps 홈페이지](http://10apps.tistory.com/)

