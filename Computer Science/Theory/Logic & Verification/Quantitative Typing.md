The main result manifests as a “quantitative” subject reduction lemma: not only is typing preserved by each reduction step, but the size of the typing derivation goes down by exactly one in each step.

Putting all our results together, we can now prove that non-idempotent intersection types are a sound and complete characterisation of [[Termination]] in the CBN λ-calculus, and moreover the size of the typing derivation is exactly the number of steps taken to terminate.

https://bentnib.org/posts/2020-08-13-non-idempotent-intersection-types.html


Quantified class constraints provide an elegant framework for statically-sized higher-kinded types. On its own, this can raise the abstraction ceiling for high-performance languages, but it also serves as the groundwork for ‘zero-cost’ versions of functional programming abstractions such as Functor, Applicative, and Traversable.

This work shows it’s definitely possible for Rust to support higher-kinded types in a reasonable manner, but there are some less theoretical reasons why that might not be a good idea in practice. Adding ‘quantified trait bounds’ would require new syntax, and represents an additional concept for users to learn. Adding a kind system to Rust would also be a controversial change; choosing to keep types uncurried would disadvantage prospective users of the system, and changing to curried types would require rethinking of syntax and educational materials to maintain Rust’s high standard of user experience.

"Statically Sized Higher-kinded [[Polymorphism]]" http://blog.ielliott.io/sized-hkts/