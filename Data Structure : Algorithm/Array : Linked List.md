## Array

- 데이터가 연속적으로 저장된 자료구조.
- 메모리 상에서 연속적으로 저장되어 있어, index를 통한 접근이 쉬움.
- array의 크기(size)는 처음 생성 시 정해지고, 이후 변경할 수 없음.



### Time Complexity

- 처음 or 중간에 Insert/Delete : O(n) (나머지 element들을 뒤로 밀어내는 시간에 좌우됨)
- 끝에 Insert/Delete : O(1)
- Find : O(1)



## (Singly) Linked List

- 여러 개의 노드가 순차적으로 연결된 형태의 자료구조.
- 첫 번째 노드를 head, 마지막 노드를 tail이라 함.
- array와 다르게, 메모리를 연속적으로 사용하지 않음.
- Insert / Delete 시 array보다 유리함.
- 하나의 Node에는, value와 다음 Node의 주소(reference)값이 저장되어 있음.



### Time Complexity

- head, tail에 Insert/Delete : O(1)
- 중간에 Insert/Delete : O(n) (탐색하는 시간에 좌우됨)



## Doubly Linked List

- Singly(Linear) Linked List와 다른 점은, 다음 Node의 주소값 뿐만 아닌, 이전 Node의 주소값까지 저장하는 것.
- 뒤에서 앞으로도 탐색해나갈 수 있어, 성능적으로는 더욱 유리하나, 메모리를 조금 더 차지.



### Time Complexity

Singly(Linear) Linked List와 동일.



## Circular Linked List

- Linked List의 Tail Node의 next node를 가리키는 주소값(reference)가 Head Node로 연결되어 있는 형태. 즉, 순환하는 형태.
- Doubly Linked List로도, Singly Linked List로도 구현되어짐.
- (tail pointer가 없을 시의) Singly/Doubly Linked List보다, List의 끝에 삽입하는 데 더욱 효율적.

(array는 Stack 영역, linked list는 heap 영역)

![Untitled](https://github.com/220v-K/CS_Study/assets/82885362/69048dce-1ca9-459d-941d-75ad348ba09d)
