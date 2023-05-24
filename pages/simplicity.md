alias:: complexity, [[simple]], [[complex]], [[you aren't gonna need it]], [[YAGNI]]
tags:: [[software principle]], [[agile principles]], [[principle]]

- > [[Simplicity]]–the art of maximizing the amount of work not done–is essential. — [[Agile]]
- See [[minimalism]]
- For a discussion on what is complexity, see Moseley, B. & Marks, P. (2006), 'Out of the Tar Pit', _Software Practice Advancement_ (SPA).
	- Consideration: necessary vs unnecessary complexity
- ((6287b8de-a35f-438b-b4dd-ee37d5dfa78a))
- ((626e666c-f9ba-4166-a0c7-697705bfd25c))
- ((638fc0fd-91c7-4be8-9bd9-dc2260106496))
- ((629ccaf6-5185-4134-ba37-3251f6bb7a03))
- There are many types of simplicity. Two may be the most important (they may be combined), the main ones are [[naive simplicity]] and [[informed simplicity]]
- Other references
	- Matthew Frederik informed simplicity, see also in the context of Dunning-Kruger and [[naive realism]]
	- Midwit meme
- For an intuitive idea (and a too detailed example with code):
  collapsed:: true
	- Cases, edge cases, features, operations, etc.
	- For example:
	  
	  * This is more complex:
	  ```
	  result = []
	  for i in x:
	      for j in y:
	          for k in z:
	              ...
	              result.append(r)
	  ```
	  *  This is less complex
	  ```
	  def function(*args):
	      ...
	      return r
	  result = [function(i, j, k) for i, j, k in product(x, y, z)]     
	  ```
	-
	- This difference is not subjective, but objective. For several reasons.
	  
	  * The first fragment  has a shared scope for all the operations, the variables that may be used within the loop are not limited to the arguments of `function`. We may find out that indeed that is the case, but it requires additional attention to the code, and risk of surprises. In the second fragment we know that the body of the `function` will only use `i`, `j`, and `k`.
	  
	  * In the second fragment  we know that `len(result) == len(x) * len(y) * len(z)`. In the first fragment  we cannot know the length of the result, there may be several `append` operations, and some of them may be skipped by `if` conditions, loop control statements (`break`, `continue`,... ), etc.
	  
	  * We may find more examples as the previous. In general, the code in the second example is more "regular" #TODO
	  
	  * Note that this is not related with the computational complexity (which is the same for both), or efficiency. The second fragment will most certainly be slower due to additional function calls, similarly the mentioned control loop statements may remove arbitrarily large sets of iterations for the first fragment.
- ((626e666c-f9ba-4166-a0c7-697705bfd25c))
  id:: 626c3144-8704-4404-affc-9c84cee41178
-