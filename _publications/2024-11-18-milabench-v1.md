---
title: "Introducing Milabench: Benchmarking Accelerators for AI"
collection: publications
permalink: /publication/2024-11-18-milabench-v1
excerpt: 'Add excerpt...'
month: november
year: 2024
date: 2024-11-18
venue: 'arXiv preprint arXiv:2411.11940'
authors: Pierre Delaunay, Xavier Bouthillier, Olivier Breuleux, Satya Ortiz-Gagné, Olexa Bilaniuk, Fabrice Normandin, Arnaud Bergeron, Bruno Carrez, Guillaume Alain, Soline Blanc, Frédéric Osterrath, Joseph Viviano, Roger Creus-Castanyer Darshan Patil, Rabiul Awal, Le Zhang
paperurl: 'https://arxiv.org/abs/2411.11940'
citation: ''
---

AI workloads, particularly those driven by deep learning, are introducing novel
usage patterns to high-performance computing (HPC) systems that are not
comprehensively captured by standard HPC benchmarks. As one of the largest
academic research centers dedicated to deep learning, Mila identified the need
to develop a custom benchmarking suite to address the diverse requirements of
its community, which consists of over 1,000 researchers. This report introduces
Milabench, the resulting benchmarking suite. Its design was informed by an
extensive literature review encompassing 867 papers, as well as surveys
conducted with Mila researchers. This rigorous process led to the selection of
26 primary benchmarks tailored for procurement evaluations, alongside 16
optional benchmarks for in-depth analysis. We detail the design methodology, the
structure of the benchmarking suite, and provide performance evaluations using
GPUs from NVIDIA, AMD, and Intel. The Milabench suite is open source and can be
accessed at this http [URL](https://github.com/mila-iqia/milabench).

BibTeX:

    @article{delaunay2024milabench,
      title={Introducing Milabench: Benchmarking Accelerators for AI},
      author={Delaunay, Pierre and Bouthillier, Xavier and Breuleux, Olivier and Ortiz-Gagn{\'e}, Satya and Bilaniuk, Olexa and Normandin, Fabrice and Bergeron, Arnaud and Carrez, Bruno and Alain, Guillaume and Blanc, Soline and others},
      journal={arXiv preprint arXiv:2411.11940},
      year={2024}
    }