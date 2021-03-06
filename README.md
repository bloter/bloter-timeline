BloterTimeline
============

타임라인 형식의 기사를 작성할 때 도움을 주는 워드프레스 플러그인 입니다. 숏코드 형태로 글에 삽입하여 사용하도록 되어 있고, 작성의 편의를 돕기 위해 에디터에 숏코드를 간편히 추가할 수 있는 버튼과 타임라인 작성 폼을 따로 구성하였습니다.

## 설치
압축된 zip 형태의 소스파일을 다운 받아서 워드프레스의 플러그인 추가하기에서 `플러그인 업로드`를 통해 업로드 할 수 있습니다. 플러그인 업로드를 할 수 없는 환경이라면 다운 받은 소스파일의 압축을 풀어 직접 FTP를 이용해 워드프레스의 `wp-content/plugins` 폴더 하위에 폴더 째로 업로드 하면 됩니다.

## 사용법
에디터에 추가된 타임라인 추가 버튼을 클릭하면 타임라인을 작성할 수 있는 폼이 나옵니다.

![alt tag](http://bloterandmedia.github.io/resources/img/added-plugin-icon-in-editor-tip.png)

타임라인은 주제와 각각의 타임라인 아이템의 제목, 날짜, 이미지, url, 내용을 포함할 수 있습니다.

![alt tag](http://bloterandmedia.github.io/resources/img/timeline-create-form-modal-expend.PNG)

타임라인 주제는 전체 타임라인을 설명하는 주제로 한번 작성이 가능합니다.

각 타임라인 아이템은 반드시 제목, 날짜, 내용을 가지고 있어야 합니다. 이미지와 url은 필수 작성 항목은 아니기 때문에 유연하게 작성할 수 있습니다. url을 작성하면 관련된 링크를 추가하여 페이지를 이동할 수 있습니다.

## 주의사항
현재 버전의 타임라인은 내용을 모두 작성한 후 타임라인의 내용을 수정하는 것이 매우 힘듭니다. 때문에 처음 작성할 때 신중하게 작성해야 불편함을 겪지 않을 수 있습니다. 이 부분은 차후 보완할 예정입니다.

## 필요한 라이브러리
- jQuery
- jQuery UI
- Bootstrap
