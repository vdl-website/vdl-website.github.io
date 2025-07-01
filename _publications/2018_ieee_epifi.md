---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "EpiFi: An In-Home Sensor Network Architecture for Epidemiological Studies"
# Keys must be unique to each paper, see section below for more details
key: 2018_ieee_epifi
# Select one of the options below
type: paper 
# Uncomment the line below for publications which should only appear on a personal webpage
# personal: y
order: 2018-06

# Auto-generates titles and alt-descriptors
shortname: 2018_ieee_epifi
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2018_ieee_epifi.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2018_ieee_epifi_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- Philip Lundrigan
- Kyeong T. Min
- Neal Patwari
- Sneha Kasera
- Kerry Kelly
- moore
- meyer
- Scott C. Collingwood
- Flory Nkoy
- Bryan Stone
- Katherine Sward


# Include a shortened name for the journal or conference/proceedings
journal-short: IEEE
year: 2018

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: article 
bib:
  
  journal: 2018 IEEE 43rd Conference on Local Computer Networks Workshops (LCN Workshops)
  issue_date:  2018
  numpages: 8
  publisher: IEEE
  address: 
  doi: 10.1109/lcnw.2018.8628482
  url: 
  volume: 2
  number: 3
  pages: 30-37
  month: Sept

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
pdf: 2018_ieee_epifi.pdf
#supplement: 2018_imwut_maav_supplement.zip

# Extra supplements, such as talk slides, data sets, etc.
#supplements: 
#name: Presentation Slides
#link: 2018_imwut_maav_slides.pdf
# Use link instead of abslink if you want to link to the master directory
# link: 2018_imwut_maav_supplement.zip
# Defaults to a download icon, use this if you want a link-out icon
# linksym: true

# Link to the repository where the code is hosted
# code: 

abstract: "<p>
We design and build EpiFi, a novel architecture for in-home sensor networks which allows epidemiologists to easily design and deploy exposure sensing systems in homes. We work collaboratively with pediatric asthma researchers to design multiple studies and deploy EpiFi in homes. Here, we report on experiences from two years of deployments in 15 homes, of two different types of studies, including many deployments continuously monitored over the past year. Based on lessons learned from these deployments and researchers, we develop a new mechanism for sensors to bootstrap their connectivity to a subject's home WiFi router and implement data reliability mechanisms to minimize loss in the network through a long-term deplovment
</p>"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements
Research reported in this publication was supported by NIBIB of the US NIH under award number 1U54EB021973-01. 
