---
layout: publication
title: "Aardvark: Composite Visualizations of Trees, Time-Series, and Images"
key: 2024_vis_aardvark
type: paper
order: 2024-4
redirect_from: /publications/2024_preprint_aardvark/

shortname: Aardvark
image: 2024_vis_aardvark.png
image_large: 2024_vis_aardvark_teaser.png

authors:
  - lange
  - Robert Judson-Torres
  - Thomas A. Zangle
  - lex

journal-short: IEEE VIS
year: 2024

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (VIS)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi:  10.1109/TVCG.2024.3456193
  url: 
  volume: 
  number: 
  pages: 
  month:

preprint: https://osf.io/cdbm6

award: IEEE VIS 2024 Best Paper Award

blog-post: 2024/09/30/aardvark/

# Links to a project hosted on VDL, or else externally on your own site

project:
external-project: https://aardvark.sci.utah.edu/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
 - name: 'Aardvark Introduction'
   youtube-id: mA6H4-i04g4
   file: 2024_vis_aardvark.mp4
   subtitles: 2024_vis_aardvark_subtitles.srt

#  - name: 'Loon VIS Preview'
#    youtube-id: iRsL3WiZbhI
#    file: 2021_vis_loon_preview.mp4
#  - name: 'Loon VIS Talk'
#    youtube-id: Xz5VrBXk5J0
#    file: 2021_vis_loon_talk.mp4




# Provide a preprint and supplement pdf

pdf: 2024_vis_aardvark.pdf
# supplement: 2021_vis_loon_supplement.pdf

# Link to an official preprint server
preprint_server: https://doi.org/10.31219/osf.io/cdbm6

# # Extra supplements, such as talk slides, data sets, etc.

supplements:
- name: Supplemental Material
  abslink: https://osf.io/3f6kr/
- name: VIS Talk Slides - Keynote
  link: 2024_vis_aardvark_slides.key
- name: VIS Talk Slides - PDF
  link: 2024_vis_aardvark_slides.pdf

# # Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2024_vis_aardvark_overview.png
  caption: The Aardvark interface includes several visualizations.
- path: 2024_vis_aardvark_time-series.png
  caption: The time-series-first visualization.
- path: 2024_vis_aardvark_tree.png
  caption: The tree-first visualization.
- path: 2024_vis_aardvark_image.png
  caption: The image-first visualization.
# - path: 2021_vis_loon_overview.png
#   caption: The overall Loon interface includes multiple visualizations.
# - path: 2021_vis_loon_exemplars.png
#   caption: The exemplar view displays representative cells compactly.
# - path: 2021_vis_loon_condition.png
#   caption: Specific experimental conditions can be selected.
# - path: 2021_vis_loon_comparison.png
#   caption: Experimental conditions can be carefully compared.
# - path: 2021_vis_loon_image_selection.png
#   caption: Specific images can be selected by condition and time.
# - path: 2021_vis_loon_image_viewer.png
#   caption: Single images can be viewed with cell boundaries.
# - path: 2021_vis_loon_metadata.png
#   caption: Cell attributes can be viewed and selected.


code: https://github.com/visdesignlab/Aardvark

abstract: "
<p>How do cancer cells grow, divide, proliferate and die? How do drugs influence these processes? These are difficult questions that we can attempt to answer with a combination of time-series microscopy experiments, classification algorithms, and data visualization. 
However, collecting this type of data and applying algorithms to segment and track cells and construct lineages of proliferation is error-prone; and identifying the errors can be challenging since it often requires cross-checking multiple data types. Similarly, analyzing and communicating the results necessitates synthesizing different data types into a single narrative.
State-of-the-art visualization methods for such data use independent line charts, tree diagrams, and images in separate views. However, this spatial separation requires the viewer of these charts to combine the relevant pieces of data in memory.
To simplify this challenging task, we describe design principles for weaving cell images, time-series data, and tree data into a cohesive visualization. Our design principles are based on choosing a primary data type that drives the layout and integrates the other data types into that layout. We then introduce Aardvark, a system that uses these principles to implement novel visualization techniques. Based on Aardvark, we demonstrate the utility of each of these approaches for discovery, communication, and data debugging in a series of case studies.</p>
"
---

# Acknowledgements

This work was supported by NIH R01CA276653 and NIH 3P30CA042014-34S6.
The authors wish to thank Jack Wilburn for technical help, Koushik Roy, members of the Visualization Design Lab, the Scientific Computing and Imaging Institute, and the Zangle and Judson-Torres labs for their feedback and advice.
