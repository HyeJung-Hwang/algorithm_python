**파이썬으로 구현하는 자료 구조**
---
1.스택 : **Last-In-First-Out**, "삽입"과 "삭제 연산이 같은 위치에서

-**list** 로 구현
```
stack=[]
#끝에서 삽입, 끝에서 삭제
stack.append()
stack.pop()
```

2.큐 : **First-In-First-Out**, "삽입"과 "삭제" 연산이 서로 다른 위치에서

-**deque** 라이브러리로 구현
```
 from collections import deque  
 q=deque([4,5,6]) 
 
 
 #앞에서 삭제, 뒤에서 삽입  
 q.append()  
 q.popleft() 
 
 #앞에서 삽입, 뒤에서 삭제
 q.appendleft()
 q.pop()
 ```
 
 -라이브러리 **없이** 구현
 ```
 l=[4,5,6]
 l.pop(o)
 l.append()
 ```



