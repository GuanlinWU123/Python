# Day 002
## Data Structures
- Using list as Stacks
	
	- ```python
	  stack = [3, 4, 5]
	  stack.append(6)
	  stack.append(7)
	  
	  stack.pop()
	  -7
	  stack.pop()
	  -6
	  ```

- Using list as Queue
	- ```python
		from collections import deque
		queue = deque(["Eric", "John", "Micheal"])
		queue.append("Terry")
		queue.append("Graham")

		queue.popleft()
		- 'Eric'
		queue.popleft()
		- 'John'
		queue
		- deque(['Micheal', 'Terry', 'Graham'])
		```

