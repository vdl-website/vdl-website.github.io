---
layout: post
title: "ReVISit 2 Paper Wins Best Paper Award at IEEE VIS"
date: 2025-11-10
categories: blog
type: blog
publication_key: 2025_vis_revisit
hide-author-images: true
authors: 
 - lex
abstract: "IWe’re happy to share that our paper on ReVISit 2 received a Best Paper Award at IEEE VIS 2025. ReVISit 2 is an open framework for designing, deploying, and disseminating browser-based visualization studies across the full experiment life cycle. In this post, we summarize the contributions of the paper, describe the replication studies that demonstrate the system’s capabilities, reflect on feedback from users, and outline how reVISit can support more reproducible and expressive experimental research.
"
lead-image: /assets/images/posts/2026_award_photo.jpg
lead-image-alt-text: "Selfie by the reVISit team on stage at IEEE VIS in Vienna after receiving the award."
---



Running online visualization studies is now standard practice in VIS and HCI research. Yet the process remains fragmented: researchers stitch together survey tools, custom web code, logging scripts, analysis pipelines, and ad hoc debugging workflows. Users of [reVISit](https://revisit.dev) already know this story: reVISit consolidates this ecosystem into a single open framework that supports the **entire experiment life cycle** – from design to dissemination.  

To inform the academic community about the new developments in reVISit 2 – which we already described in these [blog](https://revisit.dev/blog/2025/01/20/release-2.0/  
) [posts](https://revisit.dev/blog/2025/10/27/release-2.3/)  we wrote an [academic paper](https://www.visdesignlab.net/publications/2025_vis_revisit/) about it.

## Positioning reVISit in the Ecosystem

In the paper, we first situate reVISit among existing study platforms. We compare it to commercial survey systems, domain-specific research tools, and library-based frameworks. While survey platforms excel at rapid deployment, they rarely support sophisticated interaction logging or fine-grained experimental control. Academic tools often address specific domains or slices of the workflow, but lack long-term maintainability or broad adoption.

ReVISit 2 is designed differently: it treats experiment design as programmable infrastructure. A JSON-based domain-specific language (DSL) models sequences, blocks, counterbalancing strategies, interruptions, skip logic, and dynamic control flow. On top of that, reVISitPy provides Python bindings that allow researchers to generate complex study configurations directly from notebooks. **The result is a framework that emphasizes expressiveness, reproducibility, and ownership over one’s experimental stack.**

We also describe technical advances in reVISit 2, including first-class Vega support, automated provenance tracking, participant replay, and improved debugging tools such as the study browser. These features aim to tighten feedback loops during piloting while preserving transparency during dissemination.


## Putting it to the Test: Replication Studies

To demonstrate that these capabilities are not merely architectural, we conducted a series of replication studies.

![Screenshot of the revisit analysis interface showing a replay of an interactive study with think aloud and provenance tracking. A large bubble chart is the main stimulus.](/assets/images/posts/2026_bubble_chart.png)


Each study highlights a different capability of the system. In one, we implement adaptive and staircase-style designs to [evaluate visualizations of correlations](https://revisit.dev/replication-studies/?tab=JND) using [dynamic sequencing logic](https://revisit.dev/docs/typedoc/interfaces/DynamicBlock/), showing how complex control flow can be expressed directly in the study configuration. In another, we integrate [think-aloud protocols](https://revisit.dev/docs/designing-studies/think-aloud/) by embedding audio recording and transcription into browser-based experiments, allowing [researchers to capture reasoning during interaction](https://revisit.dev/replication-studies/?tab=Search) rather than only after the fact. Finally, we demonstrate [provenance tracking and replay](https://revisit.dev/replication-studies/?tab=Pattern) by instrumenting interactive visualizations to capture detailed interaction histories, enabling fine-grained participant replay and qualitative analysis. reVISit 2 also provides deep linking to specific trials or moments in user studies, to aid in dissemination and transparency. For example, [this link](https://revisit.dev/replication-studies/bubblechart-study/LzE2MTl4ZVRMTk5nSFlNYmd1ZDhjZz09?participantId=936e6c58-fc6e-4e1f-9af9-9c9ce2a65952) takes you to the exact state you see in the above image. 

Across these replications, we recruited hundreds of participants and reproduced key findings from prior visualization studies. Just as importantly, the studies surfaced practical lessons about counterbalancing, recruitment logistics, and ongoing challenges in deploying sophisticated designs online. The replication work serves as both validation and stress test for the framework, and as real live examples for studies (including the data) for the community to learn from. 

Across these replications, we recruited hundreds of participants and reproduced key findings from prior visualization studies. Just as importantly, the studies surfaced practical lessons about counterbalancing, recruitment logistics, and the realities of deploying sophisticated designs online. Together, they function both as validation and as a stress test of the framework. **They also remain publicly accessible – complete with study configurations and data – serving as concrete, real-world examples that the community can inspect, reuse, and learn from.**


## What Users Told Us

We also interviewed experienced reVISit users to better understand how the system performs in practice. Several themes emerged:

- **Tighter development loops.** Users appreciated the integrated development environment and the study browser, which makes it possible to jump directly to specific trials without stepping through an entire study.
- **Expressiveness over convenience.** While the DSL requires programming knowledge, users valued the flexibility it affords – especially for mixed designs and adaptive sequencing.
- **Learning curve trade-offs.** ReVISit inherits complexity from modern web tooling (e.g., React, TypeScript). This can be a barrier for less technical researchers, but it also enables deeper customization and extensibility.
- **Open infrastructure.** The ability to fork studies, inspect core code, and maintain version stability was frequently cited as a strength, particularly for reproducibility.

Overall, feedback confirmed that reVISit is most effective for technically oriented research teams who need more than a survey builder.

## Recognition at IEEE VIS

We were very honored to receive an [**IEEE VIS Best Paper Award**](https://ieeevis.org/year/2025/info/awards/best-paper-awards#:~:text=ReVISit%202%3A%20A%20Full%20Experiment%20Life%20Cycle%20User%20Study%20Framework) for this work. Zach Cutler presented the paper on the main stage in Vienna.  

![Zach Cutler presenting the paper at IEEE VIS in Vienna.](/assets/images/posts/2026_zach_presenting.jpg)



This recognition reflects years of iterative development, community feedback, tutorials, documentation work, and, most importantly, the researchers who have trusted ReVISit in their own studies.

ReVISit 2 is not the endpoint. It is infrastructure for a research community that increasingly relies on sophisticated, reproducible, browser-based experiments. We look forward to continuing to build it together.



