-
- In a matter, quantity beats [[quality]].
- It is the result of an [[asymmetric two-sided problem]]
  * [[quality]] may be negative.
  * quantity cannot be negative.
  $$result = quality \cdot quantity$$
- Normally the bitterness reason is:
  * We would prefer [[quality]] to be the most relevant part.
  * Quantity seems to be more relevant.
  Related: repugnant conclusion.
- It is a multiplication, both are similarly relevant (when positive), but:
  * The [[quality]] range is small and assumed, or hard to perceive and ascribed to luck or randomness.
  * The quantity aspect is more salient, resulting in salience bias.
  #speculation bitter lessons are the result of bias and [[illusion]].
  
  Note that [[quality]] is likely to be prioritized and become implicit. Reasons for prioritizing [[quality]]:
  * [[Subjective]] preference.
  * Priority in ensuring [[quality]] before increasing resource investment.
  * Possibility of negative values: negative return.
- For new participants, bitter lessons are a potential trap:
  * The [[quality]] is implicit knowledge, assumed, and not acquired.
  * Following the bitter lesson, quantity is prioritized.
  * Extraordinary quantities of a negative [[quality]] have a (extraordinarily) negative outcome.
  Related: [[sunk-cost fallacy]], [[opportunity cost]], [[underthinking]], [[malinvestment]].
