---
layout: project
agency: The National Science Foundation
key: 2018-nsf-reproducibility
permalink: /projects/2018-nsf-reproducibility/
website:
logo: nsf.jpg
title: "CAREER: Enabling Reproducibility of Interactive Visual Data Analysis"
#recipients:
# - University of Utah 
pi: lex
copi: 
coinvestigators:
time: 04/01/2018-03/31/2024
program: IIS CAREER 
agency-website: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1751238
number: NSF IIS 1751238
active: true
updated: 2022-05-09
publications: 
 - 2018_vahc_composer
 - 2019_aci_composer
 - 2018_infovis_juniper
 - 2019_eurovis_mvnv
 - 2019_vast_origraph
 - 2019_ivi_taggle
 - 2020_visshort_trrack
 - 2021_chi_revisit
 - 2021_ivi_intent
 - 2022_eurovis_reusing
 - 2022_vis_data_hunches
 - 2023_eurovis_ferret
 - 2024_eurovis_persist


staff:
 - lex
 - kiran
 - lange

 
alumni:
 - rogers
 - zcutler
 - hannah 
 - goertler
 - prajan

otherstaff:  

award: "$ 512,245"

---

Reproducibility and justifiability are widely recognized as critical aspects of data-driven decision making in fields as varied as scientific research, business, healthcare, or intelligence analysis. This project is concerned with enabling reproducibility and justifiability of decisions in the data analysis process, specifically as it relates to visual data analysis. Visualization is an important tool for discovery, yet decisions made by humans based on visualizations of data are difficult to capture and to justify. This project will develop methods to justify, communicate, and audit decisions made based on visual analysis. This, in turn will lead to better outcomes, achieved with less effort and cost. The increasing use of visual analysis tools for decision making will make data analysis accessible to a broad variety of people, as visual analysis tools are generally easier to use than scripting languages and do not require extensive computational and statistical training. This research and its related activities increase accessibility and enhance the data analysis infrastructure for research and education. 

To achieve these goals, this research will develop a framework for making visual analysis sessions not only reproducible but also reusable. The approach is based on tracking semantically meaningful provenance data during an interactive visual analysis session. Once a discovery is made, analysts can use this history to curate a succinct analysis story, adding justifications and explanations to make their analysis reproducible by others. Using a semi-automatic process, analysts will be able to make their actions data-aware, so that their analysis processes become robust to changes, such as updates in the data. A second contribution of the proposed work is the integration of visual analysis into computational analysis processes. While visualization is commonly used to present computational analysis results, the results of a visual analysis session are rarely used to feed into further computational processes. The techniques developed in this project will allow analysts to feed analysis results (selections, aggregations, filters, etc.) back into a computational environment. This will make it possible to use interactive visualization at any point in the data analysis process while maintaining reproducibility and enabling reuse. The expected results include new methods to capture user intent, create data stories from analysis processes, and to integrate computational and visual data analysis, leveraging the strength of both, human abilities and computational power. The results will be disseminated in publications and in the form of open source software, and accessible via this website.

![Reproducibility Framework Concept](../2018-nsf-reproducibility_concept.png)

## Software

We are developing a provenance tracking library for integration with web applications. The source code is available [here](https://github.com/visdesignlab/trrack), and a blog post is [also available](https://vdl.sci.utah.edu/blog/2020/10/28/trrack/). 

We are also working on a visualization tool to capture analysis intent using the provenance library discussed above. Find the code [here](https://github.com/visdesignlab/intent-system), and a live-demo of the system at [this page](https://vdl.sci.utah.edu/predicting-intent/). 

The following image illustrates the interface: 

![The predicting intent visualization user interface]({{ site.base_url }}/assets/images/publications/2021_ivi_intent_teaser.png)


Check out the two core paper for this project, on  [predicting intent]({{ site.base_url }}/publications/2021_ivi_intent/) and [reusing workflows]({{ site.base_url }}/publications/2022_eurovis_reusing_workflows/). 




