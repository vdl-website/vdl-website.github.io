---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Accessible Text Descriptions for UpSet Plots"
key: 2025_eurovis_text-descriptions
# paper | preprint | poster
type: paper
order: 2025-3

#paper_content_url: 


# The shortname is used for auto-generated titles
shortname: Accessible Text Descriptions

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2025_eurovis_text-descriptions.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2025_eurovis_text-descriptions_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Andrew McNutt
- Maggie K McCracken
- Ishrat Jahan Eliza
- Daniel Hajas
- wagoner
- lanza
- wilburn
- Sarah Creem-Regehr
- lex


year: 2025
journal-short: EuroVis

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 
  url: 
  volume: 44
  number: 3
  pages: 
  month:

preprint_server: https://arxiv.org/abs/2503.17517


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use this if you have an external project website
external-project: https://upset.multinet.app/

pdf: 2025_eurovis_text-descriptions.pdf

supplement: 2025_eurovis_text-descriptions_supplement.zip

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Supplementary Material OSF
  # Use link instead of abslink if you want to link to the master directory
  abslink: https://osf.io/kbvs9/
  # Defaults to a download icon, use this if you want a link-out icon
  linksym: true
- name: UpSet Website Code
  abslink: https://github.com/visdesignlab/upset2
  linksym: true
- name: Data Analysis Code
  abslink: https://github.com/visdesignlab/UpSet-Survey-Data-Analysis
  linksym: false
- name: Survey reVISit Code
  abslink:  https://github.com/visdesignlab/Upset-alttxt-study
  linksym: false
- name: UpSet Survey
  abslink: https://vdl.sci.utah.edu/Upset-alttxt-study/Upset-Alttext-User-Survey/
  linksym: false

# # Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
  - path: 2025_eurovis_text-descriptions_longdescription.png
    caption: UpSet 2 interface with generated text description.
  - path: 2025_eurovis_text-descriptions_text.png
    caption: UpSet 2 full text description with alternative configuration.
  - path: 2025_eurovis_text-descriptions_notebook.jpg
    caption: UpsetPlot (Python) generated text descriptions.
  - path: 2025_eurovis_text-descriptions_revisit.png
    caption: A screenshot from Experiment 1 (reVISit).

# Link to the repository where the code is hostet
code: https://github.com/visdesignlab/upset-alt-txt-gen  

videos:
 - name: 'Paper Video'
   youtube-id: OhScWL1bUkQ
   file: 2025_eurovis_text-descriptions.mp4
   subtitles: 2025_eurovis_text-descriptions.srt


abstract: "
Data visualizations are typically not accessible to blind and low-vision (BLV) users. Automatically generating text descriptions offers an enticing mechanism for democratizing access to the information held in complex scientific charts, yet appropriate procedures for generating those texts remain elusive. Pursuing this issue, we study a single complex chart form: UpSet plots. UpSet Plots are a common way to analyze set data, an area largely unexplored by prior accessibility literature. By analyzing the patterns present in real-world examples, we develop a system for automatically captioning any UpSet plot. We evaluated the utility of our captions via semi-structured interviews with (N=11) BLV users and found that BLV users find them informative. In extensions, we find that sighted users can use our texts similarly to UpSet plots and that they are better than naive LLM usage.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---

# Acknowledgements

We gratefully acknowledge funding by Chan Zuckerberg Initiative Essential Open Source Software for Science program.