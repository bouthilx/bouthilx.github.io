---
title: "Oríon: A framework for distributed hyperparameter optimisation"
excerpt: "I am the lead developper of Oríon, an open-source framework developed at Mila for distributed black-box optimization. Its purpose is to serve as a meta-optimizer for machine learning models and training, as well as a flexible experimentation platform for large scale asynchronous optimization procedures."
collection: projects
---

<b>Documentation</b> [orion.readthedocs.io](https://orion.readthedocs.io) <br/>
<b>Source code</b> [github.com/Epistimio/orion](https://github.com/Epistimio/orion)

I am the lead developper of Oríon, an open-source framework developed at Mila for distributed
black-box optimization. Its purpose is to serve as a meta-optimizer for machine learning models and
training, as well as a flexible experimentation platform for large scale asynchronous optimization
procedures. Core design value is the minimum disruption of a researcher’s workflow. It allows fast
and efficient tuning, providing minimum simple non-intrusive helper client interface for a user’s
script. Oríon is agnostic to computation infrastructures and can be used seamlessly in both
traditional HPC infrastructure (i.e. Slurm) or modern containerized environments (Kubernetes).
Oríon is also agnostic to underlying deep learning frameworks and therefore natively supports all
of them.
