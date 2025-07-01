---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Composer: Visual Cohort Analysis of Patient Outcomes"
key: 2018_infovis_composer
# paper | preprint | poster
type: poster
redirect_from: /publications/2018_infovis_composer

# The shortname is used for auto-generated titels
shortname: Composer Poster
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_vahc_composer.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_vahc_composer_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- rogers
- Nicholas Spina
- Ashley Neese
- Rachel Hess
- Darrel Brodke
- lex

year: 2018

bibentry: inproceedings
bib:
  journal: Proceedings of the IEEE Information Visualization Conference - Posters 
  booktitle:
  editor:
  publisher: 
  address:
  doi:
  url:
  volume:
  number:
  pages:
  month:

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website

# The reference to the video entry
video: 2018_infovis_composer_video.mp4
# The reference to the preview viedo entry
#preview-video:

# the prerint
pdf: 2018_infovis_composer_abstract.pdf
# A supplement PDF
#supplement: 2017_preprint_lineage_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Poster
  link: 2018_infovis_composer_poster.pdf
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/visdesignlab/Composer/


abstract: "
<p>
Lower back pain is a significant health burden, claiming 2.6 million emergency room visits a year with expenses exeeding $100 billion. 
To determine the best treatment options for their patients, doctors often rely on clinical guidelines and memory of past experience with patients that have similar medical histories to a given patient. However, Most clinical guidelines are based on evidence from clinical trials and controlled studies and data collected from clinical trials, often sourced from a general population, may not provide an accurate reflection of potential outcomes for patients with pre-existing conditions. </p>
<p>
There has been a rising interest in using EHR data in evidence based comparisons to better identify factors that can influence patients recovery, especially for those with pre-existing conditions. This was the motivation behind our collaboration with surgeons and researchers from the orthopaedic research center and population health, who are currently investigating the use of patient reported outcomes called PROMIS scores 
as a measure of patient well-being and progression of physical function following various procedures for spinal ailments.</p>
<p>
To help with this, we developed Composer, a visual cohort analysis tool to compare change in physical function following diverse treatments, such as surgery, physical therapy, or injections.
</p>
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
# Acknowledgements
We thank Sahar Mehrpour for initial data analysis and implementation. This project is funded by the Orthopaedic Research Center and NSF IIS 1751238.