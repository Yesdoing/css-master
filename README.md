# CSS Masterclass

CSS Masterclass course (Flexbox, Grid, PostCSS, CSSNext)

### CSS Flex

- [x] CSS Flex Basics
- [x] Main Axis and Cross Axis
- [x] Flex Direction
- [x] Flex Wrap
- [x] Align Self

### CSS Grid

- [x] CSS Grid Basics ( Row, columns and gaps)
        - display: grid
        - grid-template-columns: 300px 500px;
        - grid-template-rows: 120px 300px;
- [x] Auto columns, auto rows
        - grid-gap: 4px;
        - grid-auto-rows: 200px;
        - grid-auto-flow: row;
- [x] Template Areas
        - parent { grid-template-areas: "header header header" "content content sidebar" "content content sidebar" "footer footer footer"; }
        - child { grid-area: header; }
- [x] fr unit, repeat
        - fr : relative value 
        - repeat function : repeat(3, 1fr) = 1fr 1fr 1fr 
        - example = grid-template-columns: repeat(5, 1fr) 2fr;
- [x] minmax, max-content, min-content
        - minmax: set the min~max value 
        - max-content : base max-size in containing container
        - min-content : base min-size in containing container
- [x] auto-fill, auto-fit
        - auto-fill : item이 들어갈 cell들을 미리 만들어 놓고 item을 하나씩 채운다.
        - auto-fit  : item을 stretch 해서 최대한 채운다.
- [x] Justify Content, Align Content and Place Content
        - Justify Content: column을 기준으로 content을 움직인다.
        - Align Content: row를 기준으로 content을 움직인다.
        - Place Content: Align Content, Justify Content
- [x] Justify Items, Align Items and Place Items
        - Justify Items : verticle을 기준으로 넓이를 줄인다. 
        - align items : horizon을 기준으로 높이를 줄인다. 
        - place items : 위 2 설정의 short cut이다.
- [x] Grid Column, Column Start and End
        - 한 셀이 column에 대해 얼마나 공간을 차지할 수 있는지 설정하는 기능
- [x] Line Naming
        - 각 라인에 대한 이름을 부여해서 컨트롤 할 수 있다. 자주 사용 x 
- [x] Grid Row, Row Start and End
        - span 값을 사용해서 한 셀의 크기의 값만 부여할 수 있다.
- [x] Grid Area
        - grid row start / grid column start / end / end 
- [x] Justify, Align, Place Self
        - justify-self, align-self, place-self : 1 cell 에 대해서만 스타일 적용 

### Using CSS4

- [x] Installing Parcel
- [x] Configuring PostCSS
- [x] Testing

### CSS4 Awesomeness

- [x] :matches , :not
        - matches : 조건에 일치하는 셀렉터만 style 적용
        - not: 조건이 아닌 셀렉터만 style 적용 
- [x] CSS Variables
        - declare css variables 
- [x] @custom-selector
        - 특정 셀렉터에 대한 스타일 지정 가능 
- [x] @custom-media
        - custom-media 변수 정의
- [x] Media Query Ranges
        - 변수 범위 지정시 <= > 와 같은 비교연산자 사용 가능 
- [x] color-mod, gray(), system-ui
        - color-mod : color에 효과 지정 가능 (작동 안함)
        - gray() : 회색 값 설정가능 
        - system-ui : font-family에 system-ui 선언시 그 컴퓨터가 가지고 있는 폰트 적용 가능 
- [x] Nesting Rules

### Conclusions

- [x] CSS Grid Kiss
- [x] Practice Flexbox
- [x] Practice Grid

### Exercices

<img src="https://i.pinimg.com/originals/7d/4c/66/7d4c66d0b646478a297ee21e7cd8aee5.jpg" width="300px" />
<img src="https://i.pinimg.com/originals/c3/64/72/c36472e703f1ca49324f53991f610392.jpg" width="300px" />
<img src="https://i.pinimg.com/originals/69/63/a5/6963a5c312b1994e1c7ea094bbd508de.jpg" width="300px" />
<img src="https://i.pinimg.com/564x/af/c5/fd/afc5fdee8a4036487d89ae08da9f1745.jpg" width="300px" />
<img src="https://i.pinimg.com/564x/ba/ea/9d/baea9d5be82afaaea4aa6a739a0cc6a8.jpg" width="300px" />
<img src="https://i.pinimg.com/564x/fd/90/23/fd9023163c117b63caac113a7bd47f5c.jpg" width="300px" />

<img src="https://i.pinimg.com/564x/a4/0d/ba/a40dba0269d7de0120496ec830d6b25a.jpg" width="300px" />
<img src="https://cdn.dribbble.com/users/102267/screenshots/4275407/afisha_by_radiusss.jpg" width="300px" />
