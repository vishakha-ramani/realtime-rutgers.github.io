---
title: Timeliness in shared-memory updating systems
date: 2024-03-23
show_date: false
---

**Researchers:** Vishakha Ramani, Jiachen Chen, Roy D. Yates

This project is about using Ago of Information (AoI) metrics to help design edge-computing applications where information publishers and subscriber work with a shared memory.

<!-- more -->

A dense metropolis is a complex traffic environment, and autonomous cars with a plethora of attached sensors still have limited situational awareness. Hence, holistic situational awareness of a cloud-connected vehicle is facilitated by a) timely collection of sensory inputs from different sources (e.g., other vehicles, pedestrians, and smart city infrastructure sensors) , and b) employing this sensor data to provide timely feedback or decision updates to participating mobile clients.

The design and implementation of such edge-computing applications is based on publish-subscribe communication paradigm where the delivery of information from publishers to subscribers is decoupled. The current work presents an analytical framework based on the publish-subscribe interaction paradigm, that is to be used for disseminating source updates to interested clients in order for them to process these source updates and arrive at decisions in a timely way. We consider a system where the updates from independent sources are disseminated via a publish-subscribe mechanism and a decision process (DP) derives decision updates from the source data. We derive the stationary expected age of information (AoI) of decision updates delivered to a monitor.

We show that a lazy computation policy in which the DP may sit idle before computing its next decision update can reduce the average AoI at the monitor even though the DP exerts no control over the generation of source updates. This AoI reduction is shown to occur because lazy computation can offset the negative effect of high variance in the computation time.

