---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Juniper: A Tree+Table Approach to Multivariate Graph Visualization"
# Keys must be unique to each paper, see section below for more details
key: 2018_infovis_juniper
# Select one of the options below
type: paper 
order: 2019-04
# Uncomment the line below for publications which should only appear on a personal webpage
# personal: y
redirect_from: /publications/2018_preprint_juniper

# Auto-generates titles and alt-descriptors
shortname: Juniper
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2018_infovis_juniper.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2018_infovis_juniper_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- nobre
- streit
- lex

# Include a shortened name for the journal or conference/proceedings
journal-short: InfoVis
year: 2019

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (InfoVis)
  booktitle: 
  editor: 
  publisher: IEEE
  address: 
  doi:  10.1109/TVCG.2018.2865149
  url: 
  volume: 25
  number: 1
  pages: 544-554



# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: 

# Provide a link to the publisher's webpage if no DOI is available
publisherURL: 

# Link to an official preprint server
preprint_server: https://arxiv.org/abs/1804.03261

# Links to a project hosted on VDL, or else externally on your own site
project: 
external-project: http://juniper.sci.utah.edu/

# The videos, list name, youtube-id, vimeo-id, file (the filename)
videos:  
 - name: "Juniper Introduction" 
   youtube-id: EAjNxFgsJ58
   file: 2018_infovis_juniper.mp4
 - name: "Juniper Preview" 
   youtube-id: y9ZVNtuyUBU
   file: 2018_infovis_juniper_preview.mp4
 - name: "Recorded Talk" 
   vimeo-id: 299855433
   file: 2018_infovis_juniper_talk.mp4
 
# the preprint
pdf: 2018_infovis_juniper.pdf
# A supplement PDF
#supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Vis Talk Slides
  link: 2018_infovis_juniper_talkSlides.pdf
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true


# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2018_infovis_juniper_add_edge.png
  caption: Adding a hidden edge to the tree. 
- path: 2018_infovis_juniper_shortest_path.png
  caption: Shortest path between two nodes.
- path: 2018_infovis_juniper_aggregate.png
  caption: Aggregated tree in tree mode.
- path: 2018_infovis_juniper_aggregate_level_mode.png
  caption: Aggregated tree in level mode. 
- path: 2018_infovis_juniper_hidden_edges.png
  caption: Showing hidden edges on hover.
- path: 2018_infovis_juniper_level_mode.png
  caption: Tree in level mode.


# Link to the repository where the code is hosted
code: https://github.com/caleydo/lineage/tree/juniper
 

abstract: "
Analyzing large, multivariate graphs is an important problem in many domains, yet such graphs are challenging to visualize. In this paper, we introduce a novel, scalable, tree+table multivariate graph visualization technique, which makes many tasks related to multivariate graph analysis easier to achieve. The core principle we follow is to selectively query for nodes or subgraphs of interest and visualize these subgraphs as a spanning tree of the graph. The tree is laid out linearly, which enables us to juxtapose the nodes with a table visualization where diverse attributes can be shown. We also use this table as an adjacency matrix, so that the resulting technique is a hybrid node-link/adjacency matrix technique. We implement this concept in Juniper and complement it with a set of interaction techniques that enable analysts to dynamically grow, restructure, and aggregate the tree, as well as change the layout or show paths between nodes. We demonstrate the utility of our tool in usage scenarios for different multivariate networks: a bipartite network of scholars, papers, and citation metrics and a  multitype network of story characters, places, books, etc."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


# Acknowledgements

The authors wish to thank members of the Visualization Design Lab
for their feedback, and acknowledge support by NIH (U01 CA198935),
NSF (IIS 1751238), DoD (ST1605-16-01), and the Austrian Science
Fund (FWF P27975-NBL).
