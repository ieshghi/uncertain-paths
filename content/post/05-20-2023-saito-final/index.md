+++
title = "I wish Marxists knew about conservation laws"
date = "2023-05-20"
author = "Iraj"
description = "Discussion of Parts II-III of Kohei Saito's *Marx in the Anthropocene*, some thoughts about its relationship to physical phenomena."
cover = "/emmy_small.jpg"
coverCaption = "Emmy Noether looking down on the plebs"
useRelativeCover = true
katex = true
+++

See my [previous post](https://ieshghi.github.io/uncertain-paths/post/05-02-2023-marx-anthro/) for more on Part I of the book.

## Overview

In Parts II-III of *Marx in the Anthropocene*, Saito goes beyond the work of Marx and Lukács, to discuss the possible resolutions to the problems caused by capitalist accumulation. In Part II, he argues against the so-called "utopian" socialists of today, who envision a transcendence of capitalism using the new technologies it has given society (computers and the Internet, mainly). He primarily claims that since capital quickly "subsumes" any new technological development, it is impossible to leverage these to liberate the proletariat from capitalist control (see below).

Then, in Part III, the author makes his first set of positive claims. As the title of the book hints, he makes a Marxist argument for de-growth. I will lay out the main points of this argument, but it is worth already pointing out that as a scientist, I was a bit disappointed in the degree of insight I got from this regarding de-growth as an economic strategy. This made me consider what the goal of the work is in the first place, because it seems I may have initially misunderstood it.

## You can't subsume everything!

First I would like to quickly discuss the points made by Saito in Part II of the book. In here, he argues against a few different strains of modern "utopian socialism" based around the availability of new technologies. In essence, the new utopianists claim that technology may allow us to transcend capitalism and enter FALC ("Fully Automated Luxury Communism"). This is due to a combination of factors. First, information technology makes scarcity irrelevant for certain commodities (I can make as many copies of a song as I want, at essentially 0 cost). Second, the open-source culture around many new technologies leads to interesting network effects, with tech labor self-organizing in non profit-motivated ways, and offers alternate structures for the performance of work in the 21st century. Finally, the new technologies allow us to automate away a lot of menial labor, thus freeing up humanity to spend time on more rewarding labor, or simply leisure. All that needs to happen is some political change, and this will take place simply because the new technologies expose the contradictions in capitalism.

Saito thinks this is too naive, and to back up his claim he uses Marx's concept of capitalist "subsumption" of labor. In short, capital tames production lines in two ways, which usually take place one later than the other. First, the capitalists "formally" subsume the labor process, simply by slapping a corporate name on an otherwise unchanged production line (for example, if Microsoft were to buy rights to the Linux kernel or something crazy like that, but left the code as is). Once this takes place, the process of "real" subsumption begins. This corresponds to the slow dissociation of the workers from any meaningful portion of the labor process: tasks are broken down, specializations are assigned, decision-making is moved to the higher-ups in the company, and workers are slowly disposessed of any control they may have had over the process beforehand. This is done in the name of efficiency (and often does lead to increases in efficiency and profits) but the primary goal is to maximize domination of the labor force by the owners of the firm. 

Saito argues that this process, while slow, essentially removes any revolutionary capacity inherent in any technology. Capitalism can co-opt anything, and any leverage that workers had due to their expertise in something new is eventually stripped away. As we've seen the Internet become increasingly commodified since the 1990's, this is a compelling argument. But I am still not convinced. Specifically, the fact that digitized information has essentially 0 commodity value (because I can copy it) to me seems fundamentally revolutionary. The ripple effects of it are still being felt: advertising is the main means of profit-making for most websites, content creators are increasingly unable to make money off of royalties, etc. no matter how much DRM they try to attach to every audio file we try to listen to, the reality is that information is now mostly free. I am unsure what pathway to draw between this and revolution, but I don't think this can be successfully subsumed, something's got to give there. The argument that automation and network effects can be subsumed seems more solid to me, but my personal experience working with and around modern technology makes me doubt this picture a bit too. Granted, all of my work has been in academic settings, which are a bit insulated from typical capitalist encroachment (although universities these days are little else than real estate holding companies with a research arm giving them prestige and some justification for their nonprofit status). Still, the places where new technologies are being invented (startups, academic labs, government labs) do not feel like the subsumed factories Marx (and Saito through him) paint pictures of. 

## Emmy Noether as a de-growth thought leader

I've already written a small novel today, but I haven't even gotten to my complaints about Part III. This is where Saito actually makes some claims! I'm not trying to be snarky, I really appreciate the heavy lifting done in the earlier chapters to situate the reader in the intellectual landscape. In this section, Saito actually puts together a theory of de-growth based on Marxist concepts. 

I went into it expecting to learn something insightful either about *why* de-growth is important, or *how* de-growth should be achieved. I kind of got neither. The primary point being made in this chapter is that Marx's theory of metabolism (which I outlined in the [previous post](https://ieshghi.github.io/uncertain-paths/post/05-02-2023-marx-anthro/)) naturally leads to the conclusion that we must maintain asteady-state economy if we don't want to destroy the environment. Furthermore, this is only feasible if the economy stops growing, as growth necessitates depletion of natural resources.

To a scientist, this is far from surprising. In essence, what Saito has discovered in Marx is the concept of a conservation law. If I want to be annoying, I can write a generic conservation law like this
$$ \dot m = \oint_{\Omega} \vec J_m \cdot \vec{dS}$$

Here, $m$ is the quantity of some material (say, nutrients in the soil). The dot over the quantity indicates a change over time. $J_m$, meanwhile, indicates the *flux* of that quantity, basically how much that quantity is flowing through some region in space. Then the integral $\oint_{\Omega}$ indicates an integral over the bounding surface of some domain of interest $\Omega$. In my overstretched analogy, let's consider $\Omega$ to be the domain where humans perform industrial activity (a.k.a. "cities"). Then, what the expression says is that the change in the total amount of nutrients in the soil is equal to the net amount of nutrients being absorbed vs. ejected from cities. Obviously if the integral is nonzero then the amount of nutrients changes. This takes care of the first part of the logic above, that if we want to "maintain the environment" the economy must be in a steady-state, that is, we must absorb as much from the environment as we expel. 

This is not news! We've known this since the days of Lavoisier, although Emmy Noether (the lady in the cover photo) formulated the most powerful statements regarding conservation laws in physics. Her result doesn't exactly apply here because the economy is a (very) dissipative system, but in spirit it is exactly what Marx is saying: conservation laws apply when systems display a certain symmetry. If we want the economy to be time-translation-symmetric (a.k.a. in a steady state) then it must conserve certain quantities in doing so. 

The next logical step Saito takes is to argue that for the economy to be in a steady-state, we must have no economic growth. This is in some ways a tautology, and follows from the above. And I am left disappointed. Is all of the insight of the late Marx contained in a statement which was known to scientists for a good century prior?

It's worth considering all of this in a bit more detail. Which quantities must be conserved and which mustn't? It seems to me that anything that we get from the Earth must be treated as finite (nutrients, water, minerals), while energy itself is a more blurry quantity. This is funny because in Noether's treatment it's energy conservation which is associated with a system in a steady-state, but that is when the system is closed and does not dissipate energy. In the case of the economy, since we dissipate energy (the second law of thermodynamics cannot be fought), a constant supply of it is needed, *even if the economy is maintained in steady-state*. Thankfully, we have an essentially infinite supply of energy from the sun (and from fission + fusion power if and when we choose to use them). But the primary takeaway holds: there are finite materials for our use in the environment, therefore the economy cannot grow indefinitely. Who needs Marx to know this?

And this is all ignoring the most important argument for de-growth that we have today: *even if* the economy is in a steady-state, at the current high rate of fossil-fuel consumption we are, resource scarcity is not the limiting factor by a long shot! Global warming, an effect which Marx could not have known about, is the most pressing issue we have to face. Even if somehow economic growth had stopped after like 1920, global warming would have become a problem if the means of energy production had not switched to renewables. This cannot be captured by a conservation law, it is unrelated to the concept of metabolism, and it is the reason why the green revolution is imperative. Not the depletion of the soil, or the waste of any other resources.

## What was this book *supposed* to do?

Which brings me to the question I ended up asking myself once I was done with this book. What was the point of it? We already know that IF we want to have an economy which is in steady-state and doesn't continuously rob nature of its resources, then we must stop depending on growth. We've known this for centuries (at least those of us who don't delude ourselves with capitalist fables). So what does it matter what the late Marx had to say? 

I think there are a couple of interesting things that come out of this chapter, as far as Marx scholarship is concerned. One is a decoupling of Marxist analysis of capitalism from historical materialism. This is huge! I didn't get to discuss this, but in Part III Saito shows that in his late life Marx began to disavow his earlier attachment to historical materialism (HM), which is a description of the processes by which dialectics and human production drive the progress of history. I don't know how to feel about this! I think HM is probably the most insightful piece of Marxist theory I have ever encountered, and so "dropping" it seems like too radical a move. It feels to me that HM is a great *descriptor* of the progress of political economy throughout the centuries past, but just like many physical theories we encounter day to day, it is applicable only in an infinite boundless domain. Once you apply boundary conditions to it like the finite resources available to the economy, its applicability begins to fail, or rather, new forces take over and prevent the continuous economic "progress" and "growth" we have been used to for centuries.

The second thing which comes out of this, which it seems to me is most important to Saito but less important to me, is a rescuing of the Marxist tradition in the context of the new, "green" left. Saito wants to maintain that Marx is relevant, that he has things to say which are of use to us. But his book, if anything, proves the opposite. Yes Marx *thought about* things which are relevant to where we are today, but he lived in such a different time, when capital was still in its early growth stages, there's no way he would have significantly insightful things to say compared to those of us who are living through modern late capitalism. Yes from a historical perspective it is insteresting that Marx read about soil depletion and thought about the effects of capitalism on ecology, but as a driver for political action, this does not have significant value today (I thought “The philosophers have only interpreted the world, in various ways. The point, however, is to change it"). Why does the "red" left need to be attached to the thought of a single man from 150 years ago? Why can we not move on and accept that certain people make contributions at certain times, and call it a day? 

This is why I would have never succeeded as a philosopher or historian.