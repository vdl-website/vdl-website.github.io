---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Evaluating Encodings for Bivariate Edges in Adjacency Matrices"
# Keys must be unique to each paper, see section below for more details
key: 2026_eurovis_evaluating-bvnv
# Select one of the options below
type: paper
# use this if this paper was previously a preprint and you need to preserve the old URL
# redirect_from: /publications/2017_preprint_lineage
# Uncomment the line below for publications which should only appear on a personal webpage
# personal: y

# Papers are ordered by year. However, in years with many papers, we want some ordering at a lower level. You can do 
# that by specifying an order for the papers of that year. For example, 2019-11 will put papers with values lower than 
# 2019-11 below that paper. Notice that sorting is lexicographic.  
order: 2026-3

# Auto-generates titles and alt-descriptors
shortname: Evaluating Bivariate
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2026_eurovis_evaluating-bvnv.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2026_eurovis_evaluating-bvnv_teaser.png
# Add alt text for the teaser image, which is important for accessibility. If not provided, it will default to "{{ page.shortname }} screenshot. The alt text is used for the large image by default, but if a large image is not present, it's also used for the small image."
image_alt_text: "Study interface for an example Adjacency by Attribute Combination task." 

# Authors in the "database" can be used with just their person "key"
authors:
- jacosta
- lex
- he

# A link to an internal blog post (use only the relative URL)
# blog-post:

# Include a shortened name for the journal or conference/proceedings. 
# Generally go for the colloquial name here, so InfoVis, VIS, EuroVis, VAST, CHI, TVCG. 
# Don't bother with publication format (CGF for EuroVis or TVCG for VIS papers).
# Don't mention organizations (IEEE, ACM), so VIS, not IEEE VIS, CHI, not ACM CHI.  
# Do include relevant qualifiers, such as "Short Papers" (VIS Short Papers) or "Posters" (VIS Posters)
# Don't include a year, or a shorthand for the year, so NOT: InfoVis'14
journal-short: EuroVis
year: 2026

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis)
  doi: 10.1111/cgf.70475
  volume: 45
  number: 3

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
# award:

# Provide a link to the publisher's webpage if no DOI is available
# publisherURL: 

# Link to an official preprint server
preprint_server: https://zenodo.org/records/19550960

# Links to a project hosted on VDL, or else externally on your own site
# project: 
external-project: https://jorgeacostaupm.github.io/revisit/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.
# videos:  
# - name: "Juniper Introduction" 
#   youtube-id: EAjNxFgsJ58
#   file: 2018_infovis_juniper.mp4

# Provide a preprint and supplement pdf
pdf: 2026_eurovis_evaluating-bvnv.pdf
supplement: 2026_eurovis_evaluating-bvnv_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Supplementary Material OSF
  # Use link instead of abslink if you want to link to the master directory
  abslink: https://osf.io/2nrbc
  # Defaults to a download icon, use this if you want a link-out icon
  linksym: true

# Supplemental, cc-by images. Make caption brief (at most 60 chars).
#images:
#- path: 2026_eurovis_evaluating_bvnv_encodings.png
#  caption: Adjacency matrices showing the four tested encodings. 
#- path: 2026_eurovis_evaluating_bvnv_study.png
#  caption: Study interface for an example Adjacency by Attribute Combination task.

# Link to the repository where the code is hosted
code: https://github.com/jorgeacostaupm/revisit

abstract: 
 "We present the first empirical evaluation of techniques for encoding distributions of quantitative edge values within adjacency matrices. In many real-world networks, edges represent not a single value but a set of measurements. While adjacency matrices preserve structural clarity, their compact cells limit the simultaneous display of multiple values. To address this, we explore edge encodings that represent distributions by two values: a measure of central tendency (mean, median, mode) and a measure of dispersion (standard deviation, variance, IQR). We select four possible encodings for evaluation that prior work has suggested are suitable for the limited space available in matrices: a bivariate color palette, embedded bar charts, and two overlaid-mark designs mapping the primary attribute to color and the secondary attribute to area or angle. In a preregistered crowdsourced study with 156 participants, we assessed performance of these encodings across eight analytical tasks and collected readability and aesthetic ratings. Results reveal clear performance regimes: area-based overlaid marks and bar charts achieved the highest overall performance; angle-based marks show moderate but less stable performance, and bivariate color consistently underperforms these alternatives. These findings clarify how visual channels behave under strict constraints and delineate the strengths and limitations of key design choices for multivariate edge visualization."

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
# The --- is REQUIRED! 
---

# Acknowledgements

We gratefully acknowledge funding by the Programa Propio de Investigación,Innovación y Doctorado of the Universidad Politécnica de Madrid (UPM) and the National Science Foundation (CNS 2213756).
