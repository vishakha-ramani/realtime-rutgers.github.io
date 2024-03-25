---
title: Learning to help – offloading for legacy devices
date: 2024-03-23
show_date: false
---

**Researchers:** Yu Wu, Anand D. Sarwate 

The emerging paradigm of mobile edge cloud (MEC) systems provides a rich source of interesting machine learning problems. In a MEC architecture, mobile devices collaborate with cloud computing resources at the “edge” of the network to perform inference and learning. The service on mobile devices and edges may come from different service providers. Restricted by the hardware limit or access authority, sometimes it’s hard to jointly train (update) the machine learning model on both sides. 

<!-- more -->

In this project, we propose a "Learning to Help" model,  which a pre-trained model, usually embedded on mobile device, is adaptively enhanced by different external classifiers, usually provided by edge, under dynamic environment. We derived the Bayes classifiers in this model and proved the generalization upper bound. For implementation of our algorithm, we provided convex surrogate loss function for the natural 0-1 loss and proved the consistency of the surrogate loss. The Hot-swap Learning model shows extensibility to our future work on large MEC with multi-mobile, multi-edge and multi-cloud. This work addresses the major challenge where mobile platforms are heterogeneous, ranging from energy-harvesting sensors to auto-mobiles, but storage and compute resources are generally limited in comparison to the edge and server clouds while high-accuracy inferences are timely required. 
