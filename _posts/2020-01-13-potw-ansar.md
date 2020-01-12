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
---

> My resolution for the new year was to write regularly about a paper I've read.
I will try to publish these posts, which are compiled [here]({{site.baseurl}}/tag/potw/){:target="_blank"}, on a roughly biweekly schedule.
I've also added commenting using [`gitalk`](https://github.com/gitalk/gitalk){:target="_blank"} (which uses GitHub Issues as a backend, greatly boosting speed and privacy relative to other technologies like Disqus) and hope that these posts can spark a deeper conversation on and off this blog.

This week's post {% cite ansar_bigisfragile:2017 %} questions the narrative that more infrastructure spending is almost always better, and more specifically that economies of scale generally make larger and more centrally planned infrastructure relatively more attractive.
The authors point out that the theory of "bigger is better" has had a wide impact on a wide range of industries, and has also influenced thinking around infrastructure systems -- as evident on, for example, the projects advocated by the American Society of Civil Engineering's [Infrastructure Report Card](https://www.infrastructurereportcard.org/){:target="_blank"}.
The crux of their argument is outlined in the quotation below:

> We do not refute the existence of economies of scale and scope. Instead we argue that big capital investments have a disproportionate (non- linear) exposure to uncertainties that deliver poor or negative returns above and beyond their economies of scale and scope. We further argue that to succeed, leaders of capital projects need to carefully consider where scaling pays off and where it does not. To automatically assume that "bigger is better," which is common in megaproject management, is a recipe for failure.

This line of thinking builds on other papers by the same authors finding that the costs of megadams are routinely underestimated {% cite ansar_megadams:2014 %} and that China's massive infrastructure spending, widely applauded in the West, typically fails to deliver a positive risk-adjusted return {% cite ansar_china:2016 %}.
This paper attempts to bring the ideas presented in these previous works into a theoretical framework, and in particular to the fragility theory popularized by Nassim Taleb, who defines fragility "as a concave sensitivity to stressors, leading a negative sensitivity to increase in volatility" {% cite taleb_antifragile:2012 %}.
The arguments are also similar to those presented in _Strong Towns_ {% cite marohn_strongtowns:2019 %}, which suggests that much of the sprawling and auto-oriented development in the United States doesn't generate sufficient value to pay for its maintenance and eventual replacement.
By this line of thinking, a system that takes on too much debt to fund infrastructure is vulnerable to future states of the world in which the infrastructure is unneeded (eg, population declines), the infrastructure is unfit (eg, a road that becomes routinely submerged as sea level rises), or other causes is highly fragile.

The bulk of the paper consists of a series of general propositions or platitutdes, often presented without substantiating evidence, that spark thoughtful and interesting discussion.
For example, proposition 3, "as a system grows bigger, the relative size of a stressor required to break it will decline disproportionately," is taken at face value.
Alternatively, proposition 5, "systems with a low fragility threshold and low function recoverability (Quadrant 4 of below figure) require a great deal of cushioning to protect them from breaking," illustrates the implications of this cartoon:

<img src="{{ site.baseurl }}assets/images/2020-01-13-potw-ansar.png" alt="Map of Fragility" width="300"> 

Two ideas are particularly novel and worth further exploration.
First, the authors identify a distinction between “intrinsic” and “inherited” fragility and one between “apparent” and “hidden” fragility.
The idea of inherited fragility, which means that interconnected (perhaps interdependent would have been a better word) systems with low redundancy can be subject to cascading and catastrophic failure, is probably well understood in the infrastructure world -- particularly in the electricity grid.
Similarly, the authors identify that hidden fragilities of the systems can be insidious and difficult to plan for.
Both of these distinctions are interesting and merit more than a sentence or two of discussion.

A second interesting argument is that "if scalability is understood and practiced as mainly the ability to scale up, with **scant attention to scaling down** – which is the dominant approach today in both the academy and practice – then this in and of itself adds fragility."
I find this quite compelling -- a lack of ability to scale infrastructure down in keeping with population decline is one of several key reasons why the white flight and deurbanization of the past decades led to blight, decline, and debt in cities (I'm certainly not arguing that it caused this trend, but rather that their impact would have been lessened had cities been able to reduce their maintenance and debt obligations by scaling systems down).
Again I wish that the authors had further elaborated on this point.

The most substantial critique that I would level at the authors and their colleagues is that the relationship between debt and fragility is dependent on many other factors, particularly including risk aversion.
For example, a local utility might not choose to invest in a new water treatment plant if there was a 20% probability that the population of the region would decline and cause the utility's insolvency, but the federal government might be glad to invest across the country in water treatment plants even if 20% of them were likely to generate more costs than revenue.
It's true that a system with systematically bad investments may invoke "death by a thousand cuts" (Marohn argues quite convincingly that the sprawl-oriented development of the suburban US meets this criteria), but _if_ the risks are diversified then the systemic risk is low (in the case of federal spending on wastewater treatment the risks are likely diversified in some aspects, like population growth, and correlated in others, like technological innovation).
This point reminds me of a recent conference discussion I participated in, where the difference between the _economic_ viability of a project (it generates more benefits than costs, in expectation) and _finanicial_ viability (it generates sufficient revenue to maintain operation and debt/maintenance obligations at all times) sparked some debate.
This paper would benefit from further exploration of how centralized investment can reduce the probability of insolvency for a portfolio of projects that, in aggregate, provide benefits and revenue.

Despite these critiques, the fundamental argument advanced in the paper -- that centralized and static infrastructure systems are highly fragile and inflexible -- very much speaks to my heart.
As engineers, we are often trained to think of failure quite narrowly, for example as a particular component of the system breaking.
However, as systems planners (and civil engineers often find ourselves contributing to the management of water, transit, energy, and other critical infrastructure systems), this paper reminds us to consider failure more broadly.
Does a particular piece of infrastructure contribute to a better society?
Is a particular investment a better use of funds than a wide suite of plausible alternatives?
In particular, we need to remember that **large debt makes systems fundamentally dependent upon future growth** and consider whether this tradeoff is worthwhile -- which will be highly dependent upon how we define the system.

I'll conclude with a truism:

> Proposition 11. It is easier to be robust against the magnitude of harm that fragility might bring than predict or control the sources of stressor(s).

# References

{% bibliography --cited %}