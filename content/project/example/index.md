---
title: Low Latency Queuing Control in Extendable Mobile Ad-hoc Network Emulator (EMANE)
font_size=12
summary: Designed and tested a novel low-latency network scheduling module for various queueing policies using C/C++ under Linux Ubuntu system, and evaluated the algorithm in WAN under Common Open Research Emulator (CORE)
tags:
- Computing Network
date: "2020-09-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""


links:
url_code: "https://github.com/szl0144/EMANE_CORE"
url_pdf: ""
url_slides: ""
url_video: ""


---

A variation packets delay which is also called packet jitter causes packet loss and delay. When jitter happens to stream video, users suffer an annoying freezes which results in user unpleasant. The solution for reducing jitter probability is a low latency low-complexity scheduling policy in queuing system: the Earliest Due Date first (EDD) policy. To evaluate the performance of EDD in a real-world wireless network system. We implement EDD algorithms on Extendable Mobile Ad-hoc Network Emulator (EMANE) to take virtual field tests. In this paper, we present the design and implementation of a low-complexity queue scheduling module in both single-hop multi-server systems using C/C++. We also show an efficient debug method in EMANE development. Our emulation results demonstrate the EDD policy achieves over 1000x reduction in jitter probability compared to the commonly used FCFS policy.
