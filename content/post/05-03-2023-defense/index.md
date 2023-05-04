+++
title = "I fought the committee, and I won"
date = "2023-05-03"
author = "Iraj"
cover = "/committee.jpg"
description = "A celebration of the completion of my thesis"
coverCaption = "Committee members (those who were present) and I at the defense"
useRelativeCover = true
katex = true
+++
On April 28th, 2023 I defended my PhD thesis in front of my committee and a beautiful audience filled with friends and colleagues. Two of my committee members were unfortunately unable to attend in-person, but they also happened to be the ones with the most interesting questions. 

I have posted the current version of my thesis [here](/thesis/thesis.pdf), but the reader should keep in mind that as of the time of this post, the file in question is not in its final form.

## Celebration through rumination

The thesis contains 6 chapters of original research, but I presented only two at the defense. One of these is still not published and so I won't discuss it here, but the second chapter I presented is now available on arXiv [here](https://arxiv.org/abs/2305.01052). It's the one I worked on most recently, and the I got some interesting questions about it. In this post I'll discuss one such question and the consequences it has for future research. Obviously I can't repeat the question verbatim as this happened a few days ago and I was high on adrenaline when it was asked, but it was something like

> In this model you present a continuous, large-scale description of chromatin which is agnostic to molecular details of the underlying polymer chain. In what ways could you modify your description to better approximate small-scale features such as histone modifications, for example?

The committee member was correct in saying that the model I presented doesn't care about molecular details. We describe the state of the polymer simply with an almost-uniform density field $\phi(x)$ and a velocity field $\vec v^p(x)$, so how could we account for local chemical/structual changes in the polymer? 

The first part of the answer is not too hard to imagine: we can consider the fully nonlinear regime where $\phi(x)$ varies strongly from region to region (to simulate eu- or heterochromatin). We could also give the active sources in the model some spatial variation in the force they exert, to emulate the active/inactive regions of chromatin. Finally we can model the viscosity of the polymer more precisely, adding scale dependence leading to some $\eta^p_{q,\omega}$. Of course the resulting model would not be analytically tractable at all, but we could put it into a computer.

The second part of the answer is a bit more subtle, but also probably the most obvious next addition to the model. We can keep track of the local nematic alignment of the polymer through the nematic order parameter tensor $Q_{ij}(x)$. This tensor should couple to the local alignment of forces as well as the velocity fields of polymer and solvent, and as a result should have interesting dynamics. This would give the model a continuous field to keep track of some local structural properties of the chromatin fiber, which should even be comparable to experiments! What would the coupling of $Q$ to our fields of interest be, though, is still murky...

## Ciao, NYU physics

All of that said, I was really happy with how the defense went. It was a good culmination to a hard fought 6 years of PhD, which was the ending to a long 10 year stint in the NYU physics department. I am sad to see it go, but happy to be going towards new horizons. Thanks to my committee, my friends, my collaborators, and everyone else.
