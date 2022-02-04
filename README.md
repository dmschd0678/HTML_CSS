### HTML/CSS 기본 문법 공부

## HTML

- **html:5 + tab** : 자동 완성
- **`<h?> 글씨 </h?>`** : ?의 숫자 크기가 작을수록 글씨 크기 커짐
- **`<a href = "링크">글씨</a>`** : 누르면 링크 이동(페이지 이동)
- **`<img src = "이미지 경로", alt = "">`** : 이미지 불러오기
- **`<br>`** : 줄 바꿈
- **`<table></table>`** : 테이블 만들기
    
    - `<th></th>` : 테이블 헤더 만들기
    - `<tr></tr>` : 테이블 행 만들기
    - `<td></td>` : 테이블 열 만들기

    - 표 디자인 : `<table ? = ""></table>`
        <table border = "1">
            <th>속성</th>
            <th>설명</th>
            <tr>
                <td> border</td>
                <td> 테두리</td>
            </tr>
            <tr>
                <td> bordercolor</td>
                <td> 테두리 색</td>
            </tr>
            <tr>
                <td> width/height</td>
                <td> 크기</td>
            </tr>
            <tr>
                <td> align</td>
                <td> 테이블 값 정렬</td>
            </tr>
            <tr>
                <td> colspan/rowspan</td>
                <td> 셀을 합침(행/열)</td>
            </tr>
        </table> 

- **`<ul></ul>`** : 순서가 없는 목록 만들기
- **`<ol></ol>`** : 순서가 있는 목록 만들기
    - `<li></li>` : list
- **`<p></p>`** : 문단 만들기
- **`<div></div>`** : 다른 HTML 요소들을 하나로 묶는 데 자주 사용되는 대표적인 블록(block) 요소
- **`<span></span>`** : 텍스트의 특정 부분을 묶는 데 자주 사용되는 인라인(inline) 요소

- **`<form></form>`** : 웹 페이지 입력 양식
    - name : 폼의 이름
    - action : 폼 데이터가 전송되는 백엔드 url
    - method : 폼 전송 방식(GET/POST)
    - textarea : 여러 줄의 문자열을 입력할 수 있는 태그
    - `<input></input>` : 실제로 사용자가 양식을 입력하기 위한 태그<br>
        - name : 데이터의 이름<br>
        - value : 기본 값<br>
        - type : 종류
            - text : 문자
            - password : 비밀번호
            - button : 버튼
            - submit : 양식 제출용 버튼
            - reset : 양식 초기화용 버튼
            - radio : 한 개만 선택할 수 있는 컴포넌트
            - checkbox : 다수를 선택할 수 있는 컴포넌트
            - file : 파일 업로드
            - hidden : 사용자에게 보이지 않는 숨은 요소
    - `<select></select>` : 목록
        - `<option>?</option>` : 값
    - `<iframe src = "웹 페이지 주소"></iframe>` : 웹페이지를 삽입할 수 있음
------
## CSS

- **inline style sheet** : HTML 태그의 style 속성에 CSS 코드를 작성
- **internal style sheet** : HTML 문서 안의 `<style>`태그에 CSS 코드를 작성
- **linking style sheet** : 별도의 CSS코드를 만들고 HTML 문서와 연결(`<link>`)<br>
#### inline > internal > linking 순으로 적용
