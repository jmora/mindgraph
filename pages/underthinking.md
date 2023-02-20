tags:: draft

- > [[Underthinking]] is more comfortable, fast, and cheap than overthinking. Therefore it is more prevalent. But it is never discussed. Because that would be overthinking.
  > 
  > The result: [[underthinking]] overshoots, and the lessons are learned through pain rather than thinking, with an abundance of mistakes, and pain. Possibly repeating the mistakes, or making mistakes due to a lack of [[situational awareness]] (e.g. blowing on yogurt, or never attempting AI projects again because “AI is a fad and does not work”).
	- ((63bfe277-d00c-4f26-9085-0b718262f411))
	- ((63a31a8a-cc07-40a7-9a4f-ca6cb93acb25))
	- ((63f39be9-72b7-44eb-8096-433463641de1))
- Thinking is not as much about doing things, as it is about avoiding [[busywork]] that would get in the way of getting things done.
	- In most cases, using [[brute force]] to find the best solution is not humanly possible.
	- See [[subtraction]], [[effectiveness]], [[Sisyphos curse]], “do it well, or do it again.”
- Description: insufficient thinking, in quantity or [[quality]].
- The advantages of [[speed]], e.g. first-mover advantage, result in a bias towards [[embracing ignorance]] and [[underthinking]].
	- Because [[underthinking]] is preferable to overthinking, it is more prevalent.
- When to know it is enough thinking?: further thinking yields [[diminishing returns]] (and not too early)
	- As usual, beware of the potential [[false dilemma]]: usually the point is not thinking more or less, but better.
- Examples
  collapsed:: true
	- Iterative methods when a solution or answer is available (xkcd:1838)
		- It is a search optimization problem: the least space in the manifold that is explored to reach the solution (or a "good solution" assuming several possible solutions are suitable), the best
		- iterative methods present “[[locality risk]]”, assuming that there is an evaluation and directed attempts in the [[iterative method]]. If the evaluation is merely a binary classifier (works / does not work) and it does not [[guide]] the search, we are considering [[brute force]]
		- with more iterations and less thinking, the applied method becomes brute force, or "throw everything to the wall and see what sticks". The way to avoid brute force is learning to have a more [[effective]] search space exploration
		  collapsed:: true
			- learning may be from:
			  * your mistakes: if the only lesson is: "this does not stick to the wall", without generalization or extrapolation, there is no learning, only brute force. Without extrapolation and without [[situational awareness]] any new project would require learning everything again (what did not work, may work in the current context), both requiring to learn everything from zero (no extrapolation or generalization) and assuming that what did not work will not work (assuming the same context) are mistakes resulting from underthinking and lack of [[situational awareness]]
			  * someone else's mistakes: this requires a model, and extrapolating, from their context to your context
			  * the things that work, for you, or for someone else, _contextualized_, to refine them (again, no binary classifier), and specially "why", which requires a model (possibly good for predictions), [[situational awareness]], etc.
		- this is not the explore-exploit dilemma, thinking is for decision making and prioritization of the exploration part
			- it is not about exploring more or less but better, so we have both a better option and more resources for the "exploit" part
		- Yo dawg, I heard you like iterative methods, so I put ML in your Agile project
		- Why so much iteration? Why not doing "the right thing" from the start?
			- ((63a31a8a-cc07-40a7-9a4f-ca6cb93acb25))
			- Speaking of which, passive investment:
	- Passive investment
		- e.g. see the flow of capital to algorithmic ETFs and index funds, vs stock picking
		- problem: no price discovery -- the current (y2022) distortions in prices due to passive investment are unprecedented AFAIK
		- a market is a multi-agent system for distributed (or "decentralized") decision-making
		- markets are great systems for emergent intelligence from the mythical _"homo economicus"_
		- the cognitive biases of the _homo sapiens sapiens_ cause bubbles and malfunctioning in the markets
		- we are witnessing the decoupling from reality caused by the _"homo insapiens"_
			- How long may markets stay irrational? What happens after that? According to the [[Thomas Theorem]], it might be "the new normal", perhaps even a self-fulfilled prophecy (similar to the [[Pygmalion effect]])
			- Everybody is a genius in a bull market...
	- Assigning too much weight to luck (choosing the winning lottery ticket) or hard work (buying more lottery tickets)
		- Related: [Peter Thiel: You Are Not a Lottery Ticket | Interactive 2013 | SXSW ](https://www.youtube.com/watch?v=iZM_JmZdqCw)
		  id:: 63a31817-5d54-43f9-9efe-a452d44a670b
		- while with "all other things being equal" only luck and hard work remain, we are eliminating "all the other things" from that consideration, including thinking
	- "ideas are worthless, execution is everything"
- Consequences: underthinking usually results in:
	- false dilemmas by ignoring variables that are not considered in the thinking
		- For example the explore-exploit dilemma will be considered from a quantitative perspective: split the time available between the two. While ignoring qualitative aspects, e.g. how [[effective]] our exploration or exploitation approaches, techniques, systems, methodologies are. -- (I do not like the word "exploitation", but it is what it is)
	- suboptimal solutions, accepting the first "working" solution (found perhaps by chance), without considering that refining it is possible (without thinking, the next explored possibility is more likely to be worse rather than better, improvement becomes impossible)
	- waste. In theory the main problem to avoid in the [[Lean]] methodology
	- malinvestment, underperformance, and depressed growth.
		- _Arguably_, the growth from 2008 to 2019 has been lower than what it should have been according to the monetary policy. A period of depressed growth is a depression
	- bad thinking yields diminishing returns earlier than better thinking (suboptimal logistic channel). This often results in a race to the bottom with less and worse thinking, until there is no thinking at all
	- "ideas are worthless, execution is everything" results in executing without the faintest idea, headless chicken run
- Usually,
  * [[technology risk]] is considered more addressable with a theoretical approach: thinking, researching, building a [[PoT]], etc.)
  * [[market risk]] is considered only addressable through [[empirical]] observation, sometimes implemented as “throw everything to the wall and see what sticks,” which in fact works as long as you can throw enough things to the wall, and by luck, intuition, heuristics, or some other method you can choose fairly “sticky” options
  
  In that [[context]]:
  * [[technology risk]] takes a more _autonomous_ approach: if we do not know how to build it, _can we_ figure out how to?
  * [[market risk]] takes a more _heteronomous_ approach: if we build it, _will they_ pay for it?
	- > “The least [[effective]] kind of technologists are the opportunists driven by greed. The most [[effective]] are driven by curiosity.
	  > 
	  > Scratching their own itch, not [lottery tickets](((63a31817-5d54-43f9-9efe-a452d44a670b))).”
	  > 
	  >      — [François Chollet](https://twitter.com/fchollet/status/1357539249378103300) #quote
- #speculation other reason
  collapsed:: true
	- steps:
	  * Mistakes when speaking or thinking [[risk]] ridicule.
	  * Avoid mistake [[risk]], avoid any judgement or thinking.
	  * Mistakes are now directly actions with no previous thinking, but they are acceptable: “experiments.”
	  * Data is everything, everything is extensional. There is no intension, or thinking.
	- note: experiments need to be repeated in every [[situation]], because without [[situational awareness]] it is impossible to extrapolate from one [[situation]] to an indefinitely different one.
	- Result: thinking is out of fashion.
	- Also: graduate descent method.
-