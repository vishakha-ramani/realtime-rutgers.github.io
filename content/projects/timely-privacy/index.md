---
title: Timeliness and privacy leakage for realtime systems
date: 2024-03-23
show_date: false
---

**Researchers:** Nitya Sathyavageeswaran, Anand D. Sarwate, Narayan B. Mandayam, Roy D. Yates

A source (mobile device) generates time-stamped update packets that are sent to a server and then forwarded to an edge cloud (monitor). This occurs in the presence of an adversary that can infer information about the source by observing the output process of the server. The server wishes to release updates in a timely way to the monitor but also wishes to minimize the information leaked to the adversary.

<!-- more -->

We analyze the trade-off between the age of information (AoI) and the maximal leakage for systems in which the source generates updates as a Bernoulli process. For a time slotted system in which sending an update requires one slot, we consider two classes of service policies: (1) Queueing: arriving updates are queued with some probability and head-of-line update is released after a general (arbitrary) holding time; (2) Dumping: the most recently generated update (if any) is released after an arbitrary time. We find optimal service policies (within a given class) to manage the age-leakage tradeoff for a given arrival process. This work addresses the major challenge of a mobile device that requires privacy-sensitive use of the MEC. 
