---
cover: assets/images/2020-01-13-potw-ansar.png
title: "Paper Review: 'Big is Fragile: An Attempt at Theorizing Scale'"
date: 2020-01-13
permalink: 2020-01-13-potw-ansar
tags: [Paper review]
layout: post
current: post
class: post-template
navigation: true
comments_id: 1
excerpt: "Paper review: is more and bigger infrastructure always better?"
---

> My resolution for the new year was to write regularly about a paper I've read.
I will try to publish these posts, which are compiled [here]({{site.baseurl}}/tag/potw/){:target="_blank"}, on a roughly biweekly schedule.

This inaugural paper review examines a 2017 article {% cite ansar_bigisfragile:2017 %} questioning the narrative that more infrastructure spending is almost always better, and more specifically that economies of scale generally make larger and more centrally planned infrastructure relatively more attractive than smaller and more decentralized projects.
The authors point out that the theory of "bigger is better" has had a wide impact on a wide range of industries, and has also influenced thinking around infrastructure systems -- as evident on, for example, the projects advocated by the American Society of Civil Engineering's [Infrastructure Report Card](https://www.infrastructurereportcard.org/){:target="_blank"}.
The crux of their argument is outlined in the quotation below:

> We do not refute the existence of economies of scale and scope. Instead we argue that big capital investments have a disproportionate (non- linear) exposure to uncertainties that deliver poor or negative returns above and beyond their economies of scale and scope. We further argue that to succeed, leaders of capital projects need to carefully consider where scaling pays off and where it does not. To automatically assume that "bigger is better," which is common in megaproject management, is a recipe for failure.

