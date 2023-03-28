tags:: summary, good practices, software good practices

- #[[personal opinion]] in the sub-points for each point in the Joel test
- [Source: Joel Spolsky](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/)
- Do you use source control?
	- Git as of [[20230319]], previously: GIT
- Can you make a build in one step?
	- automate with [[CI-CD]] when new commits get to the main branch in the repository
- Do you make daily builds?
	- This may not be so important for
- Do you have a bug database?
	- the integration in repositories (GitHub, GitLab, Bitbucket,…) is good enough to have the issues there, and normally closing them automatically when the corresponding commit (with comment) reaches the main branch
- Do you fix bugs before writing new code?
	- Alternatively, delete the code with the bugs. That “fixes” them.
- Do you have an up-to-date schedule?
	- Alternatively, how often do you have a new schedule?
	- If the schedule changes too frequently, you do not have a schedule ([[moving the goalposts]])
	- More important than a schedule, is the prioritisation and [[strategy]] to meet that schedule
	- ((64130ecd-6b76-4f84-99dd-1e168aedbe41))
- Do you have a spec?
	- This might be a significant [[inequalizer]] in only a few years time:
	  * [[LLMs]] may soon generate the code from the spec, especially when [[formal]] (e.g. [[DSL]])
	  * Then, some teams will writing specs, and the rest of the code will be considered as “compiled” code
	  * The teams that are not writing code at this level may not be competitive except for some niches, e.g. [safe-critical software](https://en.wikipedia.org/wiki/Safety-critical_system)
	  * Similarly, the teams that write code not from a [[formal]] spec but a natural language prompt may have a hard time with [[QA]] and ultimately not be competitive
- Do programmers have quiet working conditions?
	- This might have been updated to: may programmers work remotely from their homes?
	- More importantly: [[asynchronous work]] (maker time)
- Do you use the best tools money can buy?
	- Before using new tools for something, see if [[subtraction]] would be a better approach
	- If not, use the best tools, especially for [[automation]]
	- Beware of the [golden hammers]([[golden hammer]])
- Do you have testers?
	- Arguably, you may only need testers soon (see comment on having a spec). But when everybody is a tester, nobody is a tester (no [information content](https://en.wikipedia.org/wiki/Information_content) in the word)
- Do new candidates write code during their interview?
	- Well yes, but actually no
	  collapsed:: true
	  * Do they write trivial algorithms or do they have to make architectural decisions?
	  * Who makes the architectural decisions?
	  * Do you check for the coding style and [[methodology]]? — e.g. prioritising mutability or pure functions
	  
	  
	  Note:
	  * This does not mean that there is one “right” coding style,
	  * but people working together should follow the same style
	  * Alternatively, consider the [[1 person, 1 repository]] approach
		- Side note: in a coding interview, using Python, I was specifically asked for writing [[OOP]] code, mutating input parameters in-place and returning nothing (as the input parameters would be used). It did not feel like a “trap” but as a [[legacy]] standard practice from other times (perhaps Matlab times), or for memory [[efficiency]]. In any case, I am happy I did not see thousands of lines of that codebase.
- Do you do hallway usability testing?
	- How usual is this?