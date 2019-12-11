---
title: "Kleiṓ: Experiment management for machine learning"
excerpt: "Kleiṓ is an experiment manager, a logging journal of all data describing your experiments. Its purpose is to provide an automatic tool to log extensive environment information, including script's code version, system specification and script configuration."
collection: projects
---

<b>Source code</b> [github.com/Epistimio/kleio](https://github.com/Epistimio/kleio)

This project is still a prototype. There is little documentation and no testing.
{: .notice}
This project is paused for now while we work on [Track](/projects/3-track) for a first release.
{: .notice}

Kleiṓ is an experiment manager, a logging journal of all data describing your experiments.

Its purpose is to provide an automatic tool to log extensive environment information, including a
script’s code version, system specification, and script configuration. The logging journal can
include statistics manually logged from within the user’s script as well as artifacts and resources.

It assumes the computation is entirely deterministic, and if not deterministic, then such that one
of the arguments is a seed that makes it fully reproducible.

The most distinctive feature of Kleiṓ is its inner data structure, which is based on the concept of
[concept of event sourcing](https://martinfowler.com/eaaDev/EventSourcing.html). This makes it
possible to fork experiments at arbitrary timestamps and build trees of alternative paths. For
machine learning, this can be thought of as changing the learning rate to different values at a
given epoch m without starting from scratch. Kleiṓ will then provide a unified view of all
experiments, showing logs as if all the experiments were executed from epochs 1 to m.  The same
applies for any other changes at the resumption of execution, such as the compute node or code
version.
