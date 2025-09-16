---
title: "Using a Database to Support Interactive Multiobjective Optimization, Visualization, and Analysis"
date: 2023-06-18 00:01:00 +0800
selected: false
pub: "Proceedings of the Genetic and Evolutionary Computation Conference (GECCO)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
#pub_last: ' <span class="badge badge-pill badge-publication badge-success">Best paper award</span>'
pub_date: "2023"
semantic_scholar_id: 97bfa00ae41d0f6cacb6178806bc7a15e14af21a # use this to retrieve citation count
abstract: >-
  Many libraries of open-source implementations of multiobjective optimization problems (MOPs) and evolutionary algorithms (MOEAs) have been developed in recent years. These libraries enable researchers to solve their MOPs using diverse MOEAs. Some libraries also implement interactive MOEAs, which enable decision-makers (experts in the domain of the MOP) to provide their preferences and guide the optimization process toward their region of interest. These libraries also provide access to visualization methods and benchmarking tools. However, they do not currently implement a database to store and utilize the data generated while running MOEAs.
  We propose the creation of SIVA DB, a database designed to be easily incorporated into existing libraries as a modular addition. SIVA DB provides a standard way to archive an MOEA's population and the metadata associated with each population member. Such metadata can include, e.g., the parameters and state of the MOEA and the preferences the decision-maker gives (in the case of interactive MOEAs). The database can store data from multiple runs of any number of MOEAs, and even data from different MOPs. SIVA DB provides easy access to the contained data to analyze the optimization process or create efficient MOEAs. We demonstrate the latter in this paper with experiments.
#cover: /assets/images/covers/cover3.jpg
authors:
  - Bhupinder Saini
  - Giomara Larraga
  - Kaisa Miettinen
links:
  Link: https://dl.acm.org/doi/abs/10.1145/3583133.3596383
---
