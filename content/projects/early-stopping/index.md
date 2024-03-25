---
title: Latency-accuracy tradeoffs for inference with early stopping
date: 2024-03-23
show_date: false
---

**Researchers:** Aliasghar Mohammadsalehi, Waheed U. Bajwa 

One of the aspects of the rings project is to reduce the latency for real-time applications of ml. To achieve this goal, we can reduce the inference time of the models we use in our applications. We mostly use enormous models to predict the label for our data which takes a lot of time to get the response. In order to decrease this time, we can find a way to get those labels before we finish the entire model. To do so, we can inject some internal classifier that can predict the label at earlier layers. This method can greatly reduce inference time. However, we would get a response with a lower confidence level. Therefore, I’m currently working on finding a way to minimize the latency while maximizing the confidence level of the response at that layer. 

<!-- more -->


