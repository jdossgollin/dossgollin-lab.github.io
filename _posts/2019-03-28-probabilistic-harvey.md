---
cover: assets/images/2019-03-28-probabilistic-harvey.png
layout: post
current: post
title: "Probabilistic models significantly reduce uncertainty in Hurricane Harvey pluvial flood loss estimates"
date: 2019-03-28
tags: papers
class: post-template
permalink: 2019-03-28-paper-rozer-harvey
navigation: true
---

My paper with [Viktor Rözer](http://http://www.lse.ac.uk/GranthamInstitute/profile/viktor-rozer){:target="_blank"} (lead author) and coauthors has been published in the **open access** journal Earth's Future.

In this paper {% cite Rozer:2019 %} we dive into the (unfortunately very relevant) challenge of estimating damages from the measurable characteristics of the floods.
Engineers traditionally use "stage-damage functions" to do this; these relate the depth of the flood to the expected damage.
Though they are straightforward to use, stage-damage functions often perform poorly in real-world situations.

Instead, we explore several statistical models for predicting flood damages using a dataset of flood damages in Houston, TX sustained during Hurricane Harvey.
The best-performing model is the "zero-inflated beta regression", which uses regression to first estimate whether damage occurred or not, and then to estimate the fraction of total damage that occurred, if any.
We found that using this model performed substantially better than commonly used models on the Hurricane Harvey dataset.

For more details, read the paper (did I mention it's open access?!)
Here's our abstract:

>  Pluvial flood risk is mostly excluded in urban flood risk assessment.
  However, the risk of pluvial flooding is a growing challenge with a projected increase of extreme rainstorms compounding with an ongoing global urbanization.
  Considered as a flood type with minimal impacts when rainfall rates exceed the capacity of urban drainage systems, the aftermath of rainfall‐triggered flooding during Hurricane Harvey and other events show the urgent need to assess the risk of pluvial flooding.
  Due to the local extent and small scale variations, the quantification of pluvial flood risk requires risk assessments on high spatial resolutions.
  While flood hazard and exposure information is becoming increasingly accurate, the estimation of losses is still a poorly understood component of pluvial flood risk quantification.
  We use a new probabilistic multi‐variable modeling approach to estimate pluvial flood losses of individual buildings, explicitly accounting for the associated uncertainties.
  Except for the water depth as the common most important predictor, we identified the drivers for having loss or not and for the degree of loss to be different.
  Applying this approach to estimate and validate building structure losses during Hurricane Harvey using a property level data set, we find that the reliability and dispersion of predictive loss distributions vary widely depending on the model and aggregation level of property level loss estimates.
  Our results show that the use of multi‐variable zero‐inflated beta models reduce the 90% prediction intervals for Hurricane Harvey building structure loss estimates on average by 78% (totalling US$ 3.8 billion) compared to commonly used models.

If you have any questions please feel free to [contact me](mailto:james.doss-gollin@columbia.edu){:target="_blank"} or you can contact Viktor, who is the paper's corresponding author.
Thanks for any thoughts!

# References

{% bibliography --cited %}
