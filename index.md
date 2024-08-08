---
title: Overview
layout: home
nav_order: 1
---

# Open Accelerated Discovery

**Opensource Toolkits for Molecular Science**

[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/openad)](https://pypi.org/project/openad/)
[![PyPI version](https://img.shields.io/pypi/v/openad)](https://pypi.org/project/openad/)
[![License MIT](https://img.shields.io/github/license/acceleratedscience/open-ad-toolkit)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

<!-- [![Docs](https://img.shields.io/badge/website-live-brightgreen)](https://github.com/acceleratedscience/open-ad-toolkit) -->

![Landing](assets/screenshot-landing.png)

OpenAD is an open-source framework for molecular and materials discovery developed by IBM Research.

The OpenAD client is accessible from a command line interface, Jupyter Notebooks and an API. It provides unified access to a variety of tools and AI models for literature knowledge extraction, synthesis prediction (forward and retro-), generative methods and property inference. You can train models on your own data as well as visualize and filter candidate molecules.

## Toolkits

The OpenAD Beta integrates with the following IBM Research [toolkits]({% link base-concepts.md %}#toolkits):

- ### [DS4SD](https://ds4sd.github.io/)

  _Deep Search for Scientific Discovery_<br>
  Connecting & ingesting unstructured data<br>
  [DS4SD Docs](https://ds4sd.github.io/deepsearch-toolkit/)
  {: .no-gap }
  <details markdown="block">
  <summary>More</summary>
  <div>
      <p>The Deep Search toolkit uses AI to convert unstructured PDF documents into structured JSON files and enables you to automate knowledge extraction.</p>
      <p>You can use it for both public and proprietary documents.</p>
  </div>
  </details>

- ### [RXN](https://rxn.res.ibm.com/)

  Computational Chemistry<br>
  [RXN Video tutorials](https://rxn.app.accelerate.science/rxn/learn) (account required)
  {: .no-gap }
  <details markdown="block">
  <summary>More</summary>
  <div>
      <p>The Reaction toolkit uses AI to predict chemical reactions, retrosynthesis pathways and experimental procedures.</p>
      <p>You can train AI models to build intelligence in your specific chemistry domain, and scale your analysis and model training while securing your data using features of the Discovery Platform.</p>
  </div>
  </details>

- ### [GT4SD](https://github.com/GT4SD/gt4sd-core)

  <span class="mini-label">Coming soon</span><br>
  _Generative Toolkit for Scientific Discovery_<br>
  Molecular modeling & inferences
  {: .no-gap }
  <details markdown="block">
  <summary>More</summary>
  <div>
      The Generative Toolkit accelerates hypothesis generation in the scientific discovery process. It provides a library for making state-of-the-art generative AI models easier to use.
  </div>
  </details>

- ### [ST4SD](https://st4sd.github.io/overview/)

  <span class="mini-label">Coming soon</span><br>
  _Simulation Toolkit for Scientific Discovery_<br>
  Virtual Experiments
  {: .no-gap }
  <details markdown="block">
  <summary>More</summary>
  <div>
      <p>The Simulation Toolkit simplifies the development, execution and dissemination of virtual experiments.</p>
      <p>A virtual experiment is an application workflow which measures one or more characteristics of one or more input systems. It is the computational analog of a lab experiment.</p>
  </div>
  </details>
