이벤트
====
&nbsp;  

### ☻ 마우스 이벤트  
&nbsp;

|이벤트 타입|설명|
|------|-----|
|mousedown|마우스 버튼을 누르는 순간|
|mouseup|마우스 버튼을 눌렀다 떼는 순간|
|click|왼쪽 버튼을 클릭한 순간|
|dbclick|왼쪽 버튼을 빠르게 두 번 클릭한 순간|
|contextmenu|오른쪽 버튼을 클릭한 순간|
|mousemove|마우스를 움직이는 순간|
|mouseover|마우스 포인터가 요소 위로 올라가는 순간|
|mouseout|마우스 포인터가 요소에서 벗어나는 순간|
|mouseenter|마우스 포인터가 요소 위로 올라가는 순간(버블링 일어나지 X)|
|mouseleave|마우스 포인터가 요소에서 벗어나는 순간(버블링 일어나지 X)|

&nbsp;  
(**버블링**이란 특정 화면 요소에서 **이벤트가 발생했을 때 해당 이벤트가 더 상위의 화면 요소들로 전달되어 가는 특성**을 의미한다.)    
&nbsp;  

### ☺︎ mouseover, mouseout 과 mouseenter, mouseleave 차이점
&nbsp;

가장 큰 차이는 이벤트가 자식 요소에 영향을 끼치는지이다.  

1. mouseenter, mouseleave는 버블링이 일어나지 않는다.  
2. 자식 요소의 영역을 계산하지 않는다.  

➣  <U>이벤트 핸들러가 자식 요소에까지 영향을 끼치게 하고 싶을 때</U>는 **mouseover/mouseout**을, <U>자식 요소에는 영향을 끼치지 않고 해당 요소에만 이벤트 핸들러를 다루고자 할 때</U>는 **mouseenter/mouseleave**를 사용하면 좋다.


&nbsp;  
### ☻ 키보드 이벤트  
&nbsp;  

|이벤트 타입|설명|
|------|-----|
|keydown|키를 누르는 순간|
|keypress|키를 누르는 순간 (출력 가능한 키에서만 동작)|
|keyup|키를 눌렀다 떼는 순간|

&nbsp;

### ☻ 포커스 이벤트
&nbsp;
|이벤트 타입|설명|
|------|-----|
|focusin|요소에 포커스 되는 순간|
|focusout|요소에서 포커스가 빠져나가는 순간|
|focus|요소에 포커스 되는 순간(버블링 일어나지 X)|
|blur|요소에서 포커스가 빠져나가는 순간(버블링 일어나지 X)|  

&nbsp;

### ☻ 입력 이벤트
|이벤트 타입|설명|
|------|-----|
|change|입력된 값이 바뀌는 순간|
|input|값이 입력되는 순간|
|select|입력 양식의 하나가 선택되는 순간|
|submit|폼을 전송하는 순간|

&nbsp;

### ☻ 스크롤 이벤트  
|이벤트 타입|설명|
|------|-----|
|scroll|스크롤 바가 움직일 때|

&nbsp;  

### ☻ 윈도우 창 이벤트
|이벤트 타입|설명|
|------|-----|
|resize|윈도우 사이즈를 움직일 때|
