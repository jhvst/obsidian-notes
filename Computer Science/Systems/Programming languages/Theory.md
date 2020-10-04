I somewhat fall into the stereotypical [[Haskell]]/Coq/Agda/[[Idris]]-loving, category theory embracing, [[Type theory]] enthusiast, functional programmer camp that many programmers love to make fun of (if they even know of our existence). I view programming as a craft, and I'm always eager to lean more about (and teach!) how to build better software. But I also write Java code at a big tech company because, unfortunately, it seems to pay the bills better than more mathematically-inspired programming methodology. Given the opening sentence of this post, it may come as no surprise that I care about different aspects of programming languages than most programmers, for example:

Parametricity
[[Soundness]] (of a type system)
Immutability, purity, and referential transparency
Equational reasoning
Higher-order abstractions (higher-kinded types, higher-rank types)
Understanding the tradeoffs of data/codata, [[Recursion]]/corecursion, induction/coinduction, finite/infinite, eager/lazy, strict/non-strict, least/greatest fixpoints, etc.
Compositionality: denotational semantics, models, adequacy, etc.
In general: simple, orthogonal programming language features that do one thing well (as opposed to, say, OOP classes as they exist in mainstream languages)
It's not academic curiosity that attracts me to these things. I care about such things because they allow me to feel these happy feelings:

This code makes sense to me because it fits in my head. There isn't any unnecessary boilerplate where bugs could be hiding. The logic is expressed concisely in the domain of my application. There won't be any surprising side effects or spooky action at a distance. It will work the same way every time. Many [[invariants]] are maintained automatically by the type checker, and the rest are few enough such that I can manually vet them (e.g., with equational reasoning, induction, etc.), if perhaps only informally. LGTM!

When browsing this sub, I often feel like many (most?) of the people here would rather discuss trivial syntactic choices rather than these "deeper" theoretical topics (Wadler's Law, I guess). That's not to say syntax isn't important—it's the user interface to your language after all!—but it doesn't feel right to have it dominate the conversation with so much else left by the wayside.

I know that a lot of theory stuff is inaccessible to practitioners. That's frustrating, as it was (and still is!) for me when I started learning PLT. It's also not good for theorists; it's discouraging to work out some novel idea only to find that most programmers get "lost at hello" because e.g. they don't know what a sum type is. Do we need better pedagogy, or is it a fundamental lack of interest?

I guess I'm wondering:

Do you care about getting the theory and principles "right", or do you take a more pragmatic approach to language design?
Do you think universities are/aren't doing a good job of teaching the fundamentals of programming languages?
Do I seem like a strange extraterrestrial to you? Ask me anything?

https://www.reddit.com/r/ProgrammingLanguages/comments/i8bjnb/do_you_care_about_theory/ [[2020]]