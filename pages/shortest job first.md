tags:: scheduling
alias::  shortest job next, SJN, SJF

- [[shortest job first]] ([[SJF]]) is a [[scheduling]] algorithm that prioritizes the shortest thing to do
- Advantages: this approach reduces the list of pending jobs in the fastest possible way
- When to use it: when each job in the list of pending jobs causes some overhead. In this case, eliminating as many of them as soon as possible decreases that overhead, and the total workload with it.
	- Example: pending jobs may be loaded in memory, consuming it, and their memory may be accessed occasionally, causing [thrashing](https://en.wikipedia.org/wiki/Thrashing_(computer_science)). By decreasing the number of jobs ASAP, memory consumption would lower with it, and thrashing (and its impact on performance) may be prevented altogether.
	- Arguably, the same happens to people, as pending tasks cause [[cognitive load]]. Focusing on the shortest thing to take off your plate and your mind creates headspace (reduces [[cognitive load]], releases mental bandwidth) to better address everything else.
- This entry was motivated by the explanation here: [The CIA method for making quick decisions under stress | Andrew Bustamante](https://youtu.be/h5sCj8ic1rM) (Terrible explanation, IMHO)
  * Side note: does it happen to you that you see some explanation and you think: “that is terrible, it is negatively impacting [[clarity]], someone should do something about that”?