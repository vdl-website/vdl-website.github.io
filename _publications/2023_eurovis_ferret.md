---
layout: publication
title: "Ferret: Reviewing Tabular Datasets for Manipulation"
key: 2023_eurovis_ferret
type: paper
order: 2023-6
redirect_from: /publications/2023_preprint_ferret/

shortname: Ferret
image: 2023_eurovis_ferret.png
image_large: 2023_eurovis_ferret_teaser.png

authors:
  - lange
  - sahai
  - Jeff M. Phillips
  - lex

journal-short: EuroVis
year: 2023

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis)
  doi: 10.1111/cgf.14822
  volume: 42
  number: 3
  pages: 187-198

# award: IEEE VIS 2021 Honorable Mention Award


blog-post: 2023/09/15/ferret/

# Links to a project hosted on VDL, or else externally on your own site

project:
external-project: https://ferret.sci.utah.edu/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
  - name: 'Teaser'
    youtube-id: NtYGV-XJoBE
    file: 2023_eurovis_ferret_teaser.mp4
    subtitles: 2023_eurovis_ferret_teaser_subtitles.srt
  - name: 'EuroVis Talk'
    youtube-id: NcKqIBiipvA
    file: 2023_eurovis_ferret_talk.mp4
    subtitles: 2023_eurovis_ferret_talk_subtitles.srt
  - name: 'Case Study Demo'
    youtube-id: T3_Rmy3pBqU
    file: 2023_eurovis_ferret_case_study_demo.mp4
    subtitles: 2023_eurovis_ferret_case_study_demo_subtitles.srt




# Provide a preprint and supplement pdf

pdf: 2023_eurovis_ferret.pdf
supplement: 2023_eurovis_ferret_supplemental.pdf

# Link to an official preprint server
preprint_server: https://doi.org/10.31219/osf.io/anj8v


# # Extra supplements, such as talk slides, data sets, etc.

supplements:
- name: EuroVis Talk Slides - Keynote
  link: 2023_eurovis_ferret_slides.key
- name: EuroVis Talk Slides - PDF
  link: 2023_eurovis_ferret_slides.pdf

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2023_eurovis_ferret_domain.png
  caption: Ferret has the option to include a visualization panel.
- path: 2023_eurovis_ferret_description.png
  caption: Each analysis includes advice on how to use the charts.
- path: 2023_eurovis_ferret_formatting.png
  caption: Patterns in formatting can be seen in the overview mode.
- path: 2023_eurovis_ferret_highlight.png
  caption: Highlighting values brings them to the top of the table.
- path: 2023_eurovis_ferret_overview.png
  caption: Repeated regions can be easier to see in the overview mode.



code: https://github.com/visdesignlab/Ferret

abstract: "
<p>How do we ensure the veracity of science? The act of manipulating or fabricating scientific data has led to many high-profile fraud cases and retractions. Detecting manipulated data, however, is a challenging and time-consuming endeavor. Automated detection methods are limited due to the diversity of data types and manipulation techniques. Furthermore, patterns automatically flagged as suspicious can have reasonable explanations. Instead, we propose a nuanced approach where experts analyze tabular datasets, e.g., as part of the peer-review process, using a guided, interactive visualization approach. 
In this paper, we present an analysis of how manipulated datasets are created and the artifacts these techniques generate. Based on these findings, we propose a suite of visualization methods to surface potential irregularities.
We have implemented these methods in Ferret, a visualization tool for data forensics work. Ferret makes potential data issues salient and provides guidance on spotting signs of tampering and differentiating them from truthful data.</p>
"
---

# Acknowledgements

We wish to thank Holger Stitz, Michael Pühringer, and the LineUp authors for their support using the library, the Retraction Watch Project for access to their database, Zach Cutler and Jack Wilburn for technical help, the interview participants for their time and expertise, and the Visualization Design Lab for feedback. This work was supported by NSF IIS 1751238 and CCF-2115677.
