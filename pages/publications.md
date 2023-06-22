---
layout: page
title: Publications
permalink: publications/
---

We're committed to open and accessible science.
We try to publish in open access journals whenever possible, but if one of our papers that you're interseted in is behind a paywall, please [reach out](/contact/).

{% tabs pubs %}

{% tab pubs articles %}

{% bibliography --file my-papers --query @article %}

{% endtab %}

{% tab pubs forthcoming %}

{% bibliography --file my-papers --query @online %}

{% endtab %}

{% tab pubs conference %}

{% bibliography --file my-papers --query @inproceedings %}

{% endtab %}

{% endtabs %}
