### 타입스크립트에서의 함수 형태

- var f1 = function(i: number): number { return i * i;};
> 기존과 다름점은 매개변수에 전달하는 값의 타입을 명시적으로 표현하고
> 콜론뒤에 타입을 명시적으로 표기해서 리턴값이 넘버라는 것을 말해주는게 다르다.

- var f2 = function(i: number) { return i * i;};
> 위의 코드랑 다른 점은 결과값을 확실히 알지 못할때 변동이 있을 수 있으니
> 명시적으로 타입을 표시하지 않는 점이 다르다

- var f3 = (i: number): number => {return i * i;};
> function이라는 단어가 사라진 코드이다.
> 그대신 화살표가 등장했다.
> 변수를 넣어서 그 결과를 출력한다라는 의미로 이해하면 편할듯
> 입력하면 => 출력한다


- var f4 = (i: number) => { return i * i;};
> f3와 다르게 출력에 대한 타입을 명시하지 않는 점이 다르다.

- var f5 = (i: number) => i * i;
> return도 없애고 직관적으로 단순하게 표현하는 식
