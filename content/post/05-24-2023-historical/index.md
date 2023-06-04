+++
title = "Some more notes on historical materialism, and the limits induced by Nature."
date = "2023-05-24"
author = "Iraj"
description = "A feeble attempt at formalizing my thoughts on the relevance of historical materialism given material constraints"
useRelativeCover = true
katex = true
+++

In my last post, I wrote about the conclusions Kohei Saito came to regarding the late Marx and his thinking regarding the limits that nature imposes on economic growth. Among other things, it seems Saito came to the conclusion that in his late life, Marx essentially disavowed historical materialism (hereafter referred to as HM) as a process which drives human history. If my understanding of Saito is correct (and it very well could not be), he claims that when one considers the "metabolic" relationship between society and nature along with the limited resources provided by nature, it quickly becomes apparent that actually, "productive forces" and "economic growth" are not suitable drivers for a free, socialist human society. Saito also makes pertinent points about how HM is euro-centric and too determinist, which were likely other motivators for Marx dropping it as a theory of history late in life (if he did).

It is worth re-stating the basic premise of HM to see why this is in conflict with it. In his earlier works (for example in the German Ideology), Marx presents his view on the forces which drive history, making some key changes on themes initially written down by Hegel. In the framework of HM, what determines the features of a period in human history are the material conditions of the people living in it. In other words, the nature of the economy at a given point in time is the determining factor of that historical period. The economy, in turn, determines which are the social classes engaged in struggle during that period (slaves vs. masters, lords vs. serfs, capitalists vs. proletarians, etc.). One of the key insights of HM is that every period in history, with its class struggle, contains the seeds for the next. Specifically, since Marx is particularly interested in 19th centruy capitalism, he thinks that the capitalist era is a necessary period before the development of communism, which is the state in which humanity will achieve its full potential. The principal reason for this is the development of productive forces during that period due to the profit motive. Once industrial science, automation, and organization of society have reached such an advanced level that capitalism fails to be self-consistent, then society is ripe for communist upheaval and freedom.
Or so the story goes.

Here I just want to outline a simple argument showing that HM can hold as a world-historical process, even in the presence of strict material limits. This is more for my peace of mind than anything, and it will be far from rigorous. But it goes something like this.

At any given time, "the Economy" can be captured by some state function which we call $\mathcal G$. This is not to be confused with $g$ as defined by Piketty in his *Capital in the 21st Century*, which is the growth rate of the economy. Schematically, we can write $g = \frac{d}{dt}\mathcal G$. Then, the historical-materialist theory tells us that the (long-term) rate of economic growth is set by some complicated function of the current state of the economy

$$ \frac{d}{dt}\mathcal G = g_{HM}\left(\mathcal G\right)$$ 

Where $\mathcal G$ is the aforementioned size of the economy, or "degree of economic development". $g_{HM}$ is very complicated, and I will not set out to say much about it at all. We can envision it leading to some ratchet-like dynamics for $\mathcal G$, since once a new stage of development is reached there is no going back (barring nuclear war or something). It's worth noting that of the interpretations of historical materialism, this leans very far on the "deterministic" or "mechanistic" side.

Then, we can model the limits set by the environment. There are a collection of different resources that are limited. We can think of expendable materials, for example, such as the net amount of crude oil contained in the Earth. Some of the limiting variables are rates instead of net quantities, such as the rate of energy consumption: we can consume any amount of energy (I can just put a solar panel in my yard and wait long enough, there is essentially infinite energy there), but the *rate* of energy consumption is a limiting factor for two reasons. First, the Sun emits a finite amount of power. Second, the rate at which Earth can emit the waste heat from energy consumption is limited by its surface temperature (as stated elegantly [here](http://tmurphy.physics.ucsd.edu/papers/limits-econ-final.pdf)). We can think of a great many other limiting parameters, such as the rate of possible food production given the Earth's surface, etc.

All of the quantities can be contained within some vector $\vec p$. This vector evolves as a function of the size of the economy

$$\frac{d}{dt}\vec p = \vec k \mathcal G$$

Where $\vec k$ is a vector which relates the size of the economy to all these quantities. In general this is not a linear function, but we make it linear here just because the analogy is simpler (the argument holds either way). Some things can be said about $\vec k$: it depends on a variety of choices made by the society in question. For example, if $p_1$ is the total amount of consumed oil, then $k_1 = 0$ for a completely renewable-energy based economy, but $k_1 \neq 0$ for an economy like that of the modern-day United States. Another thing worth noting is that as far as energy consumption is concerned (let's say $p_0$ is the rate of energy consumption in the economy), there is no way to have $k_0 = 0$. This is due to the second law of thermodynamics, more or less. Our existence as humans is a *strongly* dissipative process, and we can never maintain even a steady-state economy without constant consumption of energy.

So this scheme describes the rate of resource consumption in an "infinite, boundless" historical-materialist model of the economy. $\mathcal G$ evolves over time, leading to changes in the rates at which resources are consumed, but there is no feedback from those resources back to $\mathcal G$.

My claim is simple. There is a straightforward way to include material limits on the economy, without touching the claims regarding the historical-materialist process in itself. This is done by adding a term to the first equation:

$$\frac{d}{dt}\mathcal G = g_{HM}\left(\mathcal G\right) - \vec \lambda \cdot \vec p$$ 

Here we have introduced a final set of coefficients, which we can think of as a Lagrange multiplier. $\lambda$ describes the "stiffness" of a given limiting parameter given economic growth. The larger $\lambda_i$ is for a given $p_i$, then the quicker the depletion of that resource will limit economic growth. 

A few notes: this added term need not be linear, it can be a scalar function $\lambda(\vec p)$. Making it linear just makes it easier to think of the nature of the individual coefficients $\lambda_i$ as stiffness parameters. Second, it would be probably more accurate to write $\lambda\left(\Theta\left(\vec p - \vec p_{max}\right)\right)$ where $\Theta(x)$ is some smoothed version of the Heaviside function, since when $p_i$ is far from its maximal value then it doesn't really affect economic growth.

All of this long-winded writing is just there to illustrate a simple point, however. *Adding the new limits does not in any way affect the internal logic of $g_{HM}$!!!*. To me, this seems important: historical materialism is a process, one which Marx identified as driving changes in human organization of the economy. Its strength lies in the fact that it has an internal logic, and its resulting dynamics have a definite "forward" tendency. We can impose external constraints on it (we can think of HM as some kind of engine, and we can just attach weights to the back of it to slow it down), and these might eventually stop the forward motion, but that doesn't affect the internal logic and soundness of HM as a process. That is all. 
