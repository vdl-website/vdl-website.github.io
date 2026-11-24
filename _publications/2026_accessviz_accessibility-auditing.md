---
layout: publication
title: "Visual Accessibility Auditing Across Interaction States and Reading Orders"
key: 2026_accessviz_accessibility-auditing
type: workshop
order: 2026-1
shortname: Site Accessibility Auditor
image: 2026_accessviz_accessibility-auditing.png
image_large: 2026_accessviz_accessibility-auditing_teaser.png
image_alt_text: "Screenshot of the interaction lens auditing the Utah Wastewater Surveillance System dashboard. The live page is overlaid with colored bounding boxes marking each audited target as passing, warning, or failing. Beside it, a Chrome DevTools page shows a scrollable findings list (A), a page map with the same color coding (B), and a detail inspector for the selected target with its size measurements and DOM selector (C). A bottom row shows four example WCAG rule cards, including focus visible and non-text contrast, each with the failing value, an explanation, and a fix suggestion. A panel on iterative fixing and tracking shows a button enlarged from 16 to 24 px wide (D), and a session comparison confirming the issue is resolved (E)."
authors:
  - Md Rahat-uz-Zaman
  - wagoner
  - he
  - lex
  - Paul Rosen
journal-short: AccessViz Workshop
year: 2026
bibentry: inproceedings
bib:
  booktitle: Proceedings of Workshop on Accessible Data Visualization (AccessViz) at IEEE VIS
  year: 2026
pdf: 2026_accessviz_accessibility-auditing.pdf
code: https://github.com/rahatzamancse/site-accessibility-auditor
abstract: >-
  <p>Automated accessibility checkers evaluate a single snapshot of a
  page, but many barriers only emerge over multiple interactions rather than a static snapshot. Several WCAG 2.2 criteria depend on geometry, focus state, or interaction history, such as a button that becomes obscured once a sticky header appears. Others arise when the visual layout, the screen-reader order, and the keyboard (Tab) order of a page disagree, so different users encounter the same content in conflicting sequences. Auditing these requires reasoning about geometry and structure alongside the live page, which makes it both a detection and a visualization problem. We present Site Accessibility Auditor, a Chrome DevTools extension with two coordinated lenses. The interaction lens automatically drives the page through its reachable states and overlays interaction-dependent issues as inspectable visual evidence on a full-page capture. The reading &amp; focus order lens aligns the visual, screen-reader, and keyboard orders, shows where they diverge, and suppresses intentional patterns such as skip links. We actively evaluate the extension as site owners and as an auditor. In a design partnership with the Utah Wastewater Surveillance System dashboard, our tool motivated the team to ship accessibility fixes. We used the tool on the Our World in Data site, which shows that the approach runs on an unmodified in-the-wild example.</p>
---

# Acknowledgements

This work was supported by the Centers for Disease Control and
Prevention’s Center for Forecasting and Outbreak Analytics Cooperative agreement CDC-RFA-FT-23-0069. We acknowledge the feedback and collaborative efforts of Nathan Lacross, Kerry Regan, Mary Jewell, Bree Barbeau, and Abigail Collingwood from the Utah DHHS and Matthew Samore and George Vega Yon at the University of Utah.