---
layout: publication
title: "Crowdsourced Think-Aloud Studies"
key: 2025_chi_crowdaloud
type: paper
order: 2025-1


shortname: CrowdaAloud
image: 2025_chi_crowdaloud.png
image_large: 2025_chi_crowdaloud_teaser.png

authors:
  - zcutler
  - Lane Harrison
  - nobre
  - lex

journal-short: CHI
year: 2025

bibentry: inproceedings
bib:
  booktitle: "SIGCHI Conference on Human Factors in Computing Systems (CHI)"
  publisher: ACM
  doi: 10.1145/3706598.3714305
  pages: 1-23

# Links to a project hosted on VDL, or else externally on your own site

project: 
external-project: https://vdl.sci.utah.edu/ThinkAloud/

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
 - name: 'CrowdAloud Introduction'
   youtube-id: H2LD-S7JtmU
   file: 2025_chi_crowdaloud.mp4
   subtitles: 2025_chi_crowdaloud.srt


# Provide a preprint and supplement pdf

pdf: 2025_chi_crowdaloud.pdf
supplement: 2025_chi_crowdaloud_supplement.zip

# Link to an official preprint server
preprint_server: https://osf.io/preprints/osf/8jb7e_v1

# # Extra supplements, such as talk slides, data sets, etc.


code: https://github.com/visdesignlab/ThinkAloud

abstract: "
<p>
The think-aloud (TA) protocol is a useful method for evaluating user interfaces, including data visualizations. However, TA studies are time-consuming to conduct and hence often have a small number of participants. Crowdsourcing TA studies would help alleviate these problems, but the technical overhead and the unknown quality of results have restricted TA to synchronous studies. To address this gap we introduce CrowdAloud, a system for creating and analyzing asynchronous, crowdsourced TA studies. CrowdAloud captures audio and provenance (log) data as participants interact with a stimulus. Participant audio is automatically transcribed and visualized together with events data and a full recreation of the state of the stimulus as seen by participants. To gauge the value of crowdsourced TA studies, we conducted two experiments: one to compare lab-based and crowdsourced TA studies, and one to compare crowdsourced TA studies with crowdsourced text prompts. Our results suggest that crowdsourcing is a viable approach for conducting TA studies at scale.
</p>
"
---

# Acknowledgements

We thank Max Lisnic for help with Study 2 and the reviewers for their constructive feedback throughout the revision process, which helped substantially strengthen the manuscript. This work is supported by the National Science Foundation (NSF 2213756, 2213757, and 2313998).
