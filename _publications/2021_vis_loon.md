---
layout: publication
title: "Loon: Using Exemplars to Visualize Large-Scale Microscopy Data"
key: 2021_vis_loon
type: paper
order: 2021-12
redirect_from: /publications/2021_preprint_loon/

shortname: Loon
image: 2021_vis_loon.png
image_large: 2021_vis_loon_teaser.png

authors:
  - lange
  - Eddie Polanco
  - Robert Judson-Torres
  - Thomas A. Zangle
  - lex

journal-short: VIS
year: 2021

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (VIS)
  publisher: IEEE
  doi: 10.1109/TVCG.2021.3114766
  url:
  volume: 28
  number: 1
  pages: 248-258
  month:

award: IEEE VIS 2021 Honorable Mention Award

blog-post: 2022/04/27/loon/

# Links to a project hosted on VDL, or else externally on your own site

project:
external-project: https://loon.sci.utah.edu/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
 - name: 'Loon Introduction'
   youtube-id: Y7u3Kg3At9A
   file: 2021_vis_loon.mp4
 - name: 'Loon VIS Preview'
   youtube-id: iRsL3WiZbhI
   file: 2021_vis_loon_preview.mp4
 - name: 'Loon VIS Talk'
   youtube-id: Xz5VrBXk5J0
   file: 2021_vis_loon_talk.mp4




# Provide a preprint and supplement pdf

pdf: 2021_vis_loon.pdf
supplement: 2021_vis_loon_supplement.pdf

# Link to an official preprint server
preprint_server: https://doi.org/10.31219/osf.io/dfajc


# # Extra supplements, such as talk slides, data sets, etc.

supplements:
- name: VIS Talk Slides
  link: 2021_vis_loon_talk_slides.pdf

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2021_vis_loon_overview.png
  caption: The overall Loon interface includes multiple visualizations.
- path: 2021_vis_loon_exemplars.png
  caption: The exemplar view displays representative cells compactly.
- path: 2021_vis_loon_condition.png
  caption: Specific experimental conditions can be selected.
- path: 2021_vis_loon_comparison.png
  caption: Experimental conditions can be carefully compared.
- path: 2021_vis_loon_image_selection.png
  caption: Specific images can be selected by condition and time.
- path: 2021_vis_loon_image_viewer.png
  caption: Single images can be viewed with cell boundaries.
- path: 2021_vis_loon_metadata.png
  caption: Cell attributes can be viewed and selected.


code: https://github.com/visdesignlab/Loon

abstract: "
<p>Which drug is most promising for a cancer patient? A new microscopy-based approach for measuring the mass of individual cancer cells treated with different drugs promises to answer this question in only a few hours. However, the analysis pipeline for extracting data from these images is still far from complete automation: human intervention is necessary for quality control for preprocessing steps such as segmentation,  adjusting filters, removing noise, and analyzing the result. To address this workflow, we developed Loon, a visualization tool for analyzing drug screening data based on quantitative phase microscopy imaging. Loon visualizes both derived data such as growth rates and imaging data. Since the images are collected automatically at a large scale, manual inspection of images and segmentations is infeasible. However, reviewing representative samples of cells is essential, both for quality control and for data analysis. We introduce a new approach for choosing and visualizing representative exemplar cells that retain a close connection to the low-level data. By tightly integrating the derived data visualization capabilities with the novel exemplar visualization and providing selection and filtering capabilities, Loon is well suited for making decisions about which drugs are suitable for a specific patient.</p>
"
---

# Acknowledgements

We wish to thank Tarek Moustafa and Jack Wilburn for their contributions, and Soorya Pradeep and Jingzhou Zhang for participating in the CVO workshop. The research reported in this publication was supported by Huntsman Cancer Foundation through the Computational Oncology Research Initiative and the University of Utah's 1U4U seed grants and the Office of the Assistant Secretary of Defense for Health Affairs through the Breast Cancer Research Program under Award No. W81XWH-19-10065.
