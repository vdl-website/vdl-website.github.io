---
layout: publication
title: "Reflections on Traceability for Visualization Research"
key: 2026_eurovis_traceability
type: paper
order: 2026-2

shortname: tRRRacer
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2026_eurovis_traceability.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2026_eurovis_traceability_teaser.png
# Add alt text for the teaser image, which is important for accessibility. If not provided, it will default to "{{ page.shortname }} screenshot. The alt text is used for the large image by default, but if a large image is not present, it's also used for the small image."
image_alt_text: "Screenshot of the tRRRacer interface with a research thread highlighted." 

# Authors in the "database" can be used with just their person "key"
authors:
- rogers
- akbaba
- James Scott-Brown
- lex
- meyer

journal-short: EuroVis
year: 2026

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis)
  doi: 10.1111/cgf.70445
  volume: 45
  number: 3

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
# award:

# Provide a link to the publisher's webpage if no DOI is available
# publisherURL: 

# Link to an official preprint server
preprint_server: https://arxiv.org/abs/2604.14417

# Links to a project hosted on VDL, or else externally on your own site
# project: 
external-project: https://trrracer.netlify.app/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.
# videos:  
# - name: "Juniper Introduction" 
#   youtube-id: EAjNxFgsJ58
#   file: 2018_infovis_juniper.mp4

# Provide a preprint and supplement pdf
pdf: 2026_eurovis_traceability.pdf
#supplement: 

# Extra supplements, such as talk slides, data sets, etc.
# supplements:
# - name: Supplementary Material OSF
#   # Use link instead of abslink if you want to link to the master directory
#   abslink: https://osf.io/2nrbc
#   # Defaults to a download icon, use this if you want a link-out icon
#   linksym: true

# Supplemental, cc-by images. Make caption brief (at most 60 chars).
#images:
#- path: 2026_eurovis_evaluating_bvnv_encodings.png
#  caption: Adjacency matrices showing the four tested encodings. 
#- path: 2026_eurovis_evaluating_bvnv_study.png
#  caption: Study interface for an example Adjacency by Attribute Combination task.

# Link to the repository where the code is hosted
code: https://github.com/visdesignlab/trrracer

abstract: 
 "Decades of advocacy for reproducibility and replication have advanced open, transparent practices in the sciences. However, traditional notions of reproducibility fit poorly with design-oriented visualization research, where insights emerge through subjective, situated, and iterative work. So how can we ensure rigor and transparency in processes that are inherently unreproducible? To introduce transparency in design-oriented research, we propose to focus on traceability: surfacing the origin and development of research contributions based on rich sets of artifacts documenting the design process. We investigated traceability through a collaborative autoethnographic reflection that builds on several years of work exploring ways to make design-oriented research transparent. This exploration includes an experiment to build a tool to support traceability, which we called tRRRacer. The tRRRacer tool provided a testbed for us to operationalize the three tenets of a traceable process: (1) Record abundant, annotated artifacts representative of research activities; (2) Report curated research threads that articulate rationale and evolution of the process, allowing others to (3) Read via interfaces that help retrace claims and assess plausibility. Reflecting on our experiences, we contribute a theorization of traceability and reflections on how we might support it."

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
# The --- is REQUIRED! 
---

# Acknowledgements

This work is funded in part by the Swedish Research Council (Grant No. 2024-05726); by the Wallenberg AI, Autonomous Systems and Software Program (WASP) funded by the Knut and Alice
Wallenberg Foundation; and the U.S. National Science Foundation (NSF OAC 1835904).
