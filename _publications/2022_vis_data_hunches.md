---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Data Hunches: Incorporating Personal Knowledge into Visualizations"
# Keys must be unique to each paper, see section below for more details
key: 2022_vis_data_hunches
# Select one of the options below
type: paper
order: 2022-08
# use this if this paper was previously a preprint and you need to preserve the old URL
# redirect_from: /publications/2017_preprint_lineage


# Auto-generates titles and alt-descriptors
shortname: data-hunches
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2022_vis_data_hunches.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2022_vis_data_hunches_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- lin
- akbaba
- meyer
- lex

# Include a shortened name for the journal or conference/proceedings
journal-short: VIS
year: 2022

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"

bibentry: article
bib:
  booktitle: IEEE Transactions on Visualization and Computer Graphics (VIS)
  url:
  doi: 10.1109/TVCG.2022.3209451
  pages: 504-514
  award:
  volume: 29
  number: 1

# Provide a link to the publisher's webpage if no DOI is available
publisherURL:

# Link to an official preprint server
preprint_server: https://osf.io/zud5t/

# Links to a project hosted on VDL, or else externally on your own site
#project: https://vdl.sci.utah.edu/data-hunch/
external-project: https://vdl.sci.utah.edu/data-hunch/

blog-post: 2022/10/11/data_hunch/

# Video entry and preview video
videos:
 - name: 'VIS Preview'
   youtube-id: 1Dfh4p8gA0A
   file: 2022_vis_data_hunches_preview.mp4
 - name: 'VIS Talk'
   youtube-id: IqLqajd3mY0
   file: 2022_vis_data_hunches_full.mp4

# Provide a preprint and supplement pdf
pdf: 2022_vis_data_hunches.pdf
supplement: 2022_vis_data-hunches_supplement.xlsx

# Extra supplements, such as talk slides, data sets, etc.
#supplements:
#- name: Vials Conference Talk Slides
  # Use link instead of abslink if you want to link to the master directory
 # abslink: http://vials.io/talk/
  # Defaults to a download icon, use this if you want a link-out icon
  #linksym: true

images:
- path: 2022_vis_data_hunches_overview.png
  caption: The overall prototype to view and record data hunches.
- path: 2022_vis_data_hunches_types.png
  caption: A variety types of data hunches visualized on a single chart.
- path: 2022_vis_data_hunches_options.png
  caption: Different options to select from to add a data hunch to the chart.
- path: 2022_vis_data_hunches_categorical.png
  caption: Adding a categorical value hunch to the chart.
- path: 2022_vis_data_hunches_vote.png
  caption: Upvoting/downvoting to agree/disagree with the data hunch.
# Link to the repository where the code is hosted
code: https://github.com/visdesignlab/data-hunches-package

abstract: "
The trouble with data is that it frequently provides only an imperfect representation of a phenomenon of interest. Experts who are familiar with their datasets will often make implicit, mental corrections when analyzing a dataset, or will be cautious not to be overly confident about their findings if caveats are present. However, personal knowledge about the caveats of a dataset is typically not incorporated in a structured way, which is problematic if others who lack that knowledge interpret the data. In this work, we define such analysts' knowledge about datasets as data hunches. We differentiate data hunches from uncertainty and discuss types of hunches. We then explore ways of recording data hunches, and, based on a prototypical design, develop recommendations for designing visualizations that support data hunches. We conclude by discussing various challenges associated with data hunches, including the potential for harm and challenges for trust and privacy. We envision that data hunches will empower analysts to externalize their knowledge, facilitate collaboration and communication, and support the ability to learn from others' data hunches.
"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
# Acknowledgements
We wish to thank Anders Ynnerman, Ben Shneiderman, Ryan Metcalf, and the Visualization Design Lab for fruitful discussions and feedback. This work was supported by the National Science Foundation (OAC1835904, IIS 1751238), ARUP Laboratories, and by the Wallenberg AI, Autonomous Systems and Software Program (WASP) funded by the Knut and Alice Wallenberg Foundation.
