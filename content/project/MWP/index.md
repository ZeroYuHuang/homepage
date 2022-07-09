---
title: MATHion-Solving Math Word Problems with Logically Consistent Problems
summary: We propose a Contrastive-based logical retriever to boost Math Word Problem Solver performance
tags:
  - Deep Learning
  - NER
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Solving math word problems (MWPs) is a challenging task. Some existing solvers retrieve textually similar problems and draw on their solutions to solve the given problem. However, textually similar questions are not guaranteed to have similar solutions. Furthermore, questions could share the same solution template but with different descriptions. Therefore in this project, we investigate the logical consistency among different problems.

In this project, we propose MATHion, a contrastive learning-based “retrieve-then-generate” approach, which solves math word problems with logically consistent problems. Compared with previous methods, we employ contrastive learning to train the retriever to mainly focus on the logical consistency instead of textual similarity when extracting similar problems. Besides, we propose a gated initialization and an aligned guidance mechanism, thus the model could regard the solving template of the problem retrieved as hints in each generation step to produce the final expression.Solving math word problems (MWPs) is a challenging task. Some existing solvers retrieve textually similar problems and draw on their solutions to solve the given problem. However, textually similar questions are not guaranteed to have similar solutions. Furthermore, questions could share the same solution template but with different descriptions. Therefore in this project, we investigate the logical consistency among different problems.

![Model Framework](model.png)

Experimental results show that our method outperforms many strong baselines, including some pre-trained language model-based methods. Further analysis shows that our retrieval method does learn the logical similarity between questions and plays a key role in our model's performance.
![Experimental Results](results.png)

**Case Study**: To illustrate that our retriever does partially see through the narrative description and perceive the intrinsic logic, we give four cases shown in. We observe that the given problems and retrieved problems do not always share similar contexts but the consistent logic. 
![Experimental Results](case.png)



