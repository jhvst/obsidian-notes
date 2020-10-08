What are Types really?
For the answer to be obvious let's step back and dig a little deeper into what Types really are?

Surprisingly, Types didn't originate from the computer science industry. It actually came from mathematics! The type system is just one of the many secret affairs computer science had with math.

Consider the phrase "I'm lying". How will you communicate that intention to a computer or an alien? You convert the phrase to math. It'd become

"For any proposition p that I affirm, p is not true"

But wait, "I'm lying" is a proposition itself. If this proposition is p, then "I'm lying" is not true too. So now we've ended up with an error. If he claims he's lying, the alien will understand everything he's saying is true - which defeats the entire point.

Here's another such error:

A barber in a village shaves all men who don’t shave themselves. Now the question is, who shaves the barber?

If the barber shaves himself then he comes under the category of people who shave themselves, so he shouldn't shave himself. But if he doesn't shave himself then he comes under "people who won't shave themselves" and therefore should shave himself!

We've ended up with a paradox. Actually a pretty famous one at that. It's called Russell's paradox. Russell tried to base all of mathematics on top of logic and was troubled by this paradox.

He came up with something awesome. He went into Zen-like mode and said there simply cannot exist a predicate (I'm lying) that includes everything. There should be a class of results that hold true for a predicate and he called them, Types.

 

For example the "I'm lying" proposition holds true for all propositions I say, except that one. "The barber shaves all who don’t shave themselves" holds true for all men, except the barber. These are valid exceptions because they are of higher-order! (If the term higher-order rings a bell, it's because this is how first-order logic and higher-order logic was born)

This is just like how when we write int sum (int, int); we say sum() is a function, but that function only holds true for inputs of type (int, int). See the analogy? This is where we stole types from. https://docs.google.com/document/d/1-aLUwnN0XzLbzICnFLWfCLuD4ULYXGcKAoyRAqTuAIY/mobilebasic and discussion over at https://news.ycombinator.com/item?id=21898309

The Rise of Type Theory
 April 25, [[2020]]  General, Types https://pling.jondgoodwin.com/post/rise-of-type-theory/ [[review]]
 
 Types as axioms, or: playing god with static types https://lexi-lambda.github.io/blog/2020/08/13/types-as-axioms-or-playing-god-with-static-types/ [[2020]]
 
 Subtype Inference by Example Part 7: Spanned Error Messages https://blog.polybdenum.com/2020/08/15/subtype-inference-by-example-part-7-spanned-error-messages.html [[2020]]
 
 Type theory breakthroughs https://www.reddit.com/r/ProgrammingLanguages/comments/ib0cgu/type_theory_breakthroughs/ [[Discussion]]
 
 Breaking Through the Normalization Barrier:
A Self-Interpreter for F-omega http://compilers.cs.ucla.edu/popl16/popl16-full.pdf [[2016]]

The "unattainable" Programming Languages research problems https://www.reddit.com/r/ProgrammingLanguages/comments/g335xu/the_unattainable_programming_languages_research/fnpad1c/