- There are many potential bitter lessons in programming, [[machine learning]], and AI:
	- Human knowledge vs computation (original bitter lesson by [Rich Sutton](http://www.incompleteideas.net/IncIdeas/BitterLesson.html))
	- Fancy theories vs experiments ([François Chollet](https://twitter.com/fchollet/status/1611286048084041728))
		- Note: do not confuse a theorem with a working hypothesis. Both may be considered theoretical, but:
		  * Proven theorems provide a solid foundation for incremental iteration. ("standing on the shoulders of giants")
		  * Working hypotheses are often disposable and when proven false they may cause a return to square one (~[[Sisyphos curse]])
		- Note: "airplanes do not flap their wings." Do not confuse the human brain with intelligence, nor vice versa.
	- Data quantity vs data [[quality]], big data vs small data, curation vs aggregation.
	- [[strategy]] or [[intelligence]] vs [iterative methods]([[iterative method]]) or [[brute force]]
	  id:: 6422e774-40b8-4707-b288-4e1a03088680
		- e.g. Shakespeare vs an infinitely fast monkey
		- Note: an infinitely fast monkey is arguably a god, but for the [[purpose]] of the argument…
		- As the cost of running experiments decreases, trial and error (even [[brute force]]) yield comparatively better results (per cost) than more strategic and [[theoretical]] approaches .
		  * e.g. if the cost of an experiment is $1M, thinking about it for one week may not be overthinking. If it is $1, thinking about it for one week may be overthinking.
		  * In a degenerate case, this may result in [[underthinking]] and running 1M $1 experiments. Thinking about 1M experiments may still be possible in one week, at the right level of [[abstraction]].
		  * However, at the wrong level of [[abstraction]], or done incorrectly, the more strategic approaches may be less [[effective]] than iterative methods, especially if iteration may be fast enough (infinitely fast monkey).
		  * Similarly, strategic approaches may be less costly than [[brute force]] approaches for the same [[output]] or [[outcome]], but lose to [[brute force]] with a slower [[TTM]]. (related: [[blitzscaling]])
		      * Open question: what is most important: cost [[efficiency]] or time [[efficiency]]? What is the value of time?
	- [[strategy]] or [[intelligence]] vs luck
	  id:: 6422e774-1e0a-4728-8c49-4ddd586d123b
		- e.g. Shakespeare vs an infinite number of parallel monkeys
		- Millions competing to get the right combination without any thinking into it, only one winning: [[lottery]]
		- However, likely more than one winner: [[serendipity]] (different prize, e.g. different works from Shakespeare, individually)
		- Time spent to choose the right thing may mean losing to a thoughtless [[lottery]] winner ([[TTM]])
		- Deserts vs gardens: what is the likelihood of positive results from a random walk? ([[situational awareness]])
		- Did not win the [[lottery]]? Try again! ([[iterative method]])
		- Note: organizations are usually not as good at parallelizing as markets are
		  * markets may keep participating in lotteries as negative sum games, losses are externalities when considering only winners (related: survivorship [[bias]])
		  * organizations normally need to be more strategic (to survive)
		      * but sections of an [[organization]] may (in net terms) burn the money made by other sections, and
		      * entire organizations may burn investors money, indefinitely (see also [[financialization]])
	- [[Brute force]] vs smart algorithms
		- Writing the software for my PhD thesis (kyrie) I found several ways I could prune the tree of clauses that would be generated by normal resolution. When a branch is pruned early on, it pays off to do so, if it is too close to the leaves or the decisions to do so are computationally expensive, it does not pay off. In the end, only a few options paid off, from the many I tested.
	- Active vs passive investing
		- Passive investing (DCA on indexed funds) usually outperforms stock picking and timing the market, even when done by professionals.
		- Related: centrally planned economy vs free market economy, feudalism vs emergent [[organization]], intelligent design (human intelligence) vs Darwinism,…
		- #speculation for every hierarchical [[organization]] working as a feudal system (with executives, etc.) there is a decentralized [[organization]] (e.g. designed as a market) that outperforms the hierarchical [[organization]]. $$\left(\forall h \exists m. p(m) > p(h)\right)$$. However these organisations cannot be humanly designed, we can only throw more stuff to the wall and see what sticks, feed Darwinism with more variations, gamblers pulling the lever like there is no tomorrow.
			- This is because humans can get lucky and overshoot human capabilities occasionally, but not consistently. Trying with large enough numbers, we can get lucky and create algorithmic/emerging organizations that consistently operate beyond the humanly possible consistent operational [[quality]] (effectiveness, [[efficiency]],…)
			- i.e. humans may randomly achieve superhuman [[intelligence]] in some of their decisions, the more foundational (e.g. defining organizations that run independently) these decisions are, the more ramifications will benefit from the (randomly achieved) superhuman [[intelligence]]. The more specific (low level, concrete,…) these decisions are, the fewer ramifications and consequences will retain the superhuman aspect.
	- Knowledge vs intelligence
		- [François Chollet](https://twitter.com/fchollet/status/1637993437936123904)
		  collapsed:: true
			- Perhaps unsurprising -- at least if you're ever made a serious attempt at probing the system with *novel* questions. The distinction between intelligence and knowledge will keep getting more and more relevant over time.
			  
			  Intelligence is the ability to acquire new skills in an information-[[efficient]] way, i.e. the ability to adapt and improvise in the face of uncertainty and novelty.
			  
			  Intelligence is what you use when you don't *know* what to do.
			  
			  For any arbitrary task, you can always reach arbitrary levels of skill using arbitrarily little intelligence (down to 0), simply by reducing the amount of novelty and uncertainty featured in the task (down to 0).
			  
			  You do this by injecting information about the task into the solver system — the less uncertain and the less novel the task, the less intelligence it takes to handle it.  
			  
			  This added information can take two forms:     
			  
			  1.  Priors, i.e. you can hard-code into the system the exact solution of a task (like for a chess engine).    
			  
			  2.  Training data (aka experience), i.e. you can train a learning system on a dense sample of possible [[situation]] the task can involve, so that any future test [[situation]] will be a [[simple]] interpolation of known situations.
			  
			  
			  As such, the *skill* displayed by a system on any particular task (even a very large collection of tasks) has absolutely no connection to the *intelligence* of the system. The only way to measure the intelligence of a system is to present it with tasks it was not prepared for.
		- Related [[infinite dead end]]
		- > “Our education is confusing people to make them believe that memory is intelligence, memory is not intelligence, memory is useful as data, but intelligence is a different dimension, we have gobbled this up that.” — Sadhguru #quote
		- > “Memory is the intelligence of the fools.” — misattributed #quote
		- ((63a31a8a-cc07-40a7-9a4f-ca6cb93acb25))
	- Possibly related:
		- Model-centric vs data-centric ([Andrew Ng](https://twitter.com/AndrewYNg/status/1407042299637403652))
		- Model size vs token set size ([Hoffmann et al](https://twitter.com/DeepMind/status/1513901600968003594))
		- OpenCyc vs LLMs (see also: )
	- Better language vs more popular language
		- Tools, libraries, and network effects make disruption difficult (yet many try, [xkcd:927 — standards](https://xkcd.com/927/))
	- “Building vs selling”
		- > “it is unfortunate that hype is more valuable than actually delivering a product” — [Jon Roelofs](https://twitter.com/jon_roelofs/status/1638026406570647552)
		- There is a usual perception that creating valuable products and services (engineer) or knowledge (scientist) leads to less success (i.e. profit) than using smoke and mirrors for hype and sales (salesperson, illusionist)
			- Related: [Golgafrinchan Ark Fleet Ship B](https://hitchhikers.fandom.com/wiki/Golgafrinchan_Ark_Fleet_Ship_B)
			- According to economic theory, the flow of capital indicates (signals) what the society (as a super-organism) promotes for growth. Related: [angiogenesis](https://www.nature.com/articles/6604929) (growth of blood vessels to support tumour growth), hence the “sucking the oxygen in the room” metaphor.
		- Indeed:
		  * Creating without selling leads to poverty, classic example: Vincent van Gogh.
		  * Selling without creating may just be presales (if resulting in later customer satisfaction) or fraud (if customers are not satisfied). Creating something (engineering) may be the most straightforward approach for customer satisfaction, but illusionists should not be underestimated, and customers may never be involved ([[financialization]]).
		- ((6413211d-8d08-48df-82dd-b9695beedee5))
		- ((64199196-66f4-475f-bb36-116836c7eb6a))
- Example: bad products, good marketing.
	- A bad product with good marketing may win over a good product with bad marketing.
	- Winners write history: history is rewritten (by marketing) as: “a good product won to a bad product.”
- First mover advantage.
	- A bad product with bad foundations moves first and dominates an area.
	- New entrants have to fight an uphill battle against the incumbent, which has more traction, resources, visibility,…
	- Foundations now need to be ~10x better to have a chance, possibly 100x.
	- Example: JavaScript is often criticized (especially type casting, e.g. equality is not transitive due to type casting). But rather than anything replacing JavaScript in the frontend, it has such a strong hold of the frontend that got a significant popularity in the backend.
-
-
-