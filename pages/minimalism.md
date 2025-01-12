- ((626e666c-f9ba-4166-a0c7-697705bfd25c))
- Minimalism is interesting in the subjective perception of [[complexity]] and [[simplicity]]
	- For example, convention over configuration is:
		- "simple" in the interface, possibly making all parameters optional
		- "complex" in the design, as the convention needs to be known and provided as fallback values
	- When in doubt about what is more complex or more simple, choose the most minimalist approach
	- When in doubt about what is the most minimalist approach, make interfaces smaller, at the cost of providing default values or a few `if-then-else` branches
- "don't ask twice"
	- If some information is implied by information already available, request it only for the purpose of double checking. otherwise, infer it and "don't ask twice"
	- Bad: Asking twice adds unnecessary [[friction]]
	- Worse: Inconsistencies may be detected and result in errors
	- Worst: Inconsistencies may not be detected and produce inconsistent results
- [[don't repeat yourself]]
- https://pointersgonewild.com/2022/05/23/minimalism-in-programming-language-design/