-
- Tweets
  collapsed:: true
	- {{tweet https://twitter.com/backus/status/1652433895793516544}}
	- {{tweet https://twitter.com/emollick/status/1653069121704058883}}
	- {{tweet https://twitter.com/j_mora/status/1558710013769793537}}
	- {{tweet https://twitter.com/j_mora/status/1650394143380611073}}
	- {{tweet https://twitter.com/trylks/status/1650476014789599232}}
	- {{tweet https://twitter.com/trylks/status/1653065920485507072}}
- High level idea: have a conversation with JARVIS and get working code from it
- I am not very optimistic about the [[abstraction]] achievable with [[natural language]], see “legalese”
  
  $$abstract = [[concise]] + precise$$
  
  However, I have no business in [[conversational programming]] (nothing to win), and most predictions have a good chance of ageing like milk,…
- Nonetheless, I decided to try ChatGPT and see what it could write about the topic with some guidance, so here are the results:
  collapsed:: true
	- Prompt: I do not think [[conversational programming]] is here to stay. The future of programming is writing more abstract code, as understood by Edsger W. Dijkstra, i.e. higher level code, as understood by Alan Perlis. I can see why people think that natural language, e.g. English, fulfils this role, but when we try to be technically precise in English, we produce “legalese.” We are more likely to succeed with higher level programming languages like constraint programming, declarative programming, logic programming and [[functional programming]], all of them left aside for [[OOP]] and related methodologies (dominating nowadays). From this [[perspective]], [[conversational programming]] is a dead end, it may hog [[attention]] and resources, and set us back, repeatedly, similarly to how visual programming keeps returning but ultimately never becoming mainstream. Understanding all of the previous is very difficult for executives without an extensive technical background, explain it as clearly as you can, so that they can understand where higher-level programming and [[abstraction]] lead software to.
	- Answer:
	  
	  To explain higher-level programming and [[abstraction]] in simpler terms, let's start by comparing programming to cooking.
	  
	  Imagine that you're teaching someone how to cook a meal. In the beginning, you might provide step-by-step instructions, detailing every action they need to take. This is similar to low-level programming, where the code is closely tied to the hardware and provides specific, detailed instructions.
	  
	  As the person becomes more experienced, you might give them more abstract instructions, such as "prepare the vegetables" or "cook the meat." They now have the basic understanding to fill in the details themselves. This is similar to higher-level programming, where the code is more abstract, and the programmer doesn't have to worry about low-level details.
	  
	  Now, let's discuss the different types of higher-level programming languages you mentioned and their [[importance]]:
	  * Constraint programming: This is like giving the person a set of rules or constraints to follow when cooking, such as using only certain ingredients or adhering to dietary restrictions. The person can then create a meal within these boundaries.
	  * Declarative programming: Instead of explaining the step-by-step [[process]], you simply describe the desired [[outcome]], e.g., a delicious pasta dish. The person then figures out how to achieve that result. This approach focuses on the "what" instead of the "how."
	  * Logic programming: Here, you provide a set of facts and rules, and the person uses logical reasoning to create the meal. It's like solving a puzzle to find the right combination of ingredients and cooking techniques.
	  * [[Functional programming]]: In this case, you break down the cooking [[process]] into smaller, independent tasks or functions. The person can then combine these tasks to create the final meal, promoting reusability and modularity.
	  
	  These higher-level programming languages allow developers to focus on the bigger picture, rather than getting bogged down in low-level details. They promote more [[efficient]], reusable, and maintainable code, ultimately leading to better software.
	  
	  As for [[conversational programming]], it aims to make coding more accessible by using natural language, like English. However, as you pointed out, this can lead to ambiguity and [[complexity]], similar to "legalese." While it might have some applications, it is unlikely to replace the more abstract, precise nature of higher-level programming languages.
	  
	  In conclusion, higher-level programming languages and [[abstraction]] are crucial for the future of software development, as they enable developers to create more [[efficient]], maintainable, and scalable solutions. [[Conversational programming]], while interesting, may not be the best approach for achieving these goals.
	- Not bad, let's try again: Prompt: I do not think [[conversational programming]] is here to stay. The future of programming is writing more abstract code, as understood by Edsger W. Dijkstra, i.e. higher-level code, as understood by Alan Perlis. I can see why people think that natural language, e.g. English, fulfills this role, but when we try to be technically precise in English, we produce “legalese.” We are more likely to succeed with higher-level programming languages, an effort forgotten with the mirage of [[abstraction]] in [[OOP]] and related methodologies (dominating nowadays). From this [[perspective]], [[conversational programming]] is a dead end; it may hog [[attention]] and resources and set us back, repeatedly, similarly to how visual programming keeps returning but ultimately never becoming mainstream. Understanding all of the previous is very difficult for executives without an extensive technical background; explain it as clearly as you can, summarizing any background that may be relevant so that they can understand where higher-level programming and [[abstraction]] lead software.
	- Answer: To understand the argument against [[conversational programming]], it's important to first provide a brief background on programming languages and [[abstraction]].
	  
	  Edsger W. Dijkstra and Alan Perlis both advocated for higher-level programming languages. Dijkstra emphasized the importance of clear, precise, and structured code, while Perlis focused on the need for more abstract and expressive languages that allowed for easier problem-solving.
	  
	  Conversational programming, which involves using natural language (like English) to communicate with a computer, may seem like a natural progression towards higher-level programming. However, there are concerns that conversational programming may lead to imprecise and ambiguous code, similar to the complexity found in legal documents (legalese).
	  
	  Object-Oriented Programming (OOP) and related methodologies have also attempted to bring about abstraction, but some argue that they have not gone far enough, leading to the resurgence of visual programming and conversational programming. Visual programming, which involves using graphical elements to represent code, has been tried multiple times in the past but has never become mainstream.
	  
	  To explain this issue to non-technical executives, one could say:
	  * Higher-level programming languages aim to make code more understandable and easier to work with, simplifying complex systems. Conversational programming, where we use natural language to interact with computers, may seem like a step in this direction. However, there are concerns that this approach could lead to unclear and imprecise code, similar to the complexity found in legal documents.
	  * While recent programming methodologies like OOP have attempted to increase abstraction, some argue that they have not gone far enough. This has led to the repeated resurgence of alternatives like visual and conversational programming, which have not gained mainstream adoption. Instead of focusing on conversational programming, it may be more beneficial to invest in developing higher-level programming languages that offer better abstraction without sacrificing precision and clarity.
	- There are several mistakes there, including understanding some things backwards, which is perfect, because it is an 
	  example of how trying to be [[concise]] without having [[formal]] semantics leads to misunderstandings.
	- Would GPT100 solve that? Probably not. It will have to do a lot of disambiguation to understand language properly, which would require:
	  * A knowledge base to understand a particular user, considering previous conversations, disambiguating what I mean with “[[abstraction]]” which is not _exactly_ the same anyone else means with [[abstraction]] (for every person, and every word)
	  * Going deep into references like Dijkstra and Perlis, to disambiguate further.
	  * Making predictions, especially when doing something new (without extensive similar training examples)
	  * Handling pragmatics (it is hard to disambiguate what and how without knowing why)
	  * And probably more stuff, this is just off the top of my head, this is not a paper, or a [[blog]], it is a [[personal]] note that happens to be public.
	  
	  Considering that:
	  * Scale will not solve that
	  * A system solving that would have a different name (for branding, even in the unlikely event of  coming from OpenAI _tomorrow_)
	  
	  Then we can conclude that GPT100 would not solve that. But conversational AI might do it, in a few years. It is always 5 years away.
	-
-