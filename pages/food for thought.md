-
- Short comments and examples, hopefully interesting to think about. Some could be tweets, but I prefer my personal graph.
- On code [[readability]] and [[quality]]
  collapsed:: true
	- Example:
	  * Badr and Guth think each other's code is strange, with low [[quality]] and [[readability]].
	  * After 6 months, Badr has trouble reading, understanding, and maintaining his code. Any changes seem to require weeks of refactoring. Guth has no problem reading, understanding, or maintaining his code, most changes seem to be feasible in hours or minutes, with trivial changes in 10 lines of code or less.
	  * They are not the same.
	  * A [[two-pizza team]], were everybody agrees with Badr, and has the same outcome, might not be a good fit for Guth.
	  * Reminder: Ray Dalio, [[principle]] 5: [belivability weight your decision making](https://www.principles.com/principles/633d5d13-8610-425f-ad62-cd62347d9165/).
- On [[code reviews]]
  collapsed:: true
	- Example:
	  * Guth comments on the architecture and structure of the code, beyond the syntax: decoupling, maintainability, mutability, dependencies, assumptions, cognitive load, splitting different abstraction levels on different functions,...
	  * Badr comments on the syntactic and superficial aspects of the code: number of comments, length of lines, length of variables, if higher-order functions are really necessary, the use of functions and not methods,...
	  * They are not the same.
	- True stories:
	  * Long long time ago, in an interview for a company in the FAANG group: the interviewer asked why some words were painted in red. I answered reserved words were red in the Molokai theme (default of the real-time coding web app used for the interview), immediately ran the code and showed that it was running without errors or warnings, and the output was correct. For the next 5 minutes the interviewer insisted something had to be wrong, because some words were red, most of them starting a new line. In hindsight, I can imagine that the interviewer was more familiar with JavaScript, where semicolons are optional, but you may get a warning when omitting them with some linters, but I was writing Python, and I will not forget this story easily.
	  * I prefer 20 lines of code using 20 variables, each one in one single line and with one single letter, to 20 lines of code using one single variable with 20 letters in every single line.
	  * i.e. I prefer 20 lines of code using 20 variables, each in one line and with one single letter, to 20 lines using one single variable with 20 letters in every line. (If that reads more easily for you.)
	  *
-