---
layout: post
title: Reusing Operations In Interactive Visualizations and Computational Notebooks
date: 2023-01-03 1:00:00
categories: blog
type: blog
authors:
- kiran
- lex
publication_key: 2022_eurovis_reusing
abstract: "
Interactive data analysis leverages human perception to enable various analysis tasks; however, a prior analysis can rarely be used when the dataset updates or is transferred to a different analysis environment, like a computational notebook. In this post, we discuss how we can capture reusable interactive workflows.
"
lead-image: /assets/images/posts/2023_reusing_workflows_lead.png

lead-image-alt-text: Figure shows a scatterplot with a cluster dataset. One cluster is selected. Next to the scatterplot is a provenance graph with three steps - adding scatterplot, select 61 points, and apply cluster selections. The caption reads 'Curate workflow from analysis provenance' There are two arrows originating from the scatterplot. One points to another scatterplot, which shows the selected cluster moving along Y-axis. Polygons indicate selected cluster. The caption reads 'Reapply the workflows on updated datasets' The other arrow points to a screenshot of jupyter notebook which demonstrate use of the Reapply library. The caption reads 'Apply the workflow in different environment'
---
_For the publication and prototype for capturing reusable workflows, please see [the paper page]({{site.base_url}}/publications/2022_eurovis_reusing_workflows)._

Interactive data visualization is useful for identifying patterns in datasets, but it can also be used for data wrangling. Cleanup operations such as filtering, labeling, and aggregation, are often more efficiently done in an interactive, visual system. However, **interactive data analysis is ad-hoc: when datasets update or change, an analyst has to redo the analysis and can’t just re-use operations**.

Computational data analysis environments like Jupyter Notebooks, on the other hand, enable **highly reusable data analysis**: operations can be written inside a function, which can be called at any time and also on new or updated datasets. The flexible and reusable nature of computational environments comes at the cost of requiring programming knowledge and a lack of native support for interactive visualization.

In this work, we attempt to **bridge the gap between intuitive interfaces and reusable operations by making sequences of operations (workflows) executed in interactive visualization systems reusable.**


## What are Workflows?

In visual data analysis, we define workflows as steps to achieve a data transformation or another analysis goal. Workflows can be explicitly modeled; or they can leverage operations captured during an analyst's interactive analysis sessions. The latter has the advantage that analysts can interact naturally with a visualization tool without worrying about workflows until they have achieved their goal. After reaching that goal, analysts can review and curate their analysis history into a workflow. 

## Capturing Reusable Workflows

We previously developed the [Trrack library]({{site.base_url}}/blog/2020/10/28/trrack/) to capture interaction provenance in a visualization system. In our new system, analysts can curate the captured provenance to create a workflow, for example, by removing extraneous steps taken in the original analysis. Such simple workflows work well when they are reapplied to the same dataset but are not robust to updates in the data, as shown in the following figure.

![The figure shows captured analysis in the first column, curated workflow in the second column, and results of applying the workflow in the third column. The captured analysis has four steps — add scatterplot, select points, filter out selections, and resize plot. The curated workflow has three steps — add scatterplot, select points and filter out selections. The workflow is labeled ‘Filter outliers workflow.’]({{site.base_url}}/assets/images/posts/2023_reusing_workflows_non_smart_workflow.png)
_An analyst curated a “Filter Outliers Workflow” from captured provenance. The workflow is then applied to an updated dataset where three new outliers are added (red). Reapplying the workflow on the updated dataset results in two points (highlighted in green) not being detected as outliers._

To make workflows reusable and enable their application on updated datasets, we use methods that [add semantic information about the patterns selected to the captured interactions]({{site.base_url}}/blog/2022/10/28/intent/). Instead of selecting a list of points as part of a workflow, we select the underlying higher-level pattern, such as “outliers” or “clusters.”
The following figure illustrates the process.


![The figure shows captured analysis in the first column, curated workflow in the second column, and results of applying the workflow in the third column. The captured analysis has four steps — add scatterplot, select points, refine selections to select outliers, and filter out selections. The curated workflow has three steps — add a scatterplot, select outliers, and filter out selections. The workflow is labeled ‘Filter outliers workflow.’]({{site.base_url}}/assets/images/posts/2023_reusing_workflows_smart_workflow.png)
_A “Semantic Filter Outliers Workflow” curated from semantically rich interaction provenance. The workflow contains the more meaningful “selecting outliers” step instead of just “selecting points.” Using such a smart workflow can help to correctly detect outliers when reapplied on an updated dataset. Here, five new points (three outliers and two inliers) were added and are correctly filtered._

