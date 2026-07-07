# CompactSym
Repository for the paper "Compact Symbolic Representation Learning for Efficient Planning from Unsupervised Interaction"

Abstract: Symbolic representation learning from unsupervised envi-
ronment interactions is a promising strategy for enabling autonomous
agents to solve long-horizon decision problems. These approaches pop-
ularly use encoder-decoder architectures with Gumbel-reparameterized
categorical latents to discover predicates for use with classical planners.
However, if the number of symbols to be learned is unknown, the emer-
gence of overly fine-grained or redundant symbols can lead to an over-
abundance of distinct propositional states, which causes the number of
PDDL actions in the generated planning domains to increase substan-
tially. To mitigate this issue, we propose CompactSym, a regulariza-
tion procedure that employs constrained minimization of the estimated
marginal entropy of the discrete latent variables. This enables learning
significantly more compact symbolic representations and planning do-
mains while still preserving the task-relevant information by bounding
decoding loss. In experiments on a visual gridwalk task and a robotic
multi-object manipulation environment, CompactSym consistently de-
creases the number of discrete latent states used, and speeds up plan-
ning without any sacrifices in task success rate.

<p align="center">
    <img src="https://github.com/henrijacgeiss/compact_sym/blob/main/assets/Thumbnail_high_res.png" width=300>
</p>

Code release coming soon...
