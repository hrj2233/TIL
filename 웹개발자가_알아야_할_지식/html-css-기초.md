# INTRODUCTION TO HTML AND CSS

-   What do HTML and CSS stand for?
    -   html은 웹사이트의 구조를 만들고 css는 웹사이트를 꾸밈.
-   Between HTML and CSS, which would you use for putting paragraphs of text on a webpage?
    -   html
-   Between HTML and CSS, which would you use for changing the font and background color of a button?
    -   css

# ELEMENTS AND TAGS

-   What is an HTML tag?
    -   html tag는 contents를 감싸는 것.
-   What are the three parts of an HTML element?
    -   opening tag, content, closing tag

# HTML BOILERPLATE

-   What is the purpose of the doctype declaration?
    -   문서를 렌더링하는데 사용해야 하는 html 버전을 브라우저에게 알려줌.
-   What is the HTML element?
    -   문서의 루트 요소로, 문서의 다른 모든 요소는 해당 문서의 하위 요소.
-   What is the purpose of the head element?
    -   웹페이지에 대한 중요한 메타 정보와 웹 페이지가 브라우저에서 올바르게 렌더링되는데 필요한 항목을 넣는곳.
-   What is the purpose of the body element?
    -   텍스트, 이미지, 목록, 링크 등 사용자에게 표시될 모든 콘텐츠를 표시하는 곳.

# WORKING WITH TEXT

-   How do you create a paragraph in HTML?
    -   p태그
-   How do you create a heading in HTML?
    -   h1~h6태그
-   How many different levels of headings are there and what is the difference between them?
    -   h1은 가장 중요하고 숫자가 작을수록 글자가 작아지고 중요성 작음.
-   What element should you use to make text bold and important?
    -   strong 태그
-   What element should you use to make text italicized to add emphasis to it?
    -   em 태그
-   What relationship does an element have with any nested elements within it?
    -   parent and child relationship
-   What relationship do two elements have if they are at the same level of nesting?
    -   siblings
-   How do you create HTML comments?
    -   여는 꺽쇠 !-- -- 닫는 꺽쇠

# LISTS

-   What HTML tag is used to create an unordered list?
    -   ul태그
-   What HTML tag is used to create an ordered list?
    -   ol태그
-   What HTML tag is used to create list items within both unordered and ordered lists?
    -   li태그

# LINKS AND IMAGES

-   What element is used to create a link?
    -   a태그
-   What is an attribute?
    -   html 요소에 추가 정보를 줌
-   What attribute tells links where to go to?
    -   href 속성
-   What is the difference between an absolute and relative link?
    -   absolute link: 인터넷상의 다른 웹사이트 페이지에 대한 링크
    -   relative link: 자신의 웹사이트에 있는 페이지에 대한 링크
-   Which element is used to display an image?
    -   img 태그
-   What two attributes do images always need to have?
    -   src 속성, alt 속성
-   How do you access a parent directory in a filepath?
    -   ../
-   What are the four main image formats that you can use for images on the web?
    -   jpg
        -   파일 크기를 과도하게 늘리지 않고 큰 색상 팔레트를 처리하도록 설계되엇음.
        -   그라디언트가 많은 사진과 이미지에 적합.
        -   반면에 JPG는 투명 픽셀을 허용하지 않습니다. 실제로 가까이서 보면 아래 이미지의 흰색 가장자리에서 볼 수 있습니다.
    -   gif
        -   간단한 애니메이션을 위한 필수 옵션, 단점은 색상 팔레트 측면에서 다소 제한적. 사진으로는 사용x.
        -   투명 픽셀은 GIF의 이진 옵션이므로 반투명 픽셀을 가질 수 없습니다(확실히 투명이거나 아니거나). 투명한 배경에서 높은 수준의 세부 정보를 얻기 어려울 수 있습니다.
        -   이러한 이유로 애니메이션이 필요하지 않은 경우 일반적으로 PNG 이미지를 사용하는 것이 좋습니다.
    -   png
        -   사진이나 애니메이션이 아닌 모든 것에 적합.
        -   사진의 경우 동일한 품질(사람의 눈으로 인식)의 PNG 파일은 일반적으로 동등한 JPG 파일보다 큼. 그러나 불투명도를 잘 처리하고 색상 팔레트 제한이 없습니다.
        -   아이콘, 기술 다이어그램, 로고 등에 적합.
    -   svg
        -   위의 픽셀 기반 이미지 형식과 달리 SVG는 벡터 기반 그래픽 형식이므로 품질 손실 없이 모든 차원으로 확장 또는 축소할 수 있음.
        -   이 속성은 SVG 이미지를 반응형 디자인을 위한 훌륭한 도구로 만듭니다. PNG와 거의 동일한 사용 사례에 적합하며 가능하면 언제든지 사용해야 합니다.
        -   아이콘, 기술 다이어그램, 로고 등에 적합.
        -   SVG에는 한 가지 잠재적인 문제가 있습니다. SVG가 여러 브라우저에서 일관되게 표시하려면 이미지 편집기(예: Abode Illustrator 또는 Sketch)를 사용하여 텍스트 필드를 윤곽선으로 변환해야 합니다. 이미지에 많은 텍스트가 포함된 경우 파일 크기에 큰 영향을 줄 수 있습니다. 이러한 이유로 SVG가 매우 훌륭함에도 불구하고 SVG 대신 PNG를 사용합니다.

