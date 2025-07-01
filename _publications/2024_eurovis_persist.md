---
layout: publication
title: "Persist: Persistent and Reusable Interactions in Computational Notebooks"
key: 2024_eurovis_persist
type: paper
order: 2024-1
redirect_from: /publications/2023_preprint_persist/

shortname: Persist
image: 2024_preprint_persist.png
image_large: 2024_preprint_persist_teaser.png

authors:
- kiran
- zcutler
- lex

journal-short: EuroVis
year: 2024

bibentry: article
bib:
  #booktitle: "Preprint"
  journal: Computer Graphics Forum (EuroVis)
  # publisher: IEEE
  doi: 10.1111/cgf.15092
  # url:
  volume: 43
  number: 3
  # pages: 248-258
  # month:

# award: IEEE VIS 2021 Honorable Mention Award

# Links to a project hosted on VDL, or else externally on your own site


# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

# videos:
#  - name: 'Loon Introduction'
#    youtube-id: Y7u3Kg3At9A
#    file: 2021_vis_loon.mp4
#  - name: 'Loon VIS Preview'
#    youtube-id: iRsL3WiZbhI
#    file: 2021_vis_loon_preview.mp4
#  - name: 'Loon VIS Talk'
#    youtube-id: Xz5VrBXk5J0
#    file: 2021_vis_loon_talk.mp4


# Video entry and preview video
videos:
 - name: 'Introduction'
   youtube-id: DXHXPvRHN9I
   file: 2024_preprint_persist.mp4



# Provide a preprint and supplement pdf

pdf: 2024_eurovis_persist.pdf
# supplement: 2021_vis_loon_supplement.pdf

# Link to an official preprint server
preprint_server: https://doi.org/10.31219/osf.io/9x8eq


# # Extra supplements, such as talk slides, data sets, etc.

# supplements:
# - name: VIS Talk Slides
#   link: 2021_vis_loon_talk_slides.pdf

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2024_eurovis_persist_overview.png
  caption: Different outputs supported by Persist.
- path: 2024_eurovis_persist_toolbar.png
  caption: Operations injected by Persist in the output header.
- path: 2024_eurovis_persist_df_manager.png
  caption: Persist inserts a dataframe manager in the footer for created dataframes.
- path: 2024_eurovis_persist_altair.png
  caption: Persist supports Vega-Altair charts including composite charts.
- path: 2024_eurovis_persist_datatable.png
  caption: Persist supports an interactive DataTable.
# supplements:
# - name: Study Results and Example Notebooks
#  link: https://github.com/visdesignlab/persist-examples/


code: https://github.com/visdesignlab/persist/





abstract: "
<p>
Computational notebooks, such as Jupyter, support rich data visualization. However, even when visualizations in notebooks are interactive, they are a dead end: Interactive data manipulations, such as selections, applying labels, filters, categorizations, or fixes to column or cell values, could be efficiently applied in interactive visual components, but interactive components typically cannot manipulate Python data structures. Furthermore, actions performed in interactive plots are lost as soon as the cell is re-run, prohibiting reusability and reproducibility. To remedy this problem, we introduce Persist, a family of techniques to (a) capture interaction provenance, enabling the persistence of interactions, and (b) map interactions to data manipulations that can be applied to dataframes. We implement our approach as a JupyterLab extension that supports tracking interactions in Vega-Altair plots and in a data table view. Persist can re-execute interaction provenance when a notebook or a cell is re-executed, enabling reproducibility and re-use. 
We evaluate Persist in a user study targeting data manipulations with 11 participants skilled in Python and Pandas, comparing it to traditional code-based approaches. Participants were consistently faster and were able to correctly complete more tasks with Persist.</p>
"
---

# Acknowledgements

We would like to thank our interviewees for their time and participation in the study, and the Visualization Design Lab for the fruitful discussions and feedback.
Special thanks to Jake Wagoner for helping with the `intent_inference` library.
We gratefully acknowledge funding from the National Science Foundation (IIS 1751238 and CNS 213756).
