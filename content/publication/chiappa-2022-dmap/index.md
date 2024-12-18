---
title: 'DMAP: a Distributed Morphological Attention Policy for learning to locomote
  with a changing body'
authors:
- admin
- Alessandro Marin Vargas
- Alexander Mathis
date: '2022-11-01'
publishDate: '2024-11-16T17:37:15.250465Z'
publication_types:
- paper-conference
publication: '*Neural Information Processing Systems (NeurIPS)*'
abstract: Biological and artificial agents need to deal with constant changes in the real world. We study this problem in four classical continuous control environments, augmented with morphological perturbations. Learning to locomote when the length and the thickness of different body parts vary is challenging, as the control policy is required to adapt to the morphology to successfully balance and advance the agent. We show that a control policy based on the proprioceptive state performs poorly with highly variable body configurations, while an (oracle) agent with access to a learned encoding of the perturbation performs significantly better. We introduce DMAP, a biologically-inspired, attention-based policy network architecture. DMAP combines independent proprioceptive processing, a distributed policy with individual controllers for each joint, and an attention mechanism, to dynamically gate sensory information from different body parts to different controllers. Despite not having access to the (hidden) morphology information, DMAP can be trained end-to-end in all the considered environments, overall matching or surpassing the performance of an oracle agent. Thus DMAP, implementing principles from biological motor control, provides a strong inductive bias for learning challenging sensorimotor tasks. Overall, our work corroborates the power of these principles in challenging locomotion tasks.

# Summary. An optional shortened abstract.
summary: DMAP is an attention-based policy network which develops a representation of the agent's body and adapts to its changes.

tags:
  - NeurIPS
  - Reinforcement Learning
  - Adaptation
  - Motor Control

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: NeurIPS
  url: https://proceedings.neurips.cc/paper_files/paper/2022/file/f0fae49cdfab57c41c30c9b0244093cb-Paper-Conference.pdf

url_pdf: 'https://proceedings.neurips.cc/paper_files/paper/2022/file/f0fae49cdfab57c41c30c9b0244093cb-Paper-Conference.pdf'
url_code: 'https://github.com/amathislab/dmap'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

---
