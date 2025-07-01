---
speaker: lex
title: "A Hodgepodge of Visualization Research: Provenance, User Studies, Misinformation"
# paper | invited | keynote | tutorial | panel
type: invited
slides-key: https://sci.utah.edu/~vdl/talks/2024-06-03_hodgepodge.key
slides-pdf: https://sci.utah.edu/~vdl/talks/2024-06-03_hodgepodge.pdf
slides-ppt: 
video:
# Anything you want to say about this talk
note:
date: 2024-06-03

held:
 - "[Department of Informatics](https://www.ifi.uzh.ch/) Colloquium, University of Zürich, Zürich, Switzerland, 2024-10-03."
 - "[Media and Information Technology (MIT)](https://liu.se/en/organisation/liu/itn/mit) Seminar, Linköping University, Norrköping, Sweden, 2024-06-03."
---
In this talk I want to introduce three not particularly related research topics: provenance, user studies, and visualization-based misinformation.

In visualization, provenance is widely used for action recovery, to document analysis processes, and to analyze user behavior. I will focus on an exciting new application of provenance: to bridge between code-based and interactive, visual data analysis. While traditionally these two approaches can’t be easily combined, I’ll show how we can leverage provenance data to tackle these issues and design a truly integrated analysis environment.  

Next, I will introduce the reVISit framework for designing and running empirical studies online. Traditional survey tools limit the flexibility and reproducibility of online experiments. To remedy this, we introduce a domain-specific language, the reVISit Spec, that researchers can use to design complex online user studies. reVISit Spec, combined with the relevant stimuli, is compiled into a ready-to-deploy website that handles all aspects of a user study, including sophisticated provenance-based data tracking, randomization, etc. reVISit is a community focused project and ready to use! Visit https://revisit.dev/ to get started. 

Finally, I will talk about data-driven misinformation in the form of charts shared on social networks. I will demonstrate that “lying with charts” doesn’t work the way we (used to) think about it, and introduce a few strategies to “protect” charts and charting tools from being abused by malicious users. 

I will conclude by discussing how these topics mesh together after all, as (a) each project benefits from developments in the others, and (b) they all are enabled by my approach of combining engineering with visualization research. 
