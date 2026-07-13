<h1 align="center">Hi, I'm Fuji</h1>

<p align="center">
  AI Research · Large Language Models · NLP · AI for Software Engineering
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-AI%20for%20Software%20Engineering-6f42c1" alt="AI for Software Engineering">
  <img src="https://img.shields.io/badge/Research-Reproducible%20Evaluation-2ea44f" alt="Reproducible evaluation">
  <img src="https://img.shields.io/badge/Language-Python-3776AB?logo=python&logoColor=white" alt="Python">
</p>

## About Me

I work on large-language-model systems across natural language processing and software engineering. My research at Chongqing University focuses on prompt-guided data augmentation, low-resource learning, repository-level code generation, and rigorous model evaluation.

I care about rigorous experiments, transparent evaluation, and engineering systems that turn model capabilities into reliable developer tools.

## Research Interests

- Large language models for software engineering
- Prompt tuning and LLM-guided data augmentation
- Low-resource NLP and fake-news detection
- Repository-level code generation and completion
- Code quality, correctness, and risk evaluation
- Retrieval-augmented generation and coding agents
- Reproducible machine learning systems

## Featured Research

### [SharP: Soft and Hard Prompt-Guided Augmentation with LLM](https://github.com/Fujizzz/SharP)

My primary research-code release for low-resource fake-news detection. SharP combines a learnable soft prompt, a structured hard prompt, uncertainty-based active selection, and detector feedback to generate useful samples near the classifier decision boundary.

**Methods:** soft prompting, hard prompting, active learning, and LLM data augmentation<br>
**Benchmarks:** PHEME, LIAR, and Twitter15/16<br>
**Artifact:** source code, experiment variants, architecture figures, paper, citation metadata, and automated code checks

### [Multidimensional Comparative Evaluation of Human-Written and LLM-Generated Code](https://github.com/Fujizzz/Multidimensional-Comparative-Evaluation-of-Human-Written-and-LLM-Generated-Code)

A reproducible research artifact comparing human-written code with five LLM-based generation approaches on 3,655 RepoEval tasks. The project includes generation pipelines, nine primary evaluation metrics, per-sample outputs, aggregate results, and automated artifact verification.

**Methods:** DeepSeek-Coder, Qwen2.5-Coder, DeepSeek API, Repoformer, and mini-swe-agent  
**Tasks:** Function, Line, and API completion  
**Focus:** correctness, executability, engineering quality, contextual coherence, and risk exposure

## Technical Toolkit

`Python` · `PyTorch` · `Transformers` · `vLLM` · `LLM APIs` · `Git` · `Linux` · `Experiment Design` · `Data Analysis`

## Engineering Principles

- Make experiments reproducible and results independently verifiable.
- Treat evaluation quality as part of the system, not an afterthought.
- Keep credentials, model artifacts, and third-party code out of source control.
- Prefer clear documentation and small, auditable workflows.
