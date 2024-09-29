# web_basic
HTML, CSS, Javascript, Web build study

---
</br>

### **1. 웹 역할에 따른 종류**
  - 정적 사이트 : 취업을 위한 포트폴리오나, 기업 홍보 사이트는 정보를 보여주기만 하는 웹사이트
  - 동적 사이트 : 정보뿐만 아니라 사용자에게 기능과 서비스를 제공하는 웹사이트

</br>

### **2. 서버와 클라이언트**
  - 서버는 사용자에게 정보를 제공하기 위한 웹사이트가 저장된 컴퓨터입니다.
  - 클라이언트는 사용자가 웹 사이트에 접근하기 위해 사용하는 PC, 태블릿, 스마트폰을 의미합니다.

</br>

### **3. 프런트엔드와 백엔트**
  - 프런트엔드는 사용자에게 보이는 영역을 의미하며 디자인하거나, 동작에 반응하는 기능을 만드는 역할을 합니다.
  - 백엔드는 보이지 않는 영역을 의미하며 회원정보, 게시판 등 데이터를 처리하는 역할을 합니다.

</br>

### **4. 웹 개발의 기본**
  - HTML : 웹 문서의 뼈대를 만드는 마크업 언어
  - CSS : 웹 문서를 꾸미는 스타일 언어
  - Javascript : 사용자 동작에 반응하는 스크립트 프로그래밍 언어

</br>

### **5. HTML**
  - Hyper Text Markup Language의 줄임말로, 웹 문서를 만드는 기본언어
  - <>를 태그라고 하며, 웹브라우저의 속성을 구분하는 꼬리표
  - 시맨틱 태그란, 의미가 통하는 태그라는 뜻으로 웹 브라우저의 영역을 구분
    - header  : 헤더 영역, 검색창이나 사이트 메뉴를 삽입하는 영역
    - nav     : 내비게이션 영역, 다른 웹 문서로 연결하는 링크를 다루는 영역
    - main    : 핵심 콘텐츠를 담는 영역, 웹 문서의 핵심이 되는 내용을 넣는 영역
    - footer  : 웹 문서 아래를 나타내는 영역
    - article : 독립적인 콘텐츠를 담는 영역, 신문이나 블로그 포스트 등을 담는 영역
    - section : 다수의 콘텐츠를 담는 영역, 몇 개의 콘텐츠를 묶은 영역
    - aside   : 사이드바 영역
    - div     : 웹 문서의 영역을 구분하는 태그
    - 그 외 p, br, blockquote, strong, b, em, i, u

</br>

### **6. HTML : 입력양식(폼)**
  - 사용자가 정보를 입력하면 해당 정보는 웹 서버로 전송됩니다.
  - 그럼 서버는 자신이 가진 데이터베이스에서 정보를 확인하고 결과를 웹 브라우저로 보냅니다.
  - 정보를 넘겨주는 방식은 [get, post] 2가지가 있는데 get은 데이터 제한이 있고 정보가 그대로 드러나는 단점이 있습니다.
  - 양식은 HTML로 만들 수 있지만, 폼에 입력한 사용자 정보는 ASP, PHP, JSP 같은 서버 프로그래밍을 이용합니다.

</br>

### **7. CSS**
  - 웹 문서에 디자인을 담당하는 스타일 언어입니다.
  - 스타일 형식 | 선택자 { 속성1: 속성값1; 속성2: 속성값; }
      - 특정 요소(태그)에 적용하는 타입 선택자
      - 특정 부분에 적용하는 class, id 선택자
      - 같은 스타일 규칙을 사용하는 요소들을 묶어주는 그룹 선택자
  - CSS 소스 경량화 | CSS파일은 네트워크를 이용해 내려받기 때문에 파일크기가 작을수록 좋습니다.
  - css minity 또는 css compress 등 크기를 줄여주는 툴도 있습니다.
  - 웹 폰트도 *.ttf 파일은 크기가 크므로, 주로 EOT, WOFF, WOFF2 파일을 사용합니다.
  - css 적용 형식은 인라인 스타일, 내부 스타일, 외부 스타일 3가지가 있습니다.

</br>

### **8. CSS : 케스케이딩**
  - 케스케이딩이란, 우선순위가 위에서 아래 즉 계산식으로 적용된다는 의미 입니다.
  - 스타일의 중요도에 따라 우선순위를 정하고, 태그의 부모 자식 관계로 스타일을 상속합니다.
  - 스타일 규칙에 !important를 붙이면 다른 스타일보다 우선순위가 높아집니다.
  - 스타일의 우선순위 | !important > 인라인 스타일 > id 스타일 > class 스타일 > 타입 스타일

</br>

### **9. CSS : 색상**
  - css에서 글자색을 지정하는 속성은 color 입니다.
  - hsl, hsla와 같이 (0, 100%, 50%)와 같이 색상을 표현할 수도 있고
  - rgb와 rgba로 rgb(0, 0, 255)와 같이 색상을 표현할 수 있습니다.

</br>

