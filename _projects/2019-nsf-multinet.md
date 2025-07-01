---
layout: project
agency: The National Science Foundation
key: 2019-nsf-multinet
permalink: /projects/2019-nsf-multinet/
website:
logo: nsf.jpg
title: "Collaborative Research: Framework: Software: HDR: Reproducible Visual Analysis of Multivariate Networks with MultiNet"
recipients:
 - University of Utah
 - Kitware
 - University of Idaho 
 - Knowledge Vis
 - Duke University
 - Carnegie Institution of Science
pi: lex
copi: 
 - meyer
 - Jeff Baumes 
 - Curtis Lisle
 - Luke Harmon
coinvestigators:
 - Bryan Jones
 - Christopher Bail
 - Shaunna Morrison
time: 01/01/2019-12/31/2022
program: DATANET, Software Institutes
agency-website: https://nsf.gov/awardsearch/showAward?AWD_ID=1835904
collaborative-award: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1835893
number: NSF OAC 1835904
active: true
updated: 2021-01-13
publications: 
 - 2019_vast_origraph
 - 2019_eurovis_mvnv
 - 2019_infovis_clipped_graphs
 - 2020_chi_mvnv_study
 - 2020_infovis_insights
 - 2021_chi_revisit
 - 2022_vis_data_hunches
 - 2023_chi_troubling
 - 2023_nsf_multinet

 
staff:
 - meyer
 - lex
 - wilburn
 - akbaba
 
otherstaff: 
 - Roni Choudhury (Kitware)
 - Jake Conway (Kitware)
 
alumni:
 - Mark Dewy
 - rogers

award: "$ 2,022,200"
award-utah: "$ 1,115,768"
award-lex: "$ 529,929.37"
award-meyer: "$ 529,929.37" 

---

Multivariate networks – datasets that link together entities that are associated with multiple different variables – are a critical data representation for a range of high-impact problems, from understanding how our bodies work to uncovering how social media influences society. These data representations are a rich and complex reflection of the multifaceted relationships that exist in the world. Reasoning about a problem using a multivariate network allows an analyst to ask questions beyond those about explicit connectivity alone: Do groups of social-media influencers have similar backgrounds or experiences? Do species that co-evolve live in similar climates? What patterns of cell-types support different types of brain functions? Questions like these require understanding patterns and trends about entities with respect to both their attributes and their connectivity, leading to inferences about relationships beyond the initial network structure. As data continues to become an increasingly important driver of scientific discovery, datasets of networks have also become increasingly complex. These networks capture information about relationships between entities as well as attributes of the entities and the connections. Tools used in practice today provide very limited support for reasoning about networks and are also limited in the how users can interact with them. This lack of support leaves analysts and scientists to piece together workflows using separate tools, and significant amounts of programming, especially in the data preparation step. This project aims fill this critical gap in the existing cyber-infrastructure ecosystem for reasoning about multivariate networks by developing MultiNet, a robust, flexible, secure, and sustainable open-source visual analysis system. 

MultiNet aims to change the landscape of visual analysis capabilities for reasoning about and analyzing multivariate networks. The web-based tool, along with an underlying plug-in-based framework, will support three core capabilities: 

1. interactive, task-driven visualization of both the connectivity and attributes of networks, 
2. reshaping the underlying network structure to bring the network into a shape that is well suited to address analysis questions, and 
3.  leveraging provenance data to support reproducibility, communication, and integration in computational workflows. 

These capabilities will allow scientists to ask new classes of questions about network datasets, and lead to insights about a wide range of pressing topics. To meet this goal, we will ground the design of MultiNet in four deeply collaborative case studies with domain scientists in biology, neuroscience, sociology, and geology.


## Software 

Multinet is web-based, open-source software. You can find the interactive application at: 

 * [https://multinet.app/](https://multinet.app/)
 
The source code for the projects is available at:
 
 * [https://vdl.sci.utah.edu/mvnv/](https://vdl.sci.utah.edu/mvnv/)

Origraph, our network wrangling prototype is available at: 
 * [https://origraph.github.io](https://origraph.github.io)
 
Our ranking method for multivariate network visualization techniques is available at:

 * [https://vdl.sci.utah.edu/mvnv/](https://vdl.sci.utah.edu/mvnv/)
