- Note: this page refers both to Agile and the (most usual) misapplication of Agile, this is not a blog post, but a set of bullets and a draft, reader discretion is advised. In case of confusion or outrage, read the manifesto and ignore this page. Here:
	- https://agilemanifesto.org/
- We may define Agile as an epistemic development [[Methodology]]
	- The point is acquiring insight more than creating a product
		- Working software is the starting point and a constant
		- The working software is used to find out the wanted software
		- The working wanted software is the side effect of the last iteration
- Related: [[Validate first]], "fail fast"
- Agile allows progress without insight, acquiring the insight
	- Good: Write working code, avoid [[Byzantine discussion]]
	- The lack of insight does not prevent the application of agile
	- The insight is not guaranteed at the end of the process, it may be a "useful [[Delusion]]"
		- All models are wrong, some are useful
		- But they may not be useful forever ([[Inductivist turkey]])
	- The tyranny of agile: If insight is available, it may be ignored, and then agile applied
		- https://medium.com/code-for-america/the-tyranny-of-agile-4e406c1da7fa
	- See also [[Ontology]] and [[Wardley map]]
- Main problems of [[Agile]], summary:
	- https://xkcd.com/1838/
	- https://www.theatlantic.com/technology/archive/2012/11/noam-chomsky-on-where-artificial-intelligence-went-wrong/261637/
		- "If you try to do that you are led to a conception of success, which is self-reinforcing, because you do get success in terms of this conception, but it's very different from what's done in the sciences"
- Main problems of [[Agile]] (long rant):
  collapsed:: true
	- Values:
		- Individuals and interactions over processes and tools
			- Individual victories vs systematic victories
			- The [[Process]] should be an asset, not a liability ([[Asset-Liability duality]]), i.e. it needs to be preferred, or improved until preferred
		- Working software over comprehensive documentation. Alternatives:
			- Code is documentation: [[Elegance]]
			- Documentation runs: [[Literate programming]] (consider: Jupyter notebook, presentation with hidden code cells)
			- Documentation is the tests / spec: [[Test driven development]]
		- Customer collaboration over contract negotiation. Risks:
			- [[Moving the goalposts]]
			- [[Adding epicycles]], especially when failure is not acknowledged or causes are not properly diagnosed
			  collapsed:: true
				- ((629ccaf6-5185-4134-ba37-3251f6bb7a03))
			- [[Delusion]], [[Confirmation bias]], [[Clever Hans]]
				- https://xkcd.com/882/
		- Responding to change over following a plan:
			- Fail to plan = plan to fail; [[Validate first]]
			- "Measure twice, cut once" vs "measure once, cut twice" (in fact, cut in each sprint)
			- See [[Parkinson's law of triviality]], change is more likely on the least relevant aspects
				- Risk: exploration of infinite trees of irrelevant possibilities, none of them valid solutions, while never exploring alternative trees where actual solutions may lie
	- Principles (only a few to comment, they are in fact not too bad):
		- Our highest priority is to satisfy the customer through early and continuous delivery of valuable software
			- This is OK, but extremely dangerous
			- The point should be solving problems, feedback on the solution may not help to understand the problem
			- Understanding what users want does not imply understanding what users need
			- See Homer Simpson's car design
		- The most efficient and effective method of conveying information to and within a development team is face-to-face conversation
			- See [[Asynchronous work]]
		- Working software is the primary measure of progress
			- It may be a [[Delusion]] though
		- Simplicity--the art of maximizing the amount of work not done--is essential
			- This is in fact good, but not always applied properly
			- IMHO, to work less: smooth processes, tools for automation, more planning, i.e. finding out by thinking rather than by coding
			- Bad application
			  1. [[Underthinking]]
			  2. [[Cargo cult]] interface
			  3. [[Adding epicycles]]
		- The best architectures, requirements, and designs emerge from self-organizing teams
			- That is good, considering [[Conway's law]]
			- Few organizations have this level or maturity, though, making this point a perfect excuse to blame the bad application of the agile principles, rather than the Agile manifesto, it seems to be here just to provide [[Plausible deniability]]
		- At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly
			- If the most senior staff had to define a [[Process]], that would be a problem for the [[Plausible deniability]]
			- Instead, focus on the behavior (or attitude) of the least senior staff. What could go wrong?
			- While constant improvement of the process is important and necessary, it is also delicate and it may backfire
				- It has to be done in a proper way, as scientific as possible
				- Otherwise, the result is pseudoscience, superstition, and bullshit
				- The behavior may adjust to spurious correlations, or overfit to anecdotal events, possibly outliers
			- At regular intervals provides regularly adjusting the narrative
- Core issue
	- If the project is easy, agile might help:
		- Agile eliminates a lot of _(potential)_ bureaucracy that would make the problem harder
		- You may choose instead [[Common sense]]. Agile may help to compensate for a lack thereof
		- Agile is vague and ambiguous enough for an easy project to become a hell of epicycles if applied in a not entirely unusual way: disregard thinking, planning, and understanding, prioritize feedback, building, and iterating
	- If the project is hard, agile might not help:
		- The space of solutions is large, most are bad, even among the ones that "seem to work"
		- There are more delusions of solutions than in fact good solutions, result: [[Cargo cult]], [[Clever Hans]]
		- It is possible to spend infinite time exploring:
			- local maxima neighborhoods, without moving to better neigborhoods
			- infinite branches that contain no good solutions
		- Eventually, this may lead to loss of credibility, but it may happen in many different ways:
			- Internal to the organization: in [[Pathological organizations]] decision makers lead technical people without decision power, the least flattering may be chosen as escape goats
			  collapsed:: true
				- Paradoxically, when mistakes have been made by decision makers, the least flattering technical people may be "less wrong" and may have been criticizing those mistakes
				- Peak pathological organization:
					- > "I was not mistaken, if you had you followed my instructions properly and worked 80h/week, we would now have a perfectly working submarine made of cheese! The only problem is your defeatist attitude!"
			- Among clients: requires rebranding (the former branding is the escape goat)
			  collapsed:: true
				- I can imagine that eventually companies run out of chances to keep doing the same mistakes with different names, but:
				  
				  > "No man ever steps in the same river twice, for it's not the same river and he's not the same man." -- Heraclitus
				  
				  If the river is fast enough, the man may not need to change to fish new fishes and keep the cash flow, indefinitely
				- i.e. eventually, but indefinitely
			- Using the technology or the technological limitations as the escape goat
			  collapsed:: true
				- We just need:
				  * more training data
				  * more training time
				  * more GPUs/TPUs
				  * more development time
				  * more epicycles
				- Alternatively:
				  * Logic symbols cannot do that, we need embeddings
				  * Embeddings cannot do that, we need logical rules
				  * etc.
				- The result may be bad reputation for some technology, which is normally not appreciated for the practitioners of that technology. This bad reputation may be deserved or undeserved
					- But by definition in the context of this paragraph, the actual problem were decision makers, exploring the wrong space for solutions, and not the technology, which is then chosen as the escape goat, i.e. it is undeserved
			- "Eventually" is far in the future: then anything is accepted as "it has always been this way"
			  collapsed:: true
				- No loss of credibility, disruption as a "new way" of doing things
			- Everybody (incl. competitors) loses credibility: skepticism, cynicism, kakonomy, or [[Lemon market]]
	-