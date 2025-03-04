# 2장 JSX
## 1. JSX란 무엇이며, 장단점은 무엇인가요?
JSX는 자바스크립트의 확장 구문으로 트랜스파일러에 의해 순수 JavaScript로 변환됩니다. 

장점으로는 코드 가독성과 유지보수성이 높아지고, JavaScript와 HTML을 자연스럽게 결합할 수 있다는 점이 있습니다. 

반면, JSX 문법을 학습해야 하는 추가 학습 비용과, 트랜스파일 과정으로 인해 초기 설정이 필요하다는 단점이 있습니다.

## 2. JSX와 HTML의 차이점은 무엇인가요?
JSX는 HTML의 속성에 대해 camelCase를 사용합니다. 또한 HTML 엘리먼트는 소문자로 작성하지만 JSX의 엘리먼트의 첫글자는 대문자로 작성해야 합니다.

## 3. 텍스트 문자열은 어떻게 기계어가 되나요?
JSX에서 작성한 텍스트 문자열은 트랜스파일러에 의해 자바스크립트로 변환됩니다. 변환된 코드는 React의 React.createElement 메서드를 호출하여 가상 DOM 객체를 생성하는 방식으로, 자바스크립트 엔진이 이를 실행하게 됩니다. 

이렇게 생성된 가상 DOM은 브라우저가 이해할 수 있는 실제 DOM으로 렌더링되며, 브라우저의 렌더링 엔진을 통해 기계어로 변환되어 화면에 표시됩니다.

## 4. JSX 표현식이란 무엇이며 어떤 좋은 점이 있나요?
JSX 표현식은 중괄호 {}를 사용하여 자바스크립트 코드를 JSX 내부에서 실행할 수 있는 기능을 말합니다. 이를 통해서 배열을 매핑하여 각 내부 요소들을 자식 요소로 반복적으로 렌더링할 수 있으며, 조건식으로 표현하여 유연하고 가독성이 좋게 작성할 수 있습니다.
