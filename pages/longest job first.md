alias:: LJF, LJN, longest job next
tags:: scheduling

- [[scheduling]] algorithm that prioritizes the longest job, inverse of [[shortest job first]]
- Advantages, given a finite set of tasks: #.v-numlist
	- This approach maximizes the parallelism that may be achieved at all times, given a finite set of tasks.
	- By decreasing the time that some processing unit is idle, we increase the utilization of the system, and reduce the time to complete the task ([[makespan]]).
- When to use it: #.v-numlist
	- The set of tasks is finite, and all of them need to be completed.
	- There are several processing units performing tasks, which would be idle (or doing something less important) if not processing one of the tasks.
	- If processing units are interchangeable the problem is easier. Otherwise, consider the [transportation problem](https://en.wikipedia.org/wiki/Transportation_theory_(mathematics)).
- Example: a team with $$x$$ members has to complete $$x + y$$ tasks in a given project ($$y > 0$$) and one member can work on a task at a time ($$1:1$$ mapping)
	- If tasks are not independent #.v-numlist
		- take the longest branch in the tree of dependencies and group as one task
		- disregard any dependency between that new task and any other new task (for now and until it is time to start the dependent task)
		- go to 1 until all tasks are independent for current considerations
	- Once tasks are independent:
	-
-