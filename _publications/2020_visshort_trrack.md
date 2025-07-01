---
layout: publication
title: "Trrack: A Library for Provenance-Tracking in Web-Based Visualizations"
key: 2020_visshort_trrack
type: paper
order: 2020-04

shortname: Trrack
image: 2020_visshort_trrack.png
image_large: 2020_visshort_trrack_teaser.png
redirect_from:
 - 2020_trrack
 - 2020_infovis_trrack

authors:
  - zcutler
  - kiran
  - lex

journal-short: VIS Short Papers
year: 2020

blog-post: "2020/10/28/trrack/"


bibentry: article
bib:
  journal: 
  booktitle: IEEE Visualization Conference (VIS)
  editor:
  publisher:
  address:
  doi: 10.1109/VIS47514.2020.00030
  url:
  volume:
  number:
  pages: 116-120
  month:


# Links to a project hosted on VDL, or else externally on your own site

external-project: https://apps.vdl.sci.utah.edu/trrack/

# Provide a preprint and supplement pdf

videos:
- name: "Trrack: A Library for Provenance-Tracking in Web-Based Visualizations"
  youtube-id: 09b5_LviaVM
  file: 2020_visshort_trrack_talk.mp4

pdf: 2020_visshort_trrack.pdf

# Link to an official preprint server
preprint_server: https://osf.io/wnctb/

# # Extra supplements, such as talk slides, data sets, etc.

code: https://github.com/Trrack/trrackjs

abstract: "
<p>Provenance tracking is widely acknowledged as an important component of visualization systems. By tracking provenance data, visualization designers can achieve a wide variety of important functionality, ranging from action recovery (undo/redo), reproducibility, collaboration and sharing, to logging in support of quantitative and longitudinal evaluation. Yet, for web-based visualizations, there are currently no libraries that make provenance tracking easy to implement in visualization systems. The result of this is that visualization designers either develop ad-hoc solutions that are rarely comprehensive, or don't track provenance at all. In this paper, we introduce a web-based software library --- Trrack --- that is designed for easy integration in existing or future visualization systems. Trrack supports a wide range of use cases, from simple action recovery, to capturing intent and reasoning, and can be used to share states with collaborators and store provenance on a server. Trrack also includes an optional provenance visualization component that supports annotation of states and aggregation of events.</p>
"
---

# Acknowledgements

We want to thank Sai Varun Addanki for his help with the implementation, as well as Samuel Gratzl, Marc Streit, Nils Gehlenborg, and Holger Stitz for making the precursor library available. We also want to thank past and present members of the VDL team who integrated our library in their projects and provided valuable feedback. We gratefully acknowledge funding by the National Science Foundation (IIS 1751238).
