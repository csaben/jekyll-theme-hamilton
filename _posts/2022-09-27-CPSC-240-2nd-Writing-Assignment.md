<a name="Look up the term “coding convention” and briefly define what one is."></a>
<h2 style="font-family: Verdana; font-weight: bold;">Look up the term “coding convention” & briefly define what one is</h2>
<p style="font-size: 22px; font-family: Verdana;">

	A coding convention is a set of guidelines that someone or a group follow when
	writing code. This includes but is not limited to following a recommended style 
	both functionally and aesthetically.<br /><br />

</p>

<a name=""></a>
<h2 style="font-family: Verdana; font-weight: bold;">Write a post which addresses the following questions:</h2>
<p style="font-size: 22px; font-family: Verdana;">


	1) What is the benefit of everyone in a team adhering to a convention like this?<br />

		A common convention such as this allows for better readability. Code 
		can also be more portable and less likely to break (i.e. tabs vs spaces 
		errors).<br /><br />


	2) Is there any benefit to sticking to a convention even when you’re working alone?<br />

		Yes, there is. Code being more consistent is conducive to preventing 
		formatting from limiting functionality regardless of group size. I 
		generally also adhere to a max horizontal length in a given buffer
		which makes my code easy to read regardless of the screen size I'm 
		working with.<br /><br />

	3) Is there any downside to coding conventions?<br />

		It is possible that the standard being used is less readable to others.
		Also, just because you use a standard doesn't mean your code is functionally
		any better than messy code that also works. The scope of the problem you
		are trying to solve might also not necessarily require highly rigid formatting
		(i.e. my 2 minute hacky bash script that I use once doesn't need to be uber formatted
	  	if i'm in a bind for time, IMO).<br /><br />


	4) What are the areas addressed in the Google guide that you are most surprised are specified?<br />

		horizontal alignment not being required and emphasis on commented empty functions is 
		surprising.<br /><br />

		I suppose the alignment thing makes sense as it is generally a time sink and 
		may cause errors along the way.<br /><br />

		The empty/not in use fns being commented well is cool to see, actually. I 
		often times find kaggle notebooks and github sources sometimes include
		lots of extra functions that I spend half an hour decrypting just to realize they
		have no utility in the main call.<br /><br />


	5) In what areas does your own code not meet these standards?<br />

		Aplenty. I used to have a linter plugin in neovim that screamed at
		me until I made everything conform to PEP8 (python) but eventually removed it.
		It also worked with Java as I had a formatter setup for it as well.
		In truth, I need to set another one up that is less painful to the eyes
		as I don't mean to re-invent the wheel.<br /><br />

		One main standard I don't meet consistently is the javadoc or 
		docstrings for every function in python. I am actively trying to 
		include these everywhere but sometimes I'm not sure a function is 
		staying until after I fully build out a class or script and don't  
		really want to double back (i.e. stop being lazy!)<br /><br />


	6) How would you feel about being forced to use this style for the programs you write?<br />

		I wouldn't mind it, however, it would definitely take a while to
		into the swing of it. I would need to do a lot more projects in
		this format before it would come naturally.<br />
</p>
