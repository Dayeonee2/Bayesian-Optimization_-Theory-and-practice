# Bayesian Optimization Overview

As the name suggests, Bayesian optimization is an area that studies optimizationproblems using the Bayesian approach. Optimization aims at locating the optimalobjective value (i.e., a global maximum or minimum) of all possible values or thecorresponding location of the optimum in the environment (the search domain). Thesearch process starts at a specific initial location and follows a particular policy toiteratively guide the following sampling locations, collect new observations, and refreshthe guiding policy.

![Figure1-1.](https://html.scribdassets.com/3t1chy20w0d4qnmw/images/14-4096f49215.jpg)

The overall Bayesian optimization process. The policy digests thehistorical observations and proposes the new sampling location. The environment governs how the (possibly noise-corrupted) observation at the newly proposedlocation is revealed to the policy. Our goal is to learn an efficient and effectivepolicy that could navigate toward the global optimum as quickly as possible 