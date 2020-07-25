# CSS MASTERS

## GRID

- GRID 사용

  > Grid도 부모에게 선언해서 사용한다.

- grid-template-rows, grid-template-columns

  > 화면을 분할하며 repeat()로 여러개를 만들어 낼 수 있다.
  >
  > 이것 또한 부모에 선언하지만 width, height값이 없으면 auto같은 값을 사용할 수 없다.

- grid-template-area

  > "header header header"
  >
  > "content content sidebar"
  >
  > "footer footer footer" 등으로 표현할 수 있으며
  >
  > 자식값에 이름에 맞는 grid-area 속성값이 존재해야한다. ex) grid-area: header;







# Flexbox

- Flex 사용

  > Flex는 부모인 container에 선언하며, 자식이 영향을 받는다.
  >
  > cross axis를 조작하기 위해서는 height값을 가지고 있어야한다.

- flex-direction

  > row일 때, main axis 가로축, cross axis 세로축
  >
  > column일 때, main axios 세로축, cross axis 가로축
  
- align-self

  > 자식에게 주는 속성값이며 cross-axis를 단독으로 변경한다.

- flex-wrap

  > 기본 값이 nowrap이며, 자식들을 구겨서 한줄에 넣게 한다.
  >
  > wrap을 줘서 자식들이 고유의 크기를 유지할 수 있도록 변경 할 수 있다.

- flex-shrink

  > 자식한테 주는 속성값이며, default가 1이지만 2로 늘리면 nowrap에서 해당 자식이  2배로 수축하게 된다.

- flex-grow

  > box주변 공간이 남을 경우 해당 값을 통해서 공간을 양분한다.

- align-content

  > cross-axis의 line에 대한 속성값이다. flex-start 같은 값이 여기에 존재한다.
  >
  > 특히! align-items에는 라인에 대한 속성값이 없으므로 주의

- flex-basis

  > main-axis의 길이 값이 되어줄 속성이다. 초기값에 해당하며 flex-grow, flex-shrink 등에 의해서 영향을 받아 커지거나 작아질 수 있다.

- order

  > 자식들의 순서를 바꾸기 위해 주는 속성 값, default가 0이며 1,2 등등의 값을 줘서 순서를 미룰 수 있다.

  

  


## SCSS

- Nesting

  > 중첩으로 코드를 좀 더 줄일 수 있다.
  >
  > & 키워드로 상위 선택자를 참조할 수 있다.
  >
  > @at-root 키워드로 중첩밖으로 나갈 수 있다.
  >
  > font-, margin- 등과 같이 동일한 네임 스페이스 속성을 묶어 사용할 수 있다.

- Variables

  > 반복적으로 사용되는 값을 변수로 지정할 수 있다.
  >
  > $변수명: 값;
  >
  > .box {
  >
  > ​	width: $변수명;
  >
  > }
  >
  > 위와 같이 사용 가능

- Mixins

  > 재활용을 하는 코드이며, @mixin 이름으로 선언하고 @include 이름으로 사용한다.

- extend

  > 확장의 개념이다. mixin은 연산을 할 수 있기 때문에 mixin을 좀 더 사용한다.