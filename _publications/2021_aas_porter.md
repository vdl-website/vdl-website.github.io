---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "I'll Have the Porter: Interactively Visualizaing the Results of Statistical Maneuver Analysis"
# Keys must be unique to each paper, see section below for more details
key: 2021_aas_porter
# Select one of the options below
type: paper 
order: 2021-01

# Auto-generates titles and alt-descriptors
shortname: porter
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2021_aas_porter.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2021_aas_porter_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- Rohan Patel
- moore
- Jeffery Stuart
- Sonia Hernandez
- Basak Alper Ramaswamy

# Include a shortened name for the journal or conference/proceedings
journal-short: AAS
year: 2021

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: article 
bib:
  
  journal: The Journal of the Astronautical Sciences
  issue_date: 2021
  numpages: 20
  publisher: American Astronautical Society
  address: 
  doi: 
  url: https://www.space-flight.org/
  volume: 
  number: 
  pages: 20
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
# award: EuroVis 2016 Honorable Mention Award

# Provide a link to the publisher's webpage if no DOI is available


# Link to an official preprint server
# preprint_server: 

# Links to a project hosted on VDL, or else externally on your own site
project: 
# external-project: https://pathfinder.caleydoapp.org/

# Video entry and preview video
# video: 2016_eurovis_pathfinder_video
# preview-video: 2016_eurovis_pathfinder_video_preview

# Provide a preprint and supplement pdf
pdf: 2021_aas_porter.pdf
#supplement: 2018_imwut_maav_supplement.zip

# Extra supplements, such as talk slides, data sets, etc.
supplements: 
#name: Presentation Slides
#link: 
# Use link instead of abslink if you want to link to the master directory
# link:
# Defaults to a download icon, use this if you want a link-out icon
# linksym: true

# Link to the repository where the code is hosted
# code: 

abstract: "<p>
Mission design and navigation relies on statistical maneuver analysis and Monte Carlo simulations when evaluating candidate mission trajectories. Engineers must
analyze large quantities of data to optimize mission safety and propellant margins, but currently rely on static text files and dense PDF slide decks to review
simulation results. This approach is time-intensive, non-interactive, and difficult to share or coordinate with other mission designers. To improve this process, we present Porter: a web-based interactive mission analysis tool. This work describes 
Porter’s user-centered design process, its processing pipeline for importing and processing LAMBIC simulation data, core interactive features, and preliminary user feedback.
</p>"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements
The authors would like to thank members of JPL’s MDNav section for their participation in the
workshop, interviews, and their feedback through the development of Porter. This research was
carried out at the Jet Propulsion Laboratory, California Institute of Technology, under a contract
with the National Aeronautics and Space Administration. Government sponsorship acknowledged.
Copyright 2021 California Institute of Technology.
