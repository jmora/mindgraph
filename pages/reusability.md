-
- For reusability: make something with composable components, i.e.
  * they may be swapped with other components,
  * they can be combined in other ways to build different [[systems]], and
  * a system of components is a component itself.
	- #IMHO, reusability is much easier with [[FP]] than with [[OOP]], i.e. 
	  * If we consider components are pure functions, they can be reused easily.
	  * If we consider components are objects or classes, reusing them is not so easy.
	  * Microservices are more similar to OOP when [[stateful]], and more similar to FP when [[stateless]], in either case they introduce additional problems ([fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)).
-