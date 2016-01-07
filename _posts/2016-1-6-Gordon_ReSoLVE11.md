---
layout : post
comments : true
title : Gordon+:ReSoLVE11 Ginkgo: Automated, Application-Driven Memory Overcommitment for Cloud Computing
---
This paper basically starts from an observation that the performance of virtual machines doesn't neccessary has linear relation with the size of memory that assiged to the VM. Then it describes a framework that collect the memory-performance information, model it, make decision that assigment memory to applications and enforce the decision.

The collector, orchestrator are seems trivial, which the authors don't spent lot of words on it. It is said that *Ginkgo* constructs the model by "characterizing a VM memory-to-performance relationship on a pre-load basis". It is basically classify the VM by the applications running on it and the input. Then *Ginkgo* model the performance by using the historic data of the same categorie.



