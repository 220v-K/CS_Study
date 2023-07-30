## Stack

- Last-In-First-Out (LIFO) 형식의 자료구조.
- 자료를 insert / delete 하는 것을 push, pop이라 함.
- top으로 가리키는(pointing) 곳에만 접근이 가능.
- array 또는 linked list를 통해 구현하는 경우가 많음.

## Queue

- First-In-First-Out (FIFO) 형식의 자료구조.
- 자료를 insert / delete 하는 것을 enqueue, dequeue라 함.
- enqueue되는 쪽이 rear / dequeue되는 쪽이 front.
- array 또는 linked list를 통해 구현하는 경우가 많음.

------

※ 스택의 활용 예시

스택의 특징인 후입선출(LIFO)을 활용하여 여러 분야에서 활용 가능하다.

- 웹 브라우저 방문기록 (뒤로 가기) : 가장 나중에 열린 페이지부터 다시 보여준다.

- 역순 문자열 만들기: 가장 나중에 입력된 문자부터 출력한다.

- 실행 취소 (undo) : 가장 나중에 실행된 것부터 실행을 취소한다.
- 후위 표기법 계산
- 수식의 괄호 검사 (연산자 우선순위 표현을 위한 괄호 검사)



※ 큐의 활용 예시

큐는 주로 데이터가 입력된 시간 순서대로 처리해야 할 필요가 있는 상황에 이용한다.

- 우선순위가 같은 작업 예약 (프린터의 인쇄 대기열)

- 은행 업무

- 콜센터 고객 대기시간
- 프로세스 관리
- 너비 우선 탐색(BFS, Breadth-First Search) 구현
- 캐시(Cache) 구현