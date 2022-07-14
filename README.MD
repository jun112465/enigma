# 변수 내용 정리

ptr_r1
ptr_r2
ptr_r3 

refArr : 반사체를 통해 교환되는 글자를 정리한 배열이다. 예를 들어, refArr[0] = 'B'라면 
A는 B와 교환된다는 뜻이다. 여기서 refArr[1] = 'A'라는 것을 추론할 수 있다.

lamp : lampboard dom을 가리키는 변수

input : inputboard dom을 가리키는 변수

# 함수 정리

update() : 로터의 숫자를 업데이트
transform(param, ptr) : 입력된 글자를 암호화
rotate() : 글자 암호화 후 로터 회전

# 변환과정

1. 각 로터에 대한 순서로 변환 (로터가 가리키는 글자가 해당 로터에서 'A' 순번이라 생각하면 된다)
2. 반사체를 통해 반사됨
3. 로터 회전
