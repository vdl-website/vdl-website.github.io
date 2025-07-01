---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Lineage: Visualizing Multivariate Clinical Data in Genealogy Graphs"
key: 2018_tvcg_lineage
# paper | preprint | poster
type: paper
order: 2019-01
redirect_from: /publications/2017_preprint_lineage

# The shortname is used for auto-generated titels
shortname: Lineage
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- nobre
- gehlenborg
- Hilary Coon
- lex

journal-short: TVCG
year: 2019

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics
  booktitle: 
  editor: 
  publisher: IEEE
  address: 
  doi: 10.1109/TVCG.2018.2811488
  url: 
  volume: 25
  number: 3
  pages: 1543-1558
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project: https://lineage.caleydoapp.org

# The reference to the video entry
video: 2018_tvcg_lineage_video
# Talk video
talk-video: 2018_tvcg_lineage_talk

# The reference to the preview video entry
preview-video: 2018_tvcg_lineage_video_preview

# the preprint
pdf: 2018_tvcg_lineage.pdf
# A supplement PDF
supplement: 2018_tvcg_lineage_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Vis Talk Slides
  link: 2018_tvcg_lineage_talkSlides.pdf

#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2018_tvcg_lineage_clean.png
  caption: Single family in hidden mode with one expanded nuclear family. 
- path: 2018_tvcg_lineage_multiple_families.png
  caption: Two families, sorted by PD.
- path: 2018_tvcg_lineage_select_person.png
  caption: Single family showing person selection and highlight. 
- path: 2018_tvcg_lineage_sort_age.png
  caption: Single family, sorted by age.
- path: 2018_tvcg_lineage_star_attribute.png
  caption: Two families, with PD as a starred attribute.


# Link to the repository where the code is hostet
code: https://github.com/Caleydo/lineage

# Link to an official preprint server
preprint_server: https://doi.org/10.1101/128579

abstract: "
The majority of diseases that are a significant challenge for public and individual heath are caused by a combination of hereditary and environmental factors. In this paper we introduce Lineage, a novel visual analysis tool designed to support domain experts who study such multifactorial diseases in the context of genealogies. Incorporating familial relationships between cases with other data can provide insights into shared genomic variants and shared environmental exposures that may be implicated in such diseases. We introduce a data and task abstraction, and argue that the problem of analyzing such diseases based on genealogical, clinical, and genetic data can be mapped to a multivariate graph visualization problem. The main contribution of our design study is a novel visual representation for tree-like, multivariate graphs, which we apply to genealogies and clinical data about the individuals in these families. We introduce data-driven aggregation methods to scale to multiple families. By designing the genealogy graph layout to align with a tabular view, we are able to incorporate extensive, multivariate attributes in the analysis of the genealogy without cluttering the graph. We validate our designs by conducting case studies with our domain collaborators."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


# Acknowledgements

We thank Asmaa Aljuhani and Annie Cherkaev for their contributions. We also thank our collaborators and the Visualization Design Lab at the University of Utah for the feedback, and the Caleydo team for their technical support. 
This work was supported in part by the US National Institutes of Health (U01 CA198935, R00 HG007583, R01MH099134) and the DoD -- Office of Economic Adjustment (OEA), ST1605-16-01. We thank the Pedigree and Population Resource of the Huntsman Cancer Institute, University of Utah (funded in part by the Huntsman Cancer Foundation) for its role in the ongoing collection, maintenance, and support of the Utah Population Database (UPDB).  We also acknowledge support for the UPDB through grant P30 CA2014 from the National Cancer Institute, and from the University of Utah’s Program in Personalized Health and Center for Clinical and Translational Science.
