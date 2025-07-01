---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Loops: Leveraging Provenance and Visualization to Support Exploratory Data Analysis in Notebooks"
key: 2024_vis_loops
# paper | preprint | poster
type: paper
order: 2024-3

#paper_content_url: 


# The shortname is used for auto-generated titels
shortname: Loops

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2024_vis_loops_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2024_vis_loops.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Klaus Eckelt
- kiran
- lex
- streit

year: 2024
journal-short: IEEE VIS

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (VIS)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi:  10.31219/osf.io/79eyn 
  url: 
  volume: 
  number: 
  pages: 
  month:

preprint: https://osf.io/79eyn/ # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use this if you have an external project website
external-project: https://mybinder.org/v2/gh/jku-vds-lab/loops/main?labpath=notebooks

pdf: 2024_vis_loops.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Supplemental Material
  # Use link instead of abslink if you want to link to the master directory
  abslink: https://osf.io/hxuak/
  # Defaults to a download icon, use this if you want a link-out icon
  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/loops

videos:
 - name: 'Paper Video'
   youtube-id: jCUwLm5wfNo
   file: 2024_vis_loops.mp4
 - name: 'Preview Video'
   file: 2024_vis_loops_preview.mp4


abstract: "
Exploratory data science is an iterative process of obtaining, cleaning, profiling, analyzing, and interpreting data. This cyclical way of working creates challenges within the linear structure of computational notebooks, leading to issues with code quality, recall, and reproducibility. To remedy this, we present Loops, a set of visual support techniques for iterative and exploratory data analysis in computational notebooks. Loops leverages provenance information to visualize the impact of changes made within a notebook. In visualizations of the notebook provenance, we trace the evolution of the notebook over time and highlight differences between versions. Loops visualizes the provenance of code, markdown, tables, visualizations, and images and their respective differences. Analysts can explore these differences in detail in a separate view. Loops not only makes the analysis process transparent but also supports analysts in their data science work by showing the effects of changes and facilitating comparison of multiple versions. We demonstrate our approach's utility and potential impact in two use cases and feedback from notebook users from various backgrounds.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---