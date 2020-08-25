# Notes on "Clean Code" by Robert C. Martin
![clean-code](https://user-images.githubusercontent.com/69808410/91224176-9119d300-e6d6-11ea-896b-eb6e2f3f30c2.jpeg)

Table of contents
=================

<!--ts-->
   * [Chapter 1: Clean Code](#chapter-1-clean-code)
   * [Chapter 2: Meaningful Names](#chapter-2-meaningful-names)
<!--te-->

 - ### Chapter 1: Clean Code
	 - #### Bad Code
		 - *I know of one company that, in the late 80s, wrote a killer app. It was very popular, and lots of professionals bought and used it. But then the release cycles began to stretch. Bugs were not repaired from one release to the next. Load times grew and crashes increased. I remember the day I shut the product down in frustration and never used it again. The company went out of business a short time after that.*
		 - *They had rushed the product to market and had made a huge mess in the code. As they added more and more features, the code got worse and worse until they simply could not manage it any longer. **It was the bad code that bought the company down.***
	 - #### The Total Cost of Owning a Mess
		 - If you have been a programmer for longer than two or three years, you have probably been slowed down by messy code. The degree of the slowdown can be significant. Over the span of a year or two, teams that were moving very fast at the beginning of a project can find themselves moving at a snail's pace. **Every change they make to the code breaks two or three other parts of the code. No change is trivial. Every addition or modification to the system requires that the tangles, twists, and knots be "understood" so that more tangles, twists, and knots can be added**. Over time the mess becomes so big and so deep and so tall, they can not clean it up. There is no way at all.
	- #### What is Clean Code?
		- Clean code should be:
			- simple and easy to read and understand
			- easy for other developers to make changes
			- easily maintainable and improvable
			- contains no unnecessary duplications.
		- *Clean code always looks like it was written by someone who cares. There is nothing obvious that you can do to make it better.*
 - ### Chapter 2: Meaningful Names
	 -  The name of a variable, function, or class, should answer all the big questions. It should tell you why it exists, what it does, and how it is used.
	 - Names should:
		 - reveal intention
		 - reveal information
		 - make meaningful distinction
		 - be pronounceable
		 - be searchable
	 - **Class** Names
		 - Should have **noun or noun phrase** names like Customer, WikiPage, Account...
	 - **Method** Names
		 - Should have **verb or verb phrase** names like postPayment, deletePage, or save...
	 - Pick One Word per Concept
		 - It's confusing to have ***fetch, retrieve, and get*** as equivalent methods of different classes.
		 - Likewise, it's confusing to have a ***controller, manager, and a driver*** in the same codebase.
