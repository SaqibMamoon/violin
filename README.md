## VIOLIN: A Large-Scale Dataset for Video-and-Language Inference
Data and code for CVPR 2020 paper: "VIOLIN: A Large-Scale Dataset for Video-and-Language Inference"

![example](imgs/example.png)

We introduce a new task, Video-and-Language Inference, for joint multimodal understanding of video and text. Given a video clip with aligned subtitles as premise, paired with a natural language hypothesis based on the video content, a model needs to infer whether the hypothesis is entailed or contradicted by the given video clip. A new large-scale dataset, named *__Violin__* (VIdeO-and-Language INference), is introduced for this task, which consists of 95,322 video-hypothesis pairs from 15,887 video clips, spanning over 582 hours of video. These video clips contain rich content with diverse temporal dynamics, event shifts, and people interactions, collected from two sources: (i) popular TV shows, and (ii) movie clips from YouTube channels. In order to address our new multimodal inference task, a model is required to possess sophisticated reasoning skills, from surface-level grounding (e.g., identifying objects and characters in the video) to in-depth commonsense reasoning (e.g., inferring causal relations of events in the video). We present a detailed analysis of the dataset and an extensive evaluation over many strong baselines, providing valuable insights on the challenges of this new task.

### Violin Dataset
- Data Statistics

### Baseline Models
- Model Overview
![model](imgs/model.png)

[comment]: # (### Citation)

