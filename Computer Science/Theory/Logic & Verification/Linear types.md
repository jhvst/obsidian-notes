Abstract. Linear types provide a way to constrain programs by specifying that some values must be used exactly once. Recent work on graded
modal types augments and refines this notion, enabling fine-grained,
quantitative specification of data use in programs. The information provided by graded modal types appears to be useful for type-directed program synthesis, where these additional constraints can be used to prune
the search space of candidate programs. We explore one of the major
implementation challenges of a synthesis algorithm in this setting: how
does the synthesis algorithm efficiently ensure that resource constraints
are satisfied throughout program generation? We provide two solutions to
this resource management problem, adapting Hodas and Miller’s inputoutput model of linear context management to a graded modal linear [[Type theory]]. We evaluate the performance of both approaches via their
implementation as a program synthesis tool for the programming language Granule, which provides linear and graded modal typing.

Resourceful Program Synthesis from Graded
Linear Types https://granule-project.github.io/papers/LOPSTR_2020_paper_pre_proceedings.pdf [[Curry-Howard]] [[2020]]

