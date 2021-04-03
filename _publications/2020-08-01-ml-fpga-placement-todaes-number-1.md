---
title: "Machine Learning for Congestion Management and Routability Prediction within FPGA Placement"
collection: publications
permalink: /publication/2020-08-01-ml-fpga-placement-todaes-number-1
excerpt: 'The work done in this paper involves integrating machine learning and deep learning into the FPGA placement step to speed up the process without a decrease in the quality-of-result.'
date: 2020-08-01
venue: 'ACM Transactions on Design Automation of Electronic Systems (TODAES)'
paperurl: 'https://dl.acm.org/doi/10.1145/3373269'
citation: 'Hannah Szentimrey, Abeer Al-Hyari, Jeremy Foxcroft, Timothy Martin, David Noel, Gary Grewal, and Shawki Areibi. 2020. Machine Learning for Congestion Management and Routability Prediction within FPGA Placement. ACM Trans. Des. Autom. Electron. Syst. 25, 5, Article 37 (October 2020), 25 pages. DOI:https://doi.org/10.1145/3373269'
---

Placement for Field Programmable Gate Arrays (FPGAs) is one of the most important but time-consuming steps for achieving design closure. This article proposes the integration of three unique machine learning models into the state-of-the-art analytic placement tool GPlace3.0 with the aim of significantly reducing placement runtimes. The first model, MLCong, is based on linear regression and replaces the computationally expensive global router currently used in GPlace3.0 to estimate switch-level congestion. The second model, DLManage, is a convolutional encoder-decoder that uses heat maps based on the switch-level congestion estimates produced by MLCong to dynamically determine the amount of inflation to apply to each switch to resolve congestion. The third model, DLRoute, is a convolutional neural network that uses the previous heat maps to predict whether or not a placement solution is routable. Once a placement solution is determined to be routable, further optimization may be avoided, leading to improved runtimes. Experimental results obtained using 372 benchmarks provided by Xilinx Inc. show that when all three models are integrated into GPlace3.0, placement runtimes decrease by an average of 48%.

[Link to full paper](https://dl.acm.org/doi/10.1145/3373269)