# COMMIT MESSAGES

- What are two benefits of having well-written commit messages and a good commit history?
    - 동료 개발자(및 실제로 미래의 자신)에게 변경 사항에 대한 컨텍스트를 전달합니다. diff는 무엇이 변경되었는지 알려줄 것이지만 커밋 메시지만이 그 이유를 제대로 알려줄 수 있습니다. 
    - 몇 달 또는 몇 년 전에 어떤 일이 일어났는지 이해하는 것이 가능할 뿐만 아니라 효율적이기 때문에 중요하다.
- How many characters should the subject line of your commit message be?
    - 50자
# CSS FOUNDATIONS

-   What are the main differences between external, internal, and inline CSS?
    -   Inline: html 요소 내에 직접 배치
    -   Internal: html head 태그내에 <style></style> 에 배치
    -   External: css 파일을 따로 만들어 head 섹션 내에 링크를 통해 연결
-   What is the syntax for class and ID selectors?
    -   html: class="class이름", id="id이름"
    -   css: .class이름{}, #id이름{}
-   How would you apply a single rule to two different selectors?

    -   grouping selector

        ```css
        .read,
        .unread {
        	color: white;
        	background-color: black;
        }
        ```

-   Given an element that has an id of title and a class of primary, how would you use both attributes for a single rule?
    -   Chaining Selectors
        ```css
        .subsection.header {
        	color: red;
        }
        ```
-   What does the descendant combinator do?

    -   이전 선택자와 일치하는 조상(부모, 조부모 등)이 있는 경우 마지막 선택자와 일치하는 요소만 선택하도록 합니다.

    ```css
    .ancestor .contents {
    /_ some declarations _/
    }
    ```

-   Between a rule that uses one class selector and a rule that uses three type selectors, which rule has the higher specificity?
    -   one class selector

# INSPECTING HTML AND CSS

-   How do you select a specific element on your page with your browser’s developer tools?
    -   해당 요소에 오른쪽 클릭해서 검사에 들어가면 됨.
-   What does a strikethrough in a CSS element mean in your browser’s developer tools?
    -   overwritten
-   How do you change CSS in real time on specific elements of a web page with your browser’s developer tools?
    -   개별 선택자나 속성에 직접 추가하면 됨.

# THE BOX MODEL

-   From inside to outside, what is the order of box-model properties?
    -   padding -> border -> margin
-   What does the box-sizing CSS property do?
    -   너비는 페이지에 표시되는 상자의 너비이므로 콘텐츠 영역 너비는 너비에서 패딩 및 테두리 너비를 빼고 계산
-   What is the difference between the standard and alternative box model?
    -   standard box model은 실제 크기를 얻기 위해 테두리와 패딩을 추가해야 하는 것
    -   alternative box model은 모든 너비는 페이지에 표시되는 상자의 너비이므로 콘텐츠 영역 너비는 너비에서 패딩 및 테두리 너비를 뺀 것
-   Would you use margin or padding to create more space between 2 elements?
    -   margin
-   Would you use margin or padding to create more space between the contents of an element and its border?
    -   padding
-   Would you use margin or padding if you wanted two elements to overlap each other?
    -   margin

# BLOCK AND INLINE

-   What is the difference between a block element and an inline element?
    -   block은 서로 쌓여진 채 나타나며, 각각의 새 요소는 새 줄에서 시작합니다.
    -   inline은 새 줄에서 시작하지 않고 옆에 요소와 배치하여 나타납니다.
-   What is the difference between an inline element and an inline-block element?
    -   inline은 높이와 넓이가 적용되지 않고 패딩 top bottom 적용 안됨.
    -   inline-block은 높이와 넓이와 패딩이 적용됨. 그리고 inline처럼 새 줄에서 시작하지 않고 옆에 요소와 배치하여 나타남.
-   Is an h1 block or inline?
    -   block
-   Is button block or inline?
    -   inline
-   Is div block or inline?
    -   block
-   Is span block or inline?
    -   inline

# INTRODUCTION TO FLEXBOX

