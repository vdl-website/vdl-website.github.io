---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Indoor Household Particulate Matter Measurements Using a Network of Low-cost Sensors"
# Keys must be unique to each paper, see section below for more details
key: 2020_aaqr_pm
# Select one of the options below
type: paper 


# Papers are ordered by year. However, in years with many papers, we want some ordering at a lower level. You can do 
# that by specifying an order for the papers of that year. For example, 2019-11 will put papers with values lower than 
# 2019-11 belwo that paper. Notice that sorting is lexicographic.  
order: 2020-02

# Auto-generates titles and alt-descriptors
shortname: sensors
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2020_aaqr_pm.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2020_aaqr_pm_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- Shruti Hegde
- Kyeong T. Min
- moore
- Philip Lundrigan
- Neal Patwari
- Scott Collingwood
- Alfred Bach
- Kerry E. Kelly

# A link to an internal blog post (use only the relative URL)
blog-post: 

# Include a shortened name for the journal or conference/proceedings
journal-short: AAQR
year: 2020

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: article 
bib:
  journal: Aerosol Air Quality Research
  publisher: Taiwan Association for Aerosol Research
  doi: 10.4209/aaqr.2019.01.0046
  volume: 20
  number: 2
  pages: 381--394



# Provide a preprint and supplement pdf
pdf: 2020_aaqr_pm.pdf
supplement: 2020_aaqr_pm_supplement.pdf




abstract: "<p>
The World Health Organization estimates that 4.3 million deaths globally in 2012 were attributable to household air pollution, of which particulate matter (PM) with a diameter of 2.5 µm or less (PM2.5) is a significant contributor. When integrated with
a wireless network, low-cost PM measurements potentially provide personalized information on indoor concentrations in real time so that individuals can take action. The objectives of this study were to (1) deploy a network of research-grade instruments and low-cost sensors in a home environment and evaluate the performance, (2) characterize activities and conditions that increase PM concentrations, and (3) identify how these activities affect the PM levels in different rooms of a home. The wireless sensor network included low-cost PM sensors, a gateway, and a database for storing data. Based on the commercially available Dylos DC1100 Pro (Utah Modified Dylos Sensor) and Plantower PMS sensor (AirU), the low-cost sensors were compared to three research-grade instruments—the GRIMM, DustTrak, and MiniVol—in two households in Salt Lake City during summer and winter, with the results suggesting that the low-cost sensors agreed well with the DustTrak. Of the activities, frying food and spraying aerosol products generated the largest increase in PM, both in the room of the activity (the kitchen and bedroom, respectively) and the adjacent rooms. High outdoor PM concentrations during a cold air pool episode also caused indoor levels to rise. In addition, different PM sources triggered different sensor responses. Consequently, obtaining accurate estimates of the mass concentration in an indoor environment, with its wide variety of PM sources, is challenging. However, low-cost PM sensors can be incorporated into an indoor air-quality measurement network
to help individuals manage their personal exposure. 
</p>"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
# The --- is REQUIRED! 
---

# Acknowledgements

We gratefully acknowledge support by NIH Grant Number U54EB021973, Prisms Informatics Platform Federated Integration Architecture and the ECHO Program, National Institutes of Health under Award Number UH3OD023249. 