## So What is this Good For?

The most crucial application of captured workflows is **reuse on updated or changing datasets**. Datasets, as they are visualized, frequently change! Visualization might reveal problems in how the data was wrangled, requiring an update. Or new data may come in periodically. Once a dataset is updated, all steps taken with a conventional visualization tool must be repeated.

To remedy this, we developed a prototype to demonstrate how the captured workflows can be automatically reapplied when the datasets updates. The prototype allows analysts to compare the reapplication process by explicitly visualizing the difference between the datasets and interactions when applied to the datasets. The following figure shows two datasets where a cluster was selected that has moved down in an update. 

<img src="{{site.base_url}}/assets/images/posts/2023_reusing_workflows_compare_view.png"  alt="Figure shows a scatterplot for a clustered dataset in compare view of the prototype. Four distinct clusters are visible. One of the clusters has shifted down along the Y-axis. The plot shows the previous and new locations of points. Multiple points have been added and removed from the plot and are shown using different marks. Polygons indicate the selected cluster." width="75%">

_Tracking a cluster over a data update. Analysts can use the compare mode in our prototype to see their original selection and how the selection was transferred to the updated dataset. Compare mode shows the change in the points using trails for points that moved; and Xs and triangles for points that were removed and added, respectively. In this example, we see that the selected cluster moved down along the Y-axis, and the system transferred the cluster selection to the displaced cluster._

Automatic reapplication might not be appropriate depending on the update to the dataset. To handle such cases, we enable analysts to review a reapplied workflow. Analysts can approve or reject the application and add an alternate analysis for a particular dataset version. The following figure shows an example of a review that may need to be modified. 

![The figure shows two scatterplots and two provenance histories. The first scatterplot has a cluster selected and the corresponding provenance history shows three steps — add scatterplot, select 61 points, and apply cluster selection. All the steps have a green checkmark. The second scatterplot has the selected cluster broken into subclusters. The provenance has the same steps as the previous one. The ‘Selection’ and ‘apply cluster’ steps have a red cross.]({{site.base_url}}/assets/images/posts/2023_reusing_workflows_review_mode.png)
_Ambiguos dataset update. An analyst created a workflow to select a cluster. The dataset was updated, and the cluster broke into two smaller clusters. The system transferred the selection and selected both the smaller clusters. As this is not what was intended, the analyst then uses the review mechanism to mark the reapplication as incorrect in the interaction provenance and subsequently can refine the selection. Approved steps are shown with green checkmarks, and rejected steps are shown with a red cross._

## Bridging Between Interactive Tools and Computational Notebooks

Another application of smart workflows is bridging the gap between interactive visual analysis tools and computational analysis environments. Data analysis often involves multiple tools, and having the ability to switch from interactive tools back to a scripting approach easily has many benefits. Imagine, for example, being able to use an interactive tool to clean up a dataset, aggregate data points, or add labels or categorization, and then being able to use these newly derived values directly in a Jupyter Notebook!

**We developed the [Reapply python library](https://github.com/visdesignlab/reusing-intent/tree/main/reapply-workflows) to facilitate the use of workflows created in our prototype in a Jupyter notebook.**

![The figure shows multiple screenshots to load and apply a workflow using the reapply library.]({{site.base_url}}/assets/images/posts/2023_reusing_workflows_comp.png)
_Working with the Reapply library. An analyst imports the ‘Reapply’ library, loads the Covid project and loads the ‘categorize outliers’ workflow to reapply. They apply the loaded workflow to subsets of the Covid dataset for Dec 2020, Jan 2021, and June 2021. The analyst then aggregates the datasets using the newly created ‘case category’ column and creates histograms for further analysis. You can check out the initial analysis provenance [here](https://reapply-workflows.github.io/reapply-workflows/#/explore?workflow=1631260396517), and the Google Colab notebook [here](https://colab.research.google.com/drive/1EpNqN1JuicsauzixhGAv_s9mjP5qijLj?usp=sharing)._

We can further expand the use of reusable workflows to create workflow templates that can be generalized to reapply the workflows on unrelated datasets. In future work, we want to explore deeper integration between computational notebooks and interactive visualizations using interaction provenance.

Finally, check out our [interactive prototype](https://reapply-workflows.github.io/reapply-workflows/#/project), and the [Reapply library](https://test.pypi.org/project/reapply-workflows/), or watch the video below. 


<div style="padding:56.25% 0 0 0;position:relative;">
    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/6zUdTOarBIo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