-   What’s the difference between a flex container and a flex item?
    -   flex container는 display: flex가 있는 모든 요소입니다. flex item은 플렉스 컨테이너 내부에 직접 존재하는 모든 요소.
-   How do you create a flex item?
    -   flex container에 display:flex를 선언하면 container 안에 있는 요소들은 flex item이 됨.

# GROWING AND SHRINKING

-   What are the 3 values defined in the shorthand flex property (e.g. flex: 1 1 auto)?
    -   flex-grow, flex-shrink, flex-basis

# AXES

-   How do you make flex items arrange themselves vertically instead of horizontally?
    -   flex-direction: column;
-   In a column flex-container, what does flex-basis refer to?
    -   height
-   In a row flex-container, what does flex-basis refer to?
    -   width
-   Why do the previous two questions have different answers?
    -   flex-direction: row는 주축을 수평으로(왼쪽에서 오른쪽으로)하기 때문에 basis가 width, column은 주축을 수직으로(위에서 아래로) 배치하기 때문에 basis가 height.

# ALIGNMENT

-   What is the difference between justify-content and align-items?
    -   justify-content: main axis 항목 정렬
    -   align-items: cross axis 항목 정렬
-   How do you use flexbox to completely center a div inside a flex container?
    -   justify-content:center; align-items:center;
-   What’s the difference between justify-content: space-between and justify-content: space-around?

    -   space- between: item이 라인에서 균등하게 분배됨. 첫 번째 item은 시작에 있고 마지막 item은 끝에 있습니다.
    -   space-around: item은 item 주위에 동일한 공간만큼 균등하게 분배됩니다. 모든 항목의 양쪽에 동일한 공간이 있으므로 시각적으로 공간이 동일하지 않습니다. 첫 번째 항목은 컨테이너 가장자리에 대해 1단위의 공간이 있지만 다음 항목에는 적용되는 자체 간격이 있기 때문에 다음 항목들 사이에는 2단위의 공간이 있습니다.

        <img src="https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg" width="300">

# HTML AND CSS BASICS

-   What is the difference between HTML and CSS?
    -   html은 웹 페이지에 있는 모든 실제 내용을 포함하는 마크업 언어
    -   css는 어떤 특정 태그를 특정한 방식으로 브라우저에게 보여주고 싶을 때 사용
-   For accessibility in HTML, what is the attribute used to describe an image (on screen readers or if it fails to load)?
    -   alt 속성
-   What is the difference between CSS Grid and Flexbox?
    -   flexbox는 1차원의 레이아웃을 위해 설계
    -   Css grid는 2차원의 레이아웃을 위해 설계
    -   Css grid는 행과 열을 동시에 더 쉽게 렌더링 할 수 있음
    -   출처: https://www.freecodecamp.org/news/the-main-differences-between-flexbox-and-css-grid-667c03461d2b/
-   For a responsive website, should it be designed mobile-first or desktop-first?
    -   모바일이 우선이 되어야 한다. 더 쉬움
    -   출처: https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/
-   Describe the components of the CSS Box Model.
    -   Margin: border 밖의 영역
    -   Border: margin과 padding의 사이
    -   Padding: 콘텐츠와 border사이
    -   Content: 박스의 내용
-   In CSS, what is a breakpoint?
    -   웹사이트 콘텐츠가 device 너비에 따라 응답하는 지점으로, 사용자에게 최상의 레이아웃을 표시할 수 있다.
-   What is a div and how are they used?

    -   본질적으로 아무것도 나타내지 않는 플로우 콘텐츠를 위한 컨테이너
    -   <div></div>

-   What are the two main groups of CSS properties that control typography style?
    -   Font and text
-   What is the “query string” in a URL and what does it do?
    -   데이터가 웹 응용 프로그램 및 백엔드 데이터베이스로 전달되는 url의 일부이다.
    -   url에서 쿼리 문자열을 통해 데이터를 저장할 수 있다.
-   What is the difference between “pixels” and “em”?
    -   pixels은 모니터에 따라 상대적인 크기를 가짐
    -   Em은 해당 폰트의 대문자 M의 너비를 기준
-   How does inheritance work for CSS styles, i.e. how does an element get its “default” styles?
    -   요소의 속성에 어떤 값이 지정되지 않을 때 일어나는 일을 제어
-   What are two CSS attributes you can change to push an element around on the page?
    -   Margin , padding
-   What is the “default stylesheet” or “user agent stylesheet”?
    -   브라우저에 내장되어 있으며 html 요소에 기본 스타일을 부여하는 css 규칙
-   What is the purpose of a CSS reset file?
    -   기본 스타일을 무력화 하고 빈 페이지에서 완전히 시작 할 수 있음. 이는 다른 브라우저로 인해 마크업이 다르게 표시 되는 것을 방지하는데 유용.
