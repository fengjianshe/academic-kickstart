---
title: Adaptive PHM Framework
summary: This research proposes a systematic methodology to develop an effective online evolving PHM method with adaptive sampling mechanism against continuous stream data and in-process changes. 
tags:
- PHM, Adaptive Model
date: "2020-05-08T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Adaptive PHM Framework and SI Test
  focal_point: Smart

links:
- icon: researchgate
  icon_pack: fab
  name: Details
  url: https://www.researchgate.net/publication/336685442_Methodology_of_Adaptive_Prognostics_and_Health_Management_Using_Streaming_Data_in_Big_Data_Environment
url_code: ""
url_pdf: "https://www.phmpapers.org/index.php/phmconf/article/view/912"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Prognostics and health management (PHM) has gradually become an essential technique to improve the availability and efficiency of industrial systems. With the rapid advancement
of sensor technology and communication technology, a huge amount of real-time data is generated from various applications industry, which brings new challenges to PHM in the context of big data streams. On one hand, high-volume stream data places a heavy demand on data storage, communication, and PHM modeling. On the other hand, continuous fluctuation and drift are essential properties of stream data in an online environment, which requires the PHM model to be capable to capture the new formation in stream data adaptively and continuously. This research proposes a systematic methodology to develop an effective online evolving PHM method with adaptive sampling mechanism against continuous stream data and in-process changes. 

An adaptive sample selection strategy named Sample Importance (SI) Test is developed to effectively select the representative samples in both off-line and online environment. The SI test proposed here is composed of two tests: Data-based importance test and Model-based importance test.
DBI test considers determining the informativeness of the new sample based on the characteristics of the data. In other words, to make it general, we define the DBI test as freshness test, as it evaluate the importance regarding informativeness just as it is "fresh" or not compared with previously shown samples. MBI test considers determining the informativeness of the new sample based on the performance of the model’s prediction on this sample. The prediction performance here has two meanings: (1) whether the prediction has a good prediction accuracy; and (2) whether the prediction has a low uncertainty. In other words, to make it general, we define the MBI test as error test, which identified whether the sample has a large prediction error, or has a high prediction uncertainty.

Meanwhile, a probabilistic theory-based modeling approach is developed to update the model with newly selected samples. Finally, the whole methodology is validated with real-world industrial cases. The result comparison between the proposed methodology and state-ofart methods verifies the superiority of the proposed method.