Many applications require behaviour that is unpredictable yet still
satisfies strict requirements, from automated testing to route planning.
Control improvisation (CI) provides a framework for specifying such
requirements through hard constraints, which must always be satisfied,
and soft constraints, which must be satisfied with some minimum
probability, and constructs a random generator that meets these require-
ments. However, classical CI has several limitations: it requires a fixed
upper bound on improvisation length, assigns uniform lower and upper
probability bounds to all outputs rather than individual bounds, and
supports only limited forms of soft constraints. We introduce weighted
control improvisation (WCI), which uses weighted finite automata to
generalise classical CI and overcome these limitations. We investigate
the verification and synthesis problems for WCI and show that, although
they are undecidable in full generality, practically relevant instances
admit verification and synthesis algorithms.
