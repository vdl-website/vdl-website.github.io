---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Sanguine: Visual Analysis for Patient Blood Management"
# Keys must be unique to each paper, see section below for more details
key: 2020_vahc_sanguine
# Select one of the options below
type: paper 
# use this if this paper was previously a preprint and you need to preserve the old URL
# redirect_from: /publications/2017_preprint_lineag
order: 2020-10
# Auto-generates titles and alt-descriptors
shortname: Sanguine
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2020_vahc_sanguine.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2020_vahc_sanguine_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- lin
- Ryan A. Metcalf
- wilburn
- lex

# Include a shortened name for the journal or conference/proceedings
journal-short: VAHC
year: 2020

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: inproceedings
bib:
  journal:
  booktitle: Workshop on Visual Analytics in Healthcare at AMIA (VAHC)
  editor: 
  publisher:
  address: 
  doi: 
  url: 
  volume: 
  number: 
  pages:
  month: 
  pmcid: 

# Provide a link to the publisher's webpage if no DOI is available
publisherURL: https://www.visualanalyticshealthcare.org/proceedings.html

# Link to an official preprint server
preprint_server: https://arxiv.org/abs/2011.01931

# Links to a project hosted on VDL, or else externally on your own site
project: 

# Video entry and preview video
videos:
- name: "Sanguine: Visual Analysis for Patient Blood Management"
  youtube-id: DhTNyvCJgtM
  file: 2020_vahc_sanguine.mp4

# Provide a preprint and supplement pdf
pdf: 2020_vahc_sanguine.pdf

# Extra supplements, such as talk slides, data sets, etc.
#supplements:
#- name: Vials Conference Talk Slides
  # Use link instead of abslink if you want to link to the master directory
 # abslink: http://vials.io/talk/
  # Defaults to a download icon, use this if you want a link-out icon
  #linksym: true

# Link to the repository where the code is hosted
code: https://github.com/visdesignlab/Sanguine/

abstract: "
Blood transfusion is a frequently performed medical procedure in surgical and nonsurgical contexts. Although it is frequently necessary or even life-saving, it has been identified as one of the most overused procedures in hospitals. Unnecessary transfusions not only waste resources but can also be detrimental to patient outcomes. Patient blood management (PBM) is the clinical practice of optimizing transfusions and associated outcomes. In this paper, we introduce Sanguine, a visual analysis tool for transfusion data and related patient medical records. Sanguine was designed with two user groups in mind: PBM experts and clinicians who conduct transfusions. PBM experts use Sanguine to explore and analyze transfusion practices and its associated medical outcomes. They can compare individual surgeons, or compare outcomes or time periods, such as before and after an intervention regarding transfusion practices. PBM experts then curate and annotate views for communication with clinicians, with the goal of improving their transfusion practices. Such a review session could be in person or through a shared link. We validate the utility and effectiveness of Sanguine through case studies. 
"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
# Note
**This is a workshop paper which was extended [to a journal paper](../2021_ivi_sanguine). Please refer to and cite the journal paper instead.** 

# Acknowledgements
We thank Dr. Vikas Sharma, the Enterprise Data Warehouse, and the Center for High Performance Computing at the University of Utah. We gratefully acknowledge funding for this project by ARUP Laboratories. Computational resources used were partially funded by the NIH Shared Instrumentation Grant 1S10OD021644-01A1.
