---
title: Online Virtual Metrology of Semiconductor Manufacturing Processes
summary: Modeling of dynamic manufacturing processes with slow drift using data-driven approaches is challenging because most data-driven models are trained by off-line data. In this paper, we propose to track slow drift of manufacturing process using an sequential Bayesian Auto-Regression eXogenous (ARX) model with time-variant parameters.
tags:
- PHM
- Adaptive Learning
- Virtual Metrology
- Bayesian
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: ieee
  icon_pack: ai
  name: Link
  url: https://ieeexplore.ieee.org/document/8845673
url_code: ""
url_pdf: "https://www.researchgate.net/publication/335956520_An_Online_Virtual_Metrology_Model_With_Sample_Selection_for_the_Tracking_of_Dynamic_Manufacturing_Processes_With_Slow_Drift"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Virtual Metrology (VM) is an essential research for manufacturing processes, which aims to estimate the difficult-to-measure parameters of products or processes by computer programs. Modeling of dynamic manufacturing processes with slow drift using data-driven approaches is challenging because most data-driven models are trained by off-line data. In this paper, we propose to track slow drift of manufacturing process using an online Bayesian Auto-Regression eXogenous (ARX) model with time-variant parameters. The model parameters are trained off-line and are updated online using Bayes’ rule. To avoid frequent online model update, a Sample Importance test is proposed to screen online samples and only the sample that passes SI test is incremented to the VM model. The SI test decides the importance of the sample by collectively considering sample freshness, model prediction error and prediction uncertainty. The off-line sample selection algorithm can effectively reduce the sample redundancy in off-line DB while maintaining the model performance. To validate the effectiveness of the proposed method, Prognostics and Health Management (PHM) data challenge 2016 dataset is employed to predict material removal rate of chemical-mechanical planarization process. The validation results indicate that the proposed method outperforms existing state-of-art approaches in literature such as Just-in-Time (JIT) and deep learning models.
