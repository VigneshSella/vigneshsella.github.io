---
layout: post
title: Automating Scientific Knowledge Extraction and Modeling (ASKEM)
categories: [projects, miscellaneous]
excerpt: DARPA’s Automating Scientific Knowledge Extraction and Modeling (ASKEM) program uses AI approaches and tools to create, sustain, and enhance complex models and simulators.
---

The over-arching goal of this [project](https://www.darpa.mil/program/automating-scientific-knowledge-extraction-and-modeling) was to produce a software which could "enable experts to maintain, reuse, and adapt large collections of heterogeneous data, knowledge and models – with traceability across knowledge sources, model assumptions, and model fitness." My team and I were specifically responsible for the development and testing of the Python backend for the software, named [PyCIEMSS](https://github.com/ciemss/pyciemss). I created many of the testing scripts and notebooks to explore and verify the functionality of the PyCIEMSS codebase using ODE-based climate and COVID-19 epidemiology models.

An example Jupyter notebook using various interfaces provided by the PyCIEMSS library can be seen below. Typically, however, the PyCIEMSS library will be called in the back end and is not exposed to the user in this manner. There is instead a GUI which that the user interacts with to run the models and simulations, which can be found [here](https://app.terarium.ai/).


<iframe src="/assets/notebooks/ASKEM_example_notebook.html" width="100%" height="800px"></iframe>
