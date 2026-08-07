---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Using Tactile Charts to Support Comprehension and Learning of Complex Visualizations for Blind and Low-Vision Individuals"
key: 2026_vis_tactile-llm
# paper | preprint | poster
type: paper
order: 2026-6

#paper_content_url: 


# The shortname is used for auto-generated titles
shortname: Tactile Charts

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2026_vis_tactile-llm.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2026_vis_tactile-llm_teaser.png
image_alt_text: "A three-panel overview of the modalities used during chart-type learning. The left panel shows a screenshot of a web page titled ``Violin Plot Tactile Chart Exploration Instructions,'' organized into steps for orienting to the chart, introducing violin plots, and exploring the tactile model. The middle panel shows an overhead photograph of a 3D-printed tactile violin plot. The right panel shows a screenshot of an LLM chat from an actual participant session. The participant asks whether the upper peaks for Adelie and Chinstrap penguins have the same value and asks for the highest and lowest values for Gentoo; the assistant responds with numerical values and brief explanations."


# external-project: 
# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
  - he
  - Maggie McCracken
  - Daniel Hajas
  - Sarah Creem-Regehr
  - lex


year: 2026
journal-short: IEEE VIS

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (VIS)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 
  url: 
  volume: 
  number: 
  pages: 
  month: jan

preprint_server: https://arxiv.org/abs/2607.23065


# videos:
#  - name: 'Conference Presentation'
#    youtube-id: 
#    file: 
#    subtitles: 



# blog-post: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:


pdf: 2026_vis_tactile-llm.pdf

supplement: 2026_vis_tactile-llm_supplement.zip

# Extra supplements, such as talk slides, data sets, etc.
# supplements:
# - name: 
#   # Use link instead of abslink if you want to link to the master directory
#   abslink: 
#   # Defaults to a download icon, use this if you want a link-out icon
#   linksym: true


# images:
#   - path: 
#     caption: 



code: https://github.com/visdesignlab/tactile-and-LLM-revisit

abstract: "
Visualizations are central to communicating data, yet blind and low-vision (BLV) people often lack support for understanding chart types---knowledge that is essential for interpreting new visualizations and collaborating with sighted peers. Prior work found that BLV individuals viewed example tactile charts as more helpful than text-only approaches and preferred them for learning advanced chart types, particularly for understanding spatial layouts and shapes. Meanwhile, large language models (LLMs) are increasingly used by BLV individuals for chart explanation and question answering (QA), but have been studied primarily for dataset exploration rather than chart-type learning. Existing LLM-based chart QA also shows that users frequently ask about layout and structure, yet struggle with spatial concepts and misdirect questions when mental models are weak. We investigate how LLMs influence chart-type learning and whether tactile learning improves subsequent LLM-supported exploration. We extend our tactile chart learning tools with an LLM chatbot that provides interactive explanations and supports follow-up questions. In an interview study with 12 BLV participants, we compare two learning formats: (1) a tactile chart, a textual explanation, and an LLM chatbot; and (2) a textual explanation and an LLM chatbot. The learning phase was followed by exploration of an unfamiliar dataset using alt text and an LLM. Thematic analysis shows that tactile templates support BLV participants' formation of chart-type mental models, which scaffolds subsequent LLM-mediated data exploration. Text+LLM explanations without tactile support show weaknesses for spatial-reasoning tasks.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---

# Acknowledgements

The authors thank Aaron Delahunta and Sofia Djunic for correcting interview transcripts.