This line of thinking builds on other papers by the same authors, one of which finds that the costs of megadams are routinely underestimated {% cite ansar_megadams:2014 %} and another that finds China's massive infrastructure spending, widely applauded in many quarters, frequently fails to deliver a positive risk-adjusted return {% cite ansar_china:2016 %}.
This paper seeks to wrap these insights into a theoretical framework, and in particular to the fragility theory popularized by Nassim Taleb who defines fragility "as a concave sensitivity to stressors, leading a negative sensitivity to increase in volatility" {% cite taleb_antifragile:2012 %}.[^1]
The arguments are also similar to those presented in [_Strong Towns_](https://www.strongtowns.org/){:target="_blank"} {% cite marohn_strongtowns:2019 %}, which suggests that much of the sprawling and auto-oriented development in the United States doesn't generate sufficient revenue (or value -- which is not quite the same thing) to pay for its maintenance and eventual replacement.
In short, all of these works argue that a system that takes on too much debt to fund infrastructure is likely to face financial difficulties in future states of the world in which the infrastructure is unneeded (eg, population declines), the infrastructure is unfit (eg, a road that becomes routinely submerged as sea level rises), or otherwise not worth maintaining.
This matters, as an infrastructure system that is built and allowed to decay is often worse than one that never existed -- both because of the possibility of catastrophic failure (eg, the poorly maintained levees in New Orleans failed during Hurricane Katrina) or because the false perception of reliable infrastructure increases the harm when it does eventually give out.

[^1]: There are many definitions of fragility, but I think that this is the most useful. As the authors point out, however, it ephasizes fragility to tak risks rather tha fragility to "death by a thousand small cuts".

The bulk of this paper is made up of a sequence of propositions or platitutdes, often presented without much substantiating evidence.
Many follow quite naturally from Taleb's logic.
For example, proposition 3 argues that "as a system grows bigger, the relative size of a stressor required to break it will decline disproportionately."
Similarly, proposition 5, "systems with a low fragility threshold and low function recoverability (Quadrant 4 of below figure) require a great deal of cushioning to protect them from breaking," sounds like something Taleb would write, though it nicely illustrates the implications of this cartoon:

<img src="{{ site.baseurl }}assets/images/2020-01-13-potw-ansar.png" alt="Map of Fragility" width="300"> 

There are three novel ideas in this paper that are particularly worthy of further exploration.
First, the authors identify a distinction between “intrinsic” and “inherited” fragility. 
Inherited fragility here means that interconnected (perhaps interdependent would have been a better word) systems with low redundancy can be subject to cascading and catastrophic failure.
This is well understood in many corners of the infrastructure world, though generally for narrow interpretations of the system.
For example, electric grid managers understand the need to manage load and phase in real time across the entire grid.
However, understanding how electric grid outages could cascade across the water, healthcare, transportation, and security sectors remains a more complex problem and an active area of research.
In fact, this underscores a key argument: **when designing civil infrastructure systems, we need to think carefully about what our "system" really is.**

Second, the authors identify a distinction between visible fragilities that are easy to anticipate, and hidden fragilities, which can be insidious and dangerous.
Though the terminology is different, the idea of hidden fragilities is very much related to the ideas of Knightian uncertainty, Deep Uncertainty {% cite walker_deep:2013 %}, and unknown unknowns.
I wish that the authors had given more than a sentence to this idea, as this question -- how to design systems that are resilient or "antifragile" to stresses that we cannot predict or possibly even conceptualize -- remains a difficult problem.
All we are left with is proposition 11: "it is easier to be robust against the magnitude of harm that fragility might bring than predict or control the sources of stressor(s)."
Though sometimes true, it is also sometimes true that achieving robustness against a particular stressor involves a cost, which motivates some sort of cost-benefit analysis.[^2]

[^2]: this can be any type of cost-benefit analysis, not necessarily a net present value analysis using discounted cashflow.

A third interesting argument is that "if scalability is understood and practiced as mainly the ability to scale up, with **scant attention to scaling down** – which is the dominant approach today in both the academy and practice – then this in and of itself adds fragility."
I find this quite compelling -- a lack of ability to scale infrastructure down in keeping with population decline is one of several key reasons why the white flight and deurbanization of the past decades led to blight, decline, and debt in cities (I'm certainly not arguing that it caused this trend, but rather that their impact would have been lessened had cities been able to reduce their maintenance and debt obligations by scaling systems down).
Again I wish that the authors had further elaborated on this point: in my (admittedly limited) readings, I haven't come across a single paper trying to study how to design infrastructure systems that can scale down.
The answer is almost certainly in modular and/or decentralized designs, though these also incur additional costs.

The most substantial critique that I would level at the authors and their colleagues is that the relationship between debt and fragility is dependent on many other factors, particularly including risk aversion.
For example, a local utility might not choose to invest in a new water treatment plant if there was a 20% probability that the population of the region would decline and cause the utility's insolvency, but the federal government might be glad to invest across the country in water treatment plants even if 20% of them were likely to generate more costs than revenue.
It's true that a system with _systematically_ bad investments may invoke "death by a thousand cuts" (Marohn argues quite convincingly that the sprawl-oriented development of the suburban US does just this), but _if_ the risks are diversified and beneficial in the aggregate, then the systemic risk is low and there's no particular reason to worry about this investment.
This point reminds me of a recent discussion I participated in at a conference, where the differences between the _economic_ viability of a project (it generates more benefits than costs, in expectation) and _finanicial_ viability (it generates sufficient revenue to maintain operation and debt/maintenance obligations at all times) sparked some informative debate.

Despite these critiques, the fundamental argument advanced in the paper -- that centralized and static infrastructure systems are highly fragile and inflexible -- very much speaks to my heart.
As engineers, we are trained to think of failure quite narrowly, for example as a particular component of the system breaking.
However, as systems planners (and civil engineers often find ourselves contributing to the management of water, transit, energy, and other critical infrastructure systems), this paper reminds us to consider failure more broadly.
Does a particular piece of infrastructure contribute to a better society?
Is a particular investment a better use of funds than a wide suite of plausible alternatives?
The more specific point made here also applies: **large debt makes systems fundamentally dependent upon future growth** and it is imperative that engineers consider whether this tradeoff is worthwhile -- which will be highly dependent upon how we define the system.



# References

{% bibliography --cited %}