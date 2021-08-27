**파이썬으로 구현하는 자료 구조**
---
1.스택


2.큐 : **First-In-First-Out**, "삽입"과 "삭제" 연산이 서로 다른 위치에서

-**deque** 라이브러리로 구현
```
 from collections import deque  
 q=deque([4,5,6]) 
 
 
 #앞에서 삭제, 뒤에서 삽입  
 q.append()  
 q.popleft() 
 ```
 #앞에서 삽입, 뒤에서 삭제
 



