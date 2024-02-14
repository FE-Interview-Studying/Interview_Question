## TDZ (Temporal Dead Zone)

일시적 사각지대   
스코프의 시작 지점부터 초기화 시작 지점까지의 구간으로 변수를 참조할 수 없는 구간을 가리킴.

TDZ와 호이스팅 개념은 밀접한 관계를 가짐.
TDZ 구간에서 변수를 참조하게 될 경우 Reference Error가 발생하게 된다.

***

TDZ에 영향을 받는 구문 : let / const / class
TDZ에 영향을 받지 않는 구문 : var / function / import

