---
layout: publication
title: "Evaluating Multivariate Network Visualization Techniques Using a Validated Design and Crowdsourcing Approach"
key: 2020_chi_mvnv_study
type: paper
order: 2020-01

shortname: MVNV-study
image: 2020_chi_mvnv_study.png
image_large: 2020_chi_mvnv_study_teaser.png

authors:
- nobre
- wootton
- Lane Harrison
- lex

journal-short: CHI
year: 2020

bibentry: inproceedings
bib:
  booktitle: "SIGCHI Conference on Human Factors in Computing Systems (CHI)"
  publisher: ACM
  doi: 10.1145/3313831.3376381
  pages: 1-12
  award:

blog-post: 2020/07/23/crowdsourced-evaluation/  

# Links to a project hosted on VDL, or else externally on your own site

project:
external-project: https://vdl.sci.utah.edu/mvnv-study/
# external-project: https://vdl.sci.utah.edu/mvnv-study-analysis/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
- name: "MVNV Study Introduction"
  youtube-id: TFDNjlt8NIY
  file: 2020_chi_mvnv_study.mp4
- name: "MVNV Study Preview" 
  youtube-id: NtlEgVU_Yp0
  file: 2020_chi_mvnv_study_preview.mp4
- name: "CHI Presentation"
  youtube-id: hcXZC-V3iWY
  file: 2020_chi_mvnv_study_presentation.mp4


# Provide a preprint and supplement pdf

pdf: 2020_chi_mvnv_study.pdf
supplement: 2020_chi_mvnv_study_supplement.zip

# Link to an official preprint server
preprint_server: https://osf.io/9ndb3/

# # Extra supplements, such as talk slides, data sets, etc.

# supplements:
# - name: 
# - link: 

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2020_chi_mvnv_study_am_large_continent_sort.png
  caption: Adjacency matrix, sorted by continent. 
- path: 2020_chi_mvnv_study_am_large_edge_encodings.png
  caption: Adjacency matrix showing categorical and numerical edge attributes.
- path: 2020_chi_mvnv_study_am_small_node_neighbor_highlight.png
  caption: Small adjacency matrix showing neighbor highlighting. 
- path: 2020_chi_mvnv_study_nl_large_color.png
  caption: Node-link diagram using size and color to encode attributes.
- path: 2020_chi_mvnv_study_nl_large_nested_bars.png
  caption: Node-link diagram using nested bars and glyphs to encode attributes.
- path: 2020_chi_mvnv_study_nl_large_nested_bars_neighbor_highlight.png
  caption: Neighborhood highligthing in node-link diagram.
- path: 2020_chi_mvnv_study_nl_small_nested_bars.png
  caption: Small node-link diagram with nested bars.
- path: 2020_chi_mvnv_study_nl_link_attributes.png
  caption: Node-link diagram with quantitative and categorical edge attributes

code: https://github.com/visdesignlab/mvnv-study/
# code: https://github.com/visdesignlab/mvnv-analysis/

abstract: "
<p>Visualizing multivariate networks is challenging because of the trade-offs necessary for effectively encoding network topology and encoding the attributes associated with nodes and edges. A large number of multivariate network visualization techniques exist, yet there is little empirical guidance on their respective strengths and weaknesses. In this paper, we describe a crowdsourced experiment, comparing node-link diagrams with on-node encoding and adjacency matrices with juxtaposed tables. We find that node-link diagrams are best suited for tasks that require close integration between the network topology and a few attributes. Adjacency matrices perform well for tasks related to clusters and when many attributes need to be considered. We also reflect on our method of using validated designs for empirically evaluating complex, interactive visualizations in a crowdsourced setting. We highlight the importance of training, compensation, and provenance tracking.</p>"

---

# Acknowledgements

We thank John Guerra-Gomez for providing the data and the experts who gave feedback on our visualization designs. This work was funded by NSF 1835904 and 1815587.
