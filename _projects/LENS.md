---
title: "Localize-then-summarize: Enhancing scientific multimodal summarization with facet-aware cross-modal memory"
collection: projects
type: "---"
permalink: /projects/LENS
venue: ""
location: ""
---

*COLING-2025*

<div style="text-align: center; margin-bottom: 20px;">
  <a href="https://github.com/allent4n/LENS" target="_blank" style="text-decoration: none;">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" width="40" height="40" style="vertical-align: middle; margin-right: 10px;">
    <span style="font-size: 18px; color: #000;">Visit the GitHub Repository</span>
  </a>
</div>

Scientific papers follow structured facets (e.g., Introduction, Methods), and modern research dissemination increasingly incorporates multimodal formats like presentation videos and audio. This shift necessitates summarization systems that can process both structured and multimodal information. This work proposes Localize-then-Summarize (LENS), a two-stage scientific summarizer that first localizes relevant presentation segments that align with paper facets; followed by summarizing them via memory-augmented reasoning that models dependencies across modalities and facets. On a new MFS-SciSum dataset with 2.7k aligned paper–presentation pairs, the LENS localizer and summarizer achieve Recall@0.5/0.7 scores of 40.83/23.06, and ROUGE-1/2/L scores of 44.71/15.26/21.64, outperforming strong baselines like CLIP and Transformer by 10–15 points in Recall and 1–5 points in ROUGE (resp.). Additionally, the LENS summarizer reduces GPU usage by 71%, notably improving generation efficiency.

<img width="696" height="518" alt="615198702-bdb7fa57-0bf9-4464-bd8f-701fd3a09869" src="https://github.com/user-attachments/assets/bfd4cca8-2d07-4c90-9716-3e155dedaa29" />

