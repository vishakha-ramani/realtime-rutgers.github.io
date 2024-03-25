---
title: Unsupervised online learning in decentralized networks
date: 2024-03-23
show_date: false
---

**Researchers:** Muhammad Zulqarnain, Waheed U. Bajwa 

The precision of numerous downstream machine learning models is directly linked to the uncorrelated nature of training data. With the increasing trend of data often being streamed, geographically spread out, and having high dimensions, it's vital to utilize both uncorrelated feature learning and dimension reduction techniques. Principal Component Analysis (PCA) is a leading-edge tool that offers uncorrelated features and minimizes data dimensions by mapping data onto the population covariance matrix's eigenvectors. Our research tackles challenge (C3) that necessitates mobile devices to draw inferences from high-dimensional data. 

<!-- more -->

Specifically, we introduce an innovative algorithm termed as Consensus-DIstributEd Generalized Oja (C-DIEGO). This method uses Oja's approach to estimate the leading eigenvector of a population covariance matrix in a distributed streaming environment. Our research considers the complete graph without the need for a central coordinator and assumes that high-dimensional data samples are consistently streaming to individual nodes. My research aims to estimate the eigenvectors of the population covariance matrix, so PCA can be applied to each data sample and uncorrelated low-dimensional features can be extracted in real time. 