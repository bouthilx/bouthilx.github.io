---
title: "Mahler: Orchestration engine for high latency systems and dynamic workflows"
excerpt: "For my research projects I developped a framework to automatically setup all available clusters and deploy my experiments. With Mahler, I can wrap the super computer schedulers to gain more control over my workflow, better resiliency and better automation."
collection: projects
---

<b>Source code</b> [github.com/bouthilx/mahler](https://github.com/bouthilx/mahler)

This project is still a prototype. There is no documentation and no testing yet.
{: .notice}

For my research projects I developped a framework to automatically setup all available clusters and 
deploy my experiments. We typically have very little user rights on super computers
which makes it difficult to use the orchestration tools developped for the cloud. With Mahler, I can
wrap the super computer schedulers to gain more control over my workflow, better resiliency and
better automation. Thanks to this framework, I have been able to run all experiments for our paper
[Unreproducible Research is Reproducible](/publication/2019-05-24-unreproducible-research) in less
than 5 days without any intervention. That is slightly more than 39k experiments.



