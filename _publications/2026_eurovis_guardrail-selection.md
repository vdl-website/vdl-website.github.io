---
layout: publication
title: "Guardrail Selection in Line Charts to Contextualize Persuasive Visualizations"
key: 2026_eurovis_guardrail-selection
type: paper
order: 2026-5

shortname: Guardrail Selection
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2026_eurovis_guardrail-selection.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2026_eurovis_guardrail-selection_teaser.png
# Add alt text for the teaser image, which is important for accessibility. If not provided, it will default to "{{ page.shortname }} screenshot. The alt text is used for the large image by default, but if a large image is not present, it's also used for the small image."
image_alt_text: A concept figure about methods to select items for guardrails in like charts, and an example of a guardrail for stocks data.
# Authors in the "database" can be used with just their person "key"
authors:
- abrar
- Marina Kogan
- lex
- lisnic

journal-short: EuroVis
year: 2026

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis)
  doi: 10.1111/cgf.70460
  volume: 45
  number: 3

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
# award:

# Provide a link to the publisher's webpage if no DOI is available
# publisherURL: 

# Link to an official preprint server
preprint_server: 

# Links to a project hosted on VDL, or else externally on your own site
# project: 
external-project: https://vdl.sci.utah.edu/guardrail-samples-study/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.
# videos:  
# - name: "Juniper Introduction" 
#   youtube-id: EAjNxFgsJ58
#   file: 2018_infovis_juniper.mp4

# Provide a preprint and supplement pdf
pdf: 2026_eurovis_guardrail-selection.pdf
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
code: https://github.com/visdesignlab/guardrail-samples-study

abstract: 
 "Charts used for persuasion can easily veer into being outright misleading when, for instance, cherry-picked data is paired with a deceptive caption, as is commonly encountered on social media. The rise of interactive time-series data explorers for hotly debated topics makes such framing easy to produce and spread. Post-hoc interventions like fact-checking often arrive too late and suffer from persistence of belief. Prior work suggests that guardrails, in the form of contextual comparison lines embedded directly into charts, can reduce these effects. We propose and evaluate a practical set of guardrail sampling strategies for implementing such contextual lines in real systems. In a preregistered mixed-design study with two real-world scenarios (COVID-19 and Stocks), participants viewed persuasive charts with different sets of guardrails and reported trust, estimated rank in the dataset, expressed their perceived completeness of context, as well as subjective preference for different tasks. Across scenarios, guardrails improved trust, accuracy of performance judgments, and perceived completeness of context compared to the control. Taken together, the study offers practical guardrail sampling methods, evidence of their contextual benefits, and insights into participants' preferences."

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
# The --- is REQUIRED! 
---

# Acknowledgements

This work is supported by the National Science Foundation (CNS 2213756).