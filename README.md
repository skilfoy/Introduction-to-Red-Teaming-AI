# Introduction to Red Teaming AI

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-AI%20Red%20Teamer-success.svg)](https://academy.hackthebox.com/)

**Author:** Sean Kilfoy  
**Companion to:** [Hack The Box Academy: Introduction to Red Teaming AI](https://academy.hackthebox.com/app/module/294)

## Project overview

This repository presents a portfolio-ready technical writeup for the Hack The Box Introduction to Red Teaming AI module. The notebook combines the supplied lab workflow with professional data-engineering documentation, model-security analysis, experiment interpretation, and a reproducible triggered-data-poisoning assessment.

The work examines the attack surface of ML-based and generative-AI systems across model behavior, training data, text generation, model components, data components, application components, and system components. Each stage records the operational purpose, the observed evidence, the security interpretation, and the relationship to the final assessment.

## Assessment coverage

1. Red-team scope, system context, and reproducibility
2. Model manipulation and inference-time behavior
3. LLM OWASP Top 10 and text-generation attack surfaces
4. Google’s Secure AI Framework (SAIF)
5. Model, data, application, and system component attacks
6. Triggered data poisoning and model validation

## Repository artifacts

- [Interactive Jupyter notebook](./Introduction%20to%20Red%20Teaming%20AI.ipynb)
- [Compiled technical PDF report](./Introduction%20to%20Red%20Teaming%20AI.pdf)
- [Matching GitHub Gist](https://gist.github.com/skilfoy/800ddaff92e0f7c01001300bcbe48118)

## Reproducibility

The notebook documents the local HTB lab workflow and the files used during the exercises. Lab datasets, helper scripts, model artifacts, credentials, and target-instance materials remain outside this repository. Reproduce the work in an isolated environment using the corresponding HTB Academy module and its supplied lab files.

The exported PDF was generated from the cleaned notebook with manual section numbering preserved. Existing code, recorded outputs, execution counts, and author metadata remain part of the published notebook artifact.

## Source and acknowledgments

- [Hack The Box Academy: Introduction to Red Teaming AI](https://academy.hackthebox.com/app/module/294)
- [AI Red Teamer path](https://academy.hackthebox.com/app/paths/418/path-progress)
