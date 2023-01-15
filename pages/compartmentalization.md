-
- Compartmentalization is a psychological defense mechanism that keeps conflicting thoughts or feelings separated, to avoid cognitive dissonance. However, this page refers to compartmentalization as a defense mechanism for data science models and organizational decisions, in lieu of a better word.
- Example: [What Is Better: One General Model or Many Specialized Models?](https://towardsdatascience.com/what-is-better-one-general-model-or-many-specialized-models-9500d9f8751d) — [Samuele Mazzanti](https://medium.com/@mazzanti.sam)
	- > As a consequence, using specialized models involves several practical disadvantages compared to using one general model, such as:
	  > * higher maintenance effort;
	  > * higher system [[complexity]];
	  > * higher (cumulated) training time;
	  > * higher computational costs;
	  > * higher storage costs.
	  > 
	  > So, why would anyone want to do it? […]
	  > 
	  > The supporters of specialized models claim that a unique general model may be less precise on a given segment (say American customers) because it has learned also the characteristics of different segments (e.g. European customers).
	  > 
	  > I think this is a false perception born of the usage of [[simple]] models (e.g. logistic regression).
	- Yes, to some extent, but the problem is deeper, and worse.
	- Specialized models may work better by fitting [[simple]] models to specific fragments of the data, and better general models (e.g. tree-based models) work fine as general models.
	  * This is often the result of [[simple]] models (linear models), for data that is not linear.
	  * Therefore, sometimes, tree-based models solve this problem, and perform similarly (probably better) as a general model.
	- This is not always the case, sometimes general models just do not work, due to [[unknown variables]].
	  * When splitting the data and the models, these unknown variables have a smaller range in the newly split datasets, and produce smaller (acceptable) errors.
	  * These variables remain unknown, and cause the models to gradually deteriorate, requiring frequent retraining.
	  * Similarly to [[Andre bugs]], what should be a variable in the model is a constant (learned and implicit in this case).
	  * Similarly to [[embracing ignorance]], what should be known remains unknown (resulting in [[opportunity cost]]).
	- Tree-based methods may still do fine, automatically creating branches similarly to the way specialized models would be selected, with the sub-tree corresponding to one or several specialized models, *IF* the variables for model selection are included in the dataset.
	  * The unknown variables remain unknown, implying the [[risk]] of embracing ignorance.
	  * As the unknown variables remain unknown, the retraining of the models is still necessary, and in this case it is a larger model, therefore the retraining is more costly, and the deterioration of the performance more localized (harder to detect in aggregate data).
- Compartmentalization allows the three blind men to be “right” about the elephant.
	- #speculation It may be a result of ego.
	  collapsed:: true
		- > “Ego is about who's right. Truth is about what's right.” — Mike Maples Jr.
		- Truth is forfeited, for the comfort of being right. This may be the result of a [[principal-agent problem]]:
		  * The reward for being right is for the person who is right.
		  * The cost of being wrong is for someone else, possibly the employer of the person that is right.
		- Hand-in-hand: [[status game]], [[principal-agent problem]], [[ego]], [[market for lemons]], [[virtue signalling]].
- > “disciplines do not constitute different parts of reality; they are different aspects of reality, different points of view. Any part of reality can be viewed from any  of these aspects. The whole can be understood only by viewing it from  all the perspectives simultaneously.” — [Russell Ackoff](https://thesystemsthinker.com/a-lifetime-of-systems-thinking/) — There was a similar #quote from Charlie Munger about how “reality does not contradict reality” (in fact, I like more my paraphrasing here).
-