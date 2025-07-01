---
layout: publication
title: "Visualization Guardrails: Designing Interventions Against Cherry-Picking in Interactive Data Explorers"
key: 2025_chi_guardrails
type: paper
order: 2025-1
redirect_from: /publications/2024_preprint_guardrails/

shortname: Guardrails
image: 2025_chi_guardrails.png
image_large: 2025_chi_guardrails_teaser.png

authors:
  - lisnic
  - zcutler
  - Marina Kogan
  - lex

journal-short: CHI
year: 2025

bibentry: inproceedings
bib:
  booktitle: "SIGCHI Conference on Human Factors in Computing Systems (CHI)"
  publisher: ACM
  doi: 10.1145/3706598.3713385
  pages: 1-19

# Links to a project hosted on VDL, or else externally on your own site

project: 
external-project: https://vdl.sci.utah.edu/viz-guardrails-study/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:


# Provide a preprint and supplement pdf

pdf: 2025_chi_guardrails.pdf
supplement: 2025_chi_guardrails_supplement.zip

# Link to an official preprint server
preprint_server: https://doi.org/10.31219/osf.io/4j9nr

# # Extra supplements, such as talk slides, data sets, etc.


code: https://github.com/visdesignlab/viz-guardrails-study

abstract: "
<p>
The growing popularity of interactive time series exploration platforms has made data visualization more accessible to the public. However, the ease of creating polished charts with preloaded data also enables selective information presentation, often resulting in biased or misleading visualizations. Research shows that these tools have been used to spread misinformation, particularly in areas such as public health and economic policies during the COVID-19 pandemic. Post hoc fact-checking may be ineffective because it typically addresses only a portion of misleading posts and comes too late to curb the spread. In this work, we explore using visualization design to counteract cherry-picking, a common tactic in deceptive visualizations. We propose a design space of guardrails—interventions to expose cherry-picking in time-series explorers. Through three crowd-sourced experiments, we demonstrate that guardrails, particularly those superimposing data, can encourage skepticism, though with some limitations. We provide recommendations for developing more effective visualization guardrails.
</p>
"
---

# Acknowledgements

This work is supported by the National Science Foundation (IIS 2041136, IIS 1751238, and CNS 2213756).
