alias:: effectiveness

-
- We may discuss the differences between [[effective]] and [[efficient]] with an example of [search space](https://en.wikipedia.org/wiki/Feasible_region) exploration
	- [[efficient]] goes through more points faster
	- [[effective]] finds better solutions going through less points
- Note that:
	- search spaces may be infinite, see [Herbrand universe](https://en.wikipedia.org/wiki/Herbrand_structure)
	- the quality of a solution may be a boolean, a real number, or a vector (multi-objective)
- Awareness of the [[context]] and the search space are more important than effectiveness and efficiency, without them some risks are:
	- [[locality risk]], especially with [[premature optimization]]
	- thinking in the wrong box, either 
	  * being too constrained or 
	  * completely missing the target
	  
	  iterative methods won't take you out of the wrong box
-