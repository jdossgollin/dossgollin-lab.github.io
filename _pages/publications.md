---
layout: page
title: My Publications
navigation: true
class: page-template
permalink: /publications/
---

This page contains a list of my published work.
You can also visit
* [My CV](https://jdossgollin.github.io/cv-pdf/CV_Doss-Gollin_James.pdf){:target="_blank"}, which has an updated record
* My [Google Scholar Profile](https://scholar.google.com/citations?hl=en&user=6ifLBBsAAAAJ){:target="_blank"}
* My [ORCID Profile](https://orcid.org/0000-0002-3428-2224){:target="_blank"}
* My [ResearcherID Profile](https://publons.com/researcher/J-4273-2014/){:target="_blank"}

### Submitted

{% bibliography --file my-papers --query @unpublished %}

### Peer-Reviewed  Journal Articles

> **About Open Access**:
I seek to publish in open-access journals whenever possible.
However, some of my articles are behind paywalls.
If you want to read one of my papers but are not able to do so, please [contact me]({{site.baseurl}}contact/) and I will be happy to share a copy with you.

{% bibliography --file my-papers --query @article %}

### Conference Papers

{% bibliography --file my-papers --query @inproceedings %}