### **10. CSS : 박스 모델**
  - 박스 모델의 구조는 콘텐츠 영역, padding, border, margin으로 이루어져 있습니다.
  - width, height로 사용하거나 box-sizing의 border-box, content-box를 통해 크기를 적용할 영역을 지정합니다.
  - 박스 모델의 방향은 top, right, bottom, left 순서로 적용됩니다.
  - 박스 테두리(border) 스타일을 지정할 때는 border-style, border-width, border-color를 사용합니다.
  - 둥근 테두리를 만드려면 border-radius 속성을 사용합니다.
  - 여백을 조절하는 속성은 margin(요소 사이), padding(콘텐츠와 테두기 사이)입니다.
  - 이미지 배치에 사용되는 속성에 float{left | right}이 있으며, clear{left | right}로 해제할 수 있습니다.
  - 배치 방법을 결정하는 diplay 속성을 통해 인라인과 블록 레벨 요소 변환이 가능합니다.
  - float 속성은 웹 요소를 문서 위에 떠 있게 만들 수 있습니다.
  - background 속성은 박스의 배경을 지정합니다.

  </br>

  ### **11. CSS : 연결 선택자**
  - 특정 요소를 기준으로 그 안에 포함된 요소를 하위 요소라고 합니다.
  - 하위 선택자를 사용하면 부모 요소에 포함된 하위 요소를 모두 선택할 수 있습니다.
    - section p {color: blue;}라면 section 요소의 모든 하위 p요소를 파란색 글자로 적용됩니다.
  - 자식 선택자는 하위 선택자와 다르게 자식 요소에만 스타일을 적용하는 선택자 입니다.
    - section > p {color: blue;}라면 section 바로 하위에 있는 자식 p들만 적용됩니다.
  - 인접 형제 선택자는 가장 인접한 요소를 선택합니다.
    - section + p {color: blue;}라면 section와 가장 인접한 하위 p 1개만 적용됩니다.
  - 형제 선택자는 인접 형제와 달리 모든 형제 요소에 적용됩니다.
    - section ~ p {color: blue;}라면 section과 형제인 p요소 모두 적용됩니다.

</br>

  ### **12. CSS : 속성선택자**
  - [속성] 선택자는 대괄호[]사이에 원하는 속성을 입력하면 됩니다.
    - a[href]라면 a요소에서 href 속성이 있는 요소를 찾아 스타일을 적용합니다.
  - [속성 = 속성값] 선택자는 주어진 속성과 속성값이 일치하는 요소를 찾습니다.
    - a[target = _blank]라면 target 속성값이 _blank인 요소에 스타일을 적용합니다.
  - [속성 ~= 값] 선택자는 여러 속성값 중에서 해당 속성값이 포함된 요소를 선택합니다.
    - [class ~= button]라면 class값 중에 button이 있는 요소에 스타일을 적용합니다.
  - [속성 |= 값] 선택자는 특정 속성값이 포함된 속성에 스타일을 적용합니다.
    - ~=과 다르게 (-)하이픈으로 연결되어 있는 단어도 스타일이 적용됩니다.
  - [속성 ^= 값] 선택자는 특정 속성에서 값으로 시작하는 요소를 찾습니다.
  - [속성 $= 값] 선택자는 특정 속성에서 값으로 끝나는 요소를 찾습니다.
  - [속성 *= 값] 선택자는 특정 속성에서 값의 위치와 상관없이 일부 포함되어 있는 요소를 찾습니다.
    - a[title ^= jap]라면 title 속성에서 jap로 시작하는 요소에 스타일을 적용합니다.
  
</br>

### **13. CSS : 가상클래스와 가상 요소**
  - 사용자가 웹 요소에 대해 특정 동작을 할 때 스타일을 변경하고 싶다면 가상클래스 선택자를 사용합니다.
    - ':link' 방문하지 않은 링크에 스타일을 적용하는 선택자
    - ':visited' 방문한 링크에 스타일을 적용하는 선택자
    - ':hover' 특정 요소에 마우스 포인터를 올려놓으면 스타일을 적용하는 선택자
    - ':active' 웹 요소를 활성화했을 때 스타일을 적용하는 선택자
    - ':focus' 웹 요소에 초점이 맞추어졌을 때 스타일을 적용하는 선택자
    - ':target' 앵커 대상에 스타일을 적용하는 선택자
    - ':checked' 선택한 항목의 스타일을 적용하는 선택자
    - ':not([])' 특정 요소를 제외하고 스타일을 적용하는 선택자
    - ':nth-child' 부모 안에 있는 요소 중 n번째 자식 요소에 대한 선택자
  - 가상클래스가 웹문서의 원하는 요소를 선택한다면 가상요소는 특정 부분에 스타일을 지정합니다.
    - '::first-line', '::first-letter'를 사용하면 첫 글자 혹은 줄에 스타일을 지정합니다.
    - '::before', '::after' 지정한 요소의 내용 앞뒤에 대한 스타일을 적용하는 선택자

</br>

### **14. Javascript**
  - 자바스크립트는 HTML, CSS와 함께 사용해서 웹의 요소를 움직이거나, 제어합니다.
  - alert(메세지) 알림 창 출력하기
  - confirm(메세지) 확인 & 취소 버튼이 있는 확인 창 출력하기
  - prompt(메세지, 기본값) 기본값이 입력된 프롬프트 창 출력하기
  - 자바스크립트의 자료형은 숫자형, 문자열, 논리형, 배열, 객체 등이 있습니다.
  - 변수나 자료형을 활용하는 방식은 언어가 다를뿐 파이썬이나 자바와 유사합니다.

</br>

### **15. Javascript : 연산자**
  - 산술연산자 ++은 피연산자를 1 증가시킵니다.
  - 산술연산자 --는 피연산자를 1 감소시킵니다.
  - ++와 --는 피연산자 앞뒤 어디에 붙이느냐에 따라 큰 차이가 있습니다.
  - 할당 연산자는 연산자 오른쪽의 실행 결과를 왼쪽 변수에 할당합니다.
  - 할당 연산자에는 +=, -=, *=, /=, %= 가 있습니다.
  - 논리 연산자에는 ||(OR), &&(AND), !(NOT)가 있습니다.

</br>

### **16. Javascript : 조건문**
  - if(조건) {조건 결과값이 true일 때 실행}
  - else {조건 결과값이 False일 때 실행}