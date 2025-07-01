---
layout: publication
title: "reVISit: Looking Under the Hood of Interactive Visualization Studies"
key: 2021_chi_revisit
type: paper
order: 2021-02

shortname: revisit
image: 2021_chi_revisit.png
image_large: 2021_chi_revisit_teaser.png

authors:
- nobre
- wootton
- zcutler
- Lane Harrison
- pfister
- lex

journal-short: CHI
year: 2021

bibentry: inproceedings
bib:
  booktitle: "SIGCHI Conference on Human Factors in Computing Systems (CHI)"
  publisher: ACM
  doi: 10.1145/3411764.3445382 
  pages: 1-13
  award:

blog-post: 

# Links to a project hosted on VDL, or else externally on your own site

project:
external-project: https://vdl.sci.utah.edu/reVISit/
# external-project: https://vdl.sci.utah.edu/mvnv-study-analysis/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
- name: "reVISit Overview"
  youtube-id: _8AkZQZ4L1Q
  file: 2021_chi_revisit.mp4
  subtitles: 2021_chi_revisit.srt


# Provide a preprint and supplement pdf

pdf: 2021_chi_revisit.pdf
supplement: 

# Link to an official preprint server
preprint_server: https://osf.io/cbw36

# # Extra supplements, such as talk slides, data sets, etc.

# supplements:
# - name: 
# - link: 

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2021_chi_revisit_task_overview.png
  caption: The reVISit task overview visualization. 


code: https://github.com/visdesignlab/revisit/
# code: https://github.com/visdesignlab/mvnv-analysis/

abstract: "
Quantifying user performance with metrics such as time and accuracy does not show the whole picture when researchers evaluate complex, interactive visualization tools. In such systems, performance is often influenced by different analysis strategies that statistical analysis methods cannot account for.  To remedy this lack of nuance, we propose a novel analysis methodology for evaluating complex interactive visualizations at scale. We implement our analysis methods in reVISit, which enables analysts to explore participant interaction performance metrics and responses in the context of users' analysis strategies. Replays of participant sessions can aid in identifying usability problems during pilot studies and make individual analysis processes salient. To demonstrate the applicability of reVISit to visualization studies, we analyze participant data from two published crowdsourced studies. Our findings show that reVISit can be used to reveal and describe novel interaction patterns, to analyze performance differences between different analysis strategies, and to validate or challenge design decisions."

---

# Acknowledgements

We want to thank Kiran Gadhave for making his study data available and for his help with the provenance tracking library. We gratefully acknowledge funding by the National Science Foundation (IIS 1751238, IIS 1815587, and OAC 1835904).
