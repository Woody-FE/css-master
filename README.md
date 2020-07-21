# CSS MASTERS

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

  

  

  