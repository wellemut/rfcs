- Feature Name: Metatag
- Start Date: 30.9.2019
- RFC PR: ??? https://github.com/kartevonmorgen/kartevonmorgen/issues/598
- Rust Issue: ??? [rust-lang/rust#0000](https://github.com/rust-lang/rust/issues/0000)

# Summary
[summary]: #summary

The high diversity of possible hashtags make it quite difficult to find all entries for one topic. We can introduce Meta-tags: They are a container for different tags and are as ease to use as one tag but bring many more results.

# Motivation
[motivation]: #motivation
Many movements want to use the map for one topic, but do not want to add one unig tag to all entries of that topic, to make this topic visible on one map.

- The "Social Economy" is a gerenal topic of our map. It can be #socent, #gwö, #b-corp, #sustainabel-finance... But there is no hashtag everyone is using and it is impossible to teach all active mappers to use one common hashtag.
- #GWÖ is a commonly used hashtag, but some users just use special world like #energiefeld for a #gwö-regionalgroup. If #gwö becomes a Meta Tag, that does not matter
- We can solve **spelling errors**. If #urbangardening contains the hashtags #urban-guardening and #stadtgarten, we automatically did a translation and connected synonyms and wrong written tags.
- #Futurefashion wants to create a map of all fair clothing-shops. Untill know a user would have to add all tags like #futurefashion #fairfashion #kleidung 

# Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

Explain the proposal as if it was already included in the language and you were teaching it to another Rust programmer. That generally means:

- Introducing new named concepts.
- Explaining the feature largely in terms of examples.
- Explaining how Rust programmers should *think* about the feature, and how it should impact the way they use Rust. It should explain the impact as concretely as possible.
- If applicable, provide sample error messages, deprecation warnings, or migration guidance.
- If applicable, describe the differences between teaching this to existing Rust programmers and new Rust programmers.

For implementation-oriented RFCs (e.g. for compiler internals), this section should focus on how compiler contributors should think about the change, and give examples of its concrete impact. For policy RFCs, this section should provide an example-driven introduction to the policy, and explain its impact in concrete terms.

# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC. Explain the design in sufficient detail that:

- Its interaction with other features is clear.
- It is reasonably clear how the feature would be implemented.
- Corner cases are dissected by example.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks
[drawbacks]: #drawbacks

Why should we *not* do this?

# Rationale and alternatives
[rationale-and-alternatives]: #rationale-and-alternatives

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?

# Prior art
[prior-art]: #prior-art

Discuss prior art, both the good and the bad, in relation to this proposal.
A few examples of what this can include are:

- For language, library, cargo, tools, and compiler proposals: Does this feature exist in other programming languages and what experience have their community had?
- For community proposals: Is this done by some other community and what were their experiences with it?
- For other teams: What lessons can we learn from what other communities have done here?
- Papers: Are there any published papers or great posts that discuss this? If you have some relevant papers to refer to, this can serve as a more detailed theoretical background.

This section is intended to encourage you as an author to think about the lessons from other languages, provide readers of your RFC with a fuller picture.
If there is no prior art, that is fine - your ideas are interesting to us whether they are brand new or if it is an adaptation from other languages.

Note that while precedent set by other languages is some motivation, it does not on its own motivate an RFC.
Please also take into consideration that rust sometimes intentionally diverges from common language features.

# Unresolved questions
[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

# Future possibilities
[future-possibilities]: #future-possibilities

- When we do legends and categories on any iframes, it can become really usefull to subgroup most of our content under 10 to 20 keywords. https://github.com/kartevonmorgen/kartevonmorgen/issues/372
- The Glossary of change can improve the search results 
