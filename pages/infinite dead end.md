tags:: personal concept
alias:: endless dead end

- Related: [[sunk-cost fallacy]], [[sunk cost]], [[opportunity cost]], [[Parkinson's law of triviality]], choice supportive biases, confirmation bias,…
- When searching for a solution, an [[infinite dead end]] is an infinite path of exploration that does not contain the solution
  collapsed:: true
	- {{tweet https://twitter.com/clairevo/status/1626581276571602944}}
- The contrast between [[GOFAI]] and [[machine learning]] is similar to the contrast between direct methods and [iterative methods]([[iterative method]])
	- In [[GOFAI]] it is well known that:
		- [Herbrand structures](https://en.wikipedia.org/wiki/Herbrand_structure) contain infinite branches. Depth first search on the wrong branch will be infinite and not lead to any solution
		- Some problems are [undecidable](https://en.wikipedia.org/wiki/Undecidable_problem)
	- In [[machine learning]] and iterative methods, normally search spaces are not infinite and solutions are approximations
		- The exploration of the search space may be done with methods that worry only about [[locality risk]], e.g. [[gradient descent]], random walk, random-restart hill climbing,…
		- Experience in this [[context]] (without concern for infinity) may result in a bias to jumping into infinite dead ends, repeatedly, hoping that iteration will solve it
		  collapsed:: true
			- ![Mario 64 infinite stairs](http://img1.wikia.nocookie.net/__cb20130113194944/random-ness/images/e/e4/Mario_Endless_Stairs.gif)
			- ![Sheep is stuck. Sheep gets help. Sheep runs and gets stuck.](https://media.tenor.com/I47IGx5MeTQAAAAC/sheep-rescue.gif)
- ((63f39a93-fe3c-41fe-a4d3-713ee35070ee))
	- Note: “botanical” trees are not infinite. The maximum scale for deep learning models is indefinite, though.
- When used to [iterative methods]([[iterative method]]), people may be quick to [embrace ignorance]([[embracing ignorance]]) and learn by iterating
	- If the chosen path is an [[infinite dead end]], the best [[outcome]] is [failing fast]([[fail fast]])
	- Before going down an infinite path of despair, try to [[validate first]] it contains the solution ([[exhaust theory]])
- “Fun” “facts”:
	- [Infinite monkeys](https://en.wikipedia.org/wiki/Infinite_monkey_theorem) (or AWS scale) may not produce a solution when stuck in an [[infinite dead end]] (the bill for AWS may be arbitrarily large, though)
	- An engineer that is able to escape an [[infinite dead end]] where an arbitrary number of engineers may get stuck is not a $$10\times$$ engineer, but a $$\infty\times$$ engineer
- A [[bitter lesson]] may result in an [[infinite dead end]], consider scale for deep learning models and how “[[bigger number better]]” was an obsession until [Chinchilla](https://arxiv.org/abs/2203.15556) proved smaller models could do better.
	- In fact, arguably, larger models are dumber models: more parameters normally require more data, time, and computation to learn[ ](https://twitter.com/trylks/status/1494121801621856256)
-