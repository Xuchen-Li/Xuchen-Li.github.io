---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
## Conferences
* **A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Casual Relationship**<br>
  S. Hu, D. Zhang, M. Wu, X. Feng, **Xuchen Li**, X. Zhao, K. Huang<br>
  *NeurIPS 2023 (CCF-A Conference, Poster): [the 37th Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2023)*<br>
  [[PDF](https://xuchen-li.github.io/files/MGIT.pdf)]
  [[Poster](https://xuchen-li.github.io/files/MGIT-poster.pdf)]
  [[Slides](https://xuchen-li.github.io/files/MGIT-Slides.pdf)]
  [[Platform](http://videocube.aitestunion.com/)]
  [[Toolkit](https://github.com/Xuchen-Li/MGIT-toolkit)]
  **Abstract:** Tracking an arbitrary moving target in a video sequence is the foundation for high-level tasks like video understanding. Although existing visual-based trackers have demonstrated good tracking capabilities in short video sequences, they always perform poorly in complex environments, as represented by the recently proposed global instance tracking task, which consists of longer videos with more complicated narrative content. Recently, several works have introduced natural language into object tracking, desiring to address the limitations of relying only on a single visual modality. However, these selected videos are still short sequences with uncomplicated spatio-temporal and causal relationships, and the provided semantic descriptions are too simple to characterize video content.To address these issues, we (1) first propose a new multi-modal global instance tracking benchmark named MGIT. It consists of 150 long video sequences with a total of 2.03 million frames, aiming to fully represent the complex spatio-temporal and causal relationships coupled in longer narrative content. (2) Each video sequence is annotated with three semantic grains (i.e., action, activity, and story) to model the progressive process of human cognition. We expect this multi-granular annotation strategy can provide a favorable environment for multi-modal object tracking research and long video understanding. (3) Besides, we execute comparative experiments on existing multi-modal object tracking benchmarks, which not only explore the impact of different annotation methods, but also validate that our annotation method is a feasible solution for coupling human understanding into semantic labels. (4) Additionally, we conduct detailed experimental analyses on MGIT, and hope the explored performance bottlenecks of existing algorithms can support further research in multi-modal object tracking. The proposed benchmark, experimental results, and toolkit will be released gradually on http://videocube.aitestunion.com/.
