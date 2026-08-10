---
layout: page
title: Projects
permalink: /projects/
description: Selected portfolio case studies in AI systems, machine learning, and applied statistics.
nav: true
nav_order: 2
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<p class="page-intro">These case studies highlight applied work in AI systems, multimodal modeling, and statistical machine learning.</p>

<div class="project-grid">
  <article class="project-card">
    <h3>Production LLM System for Healthcare Navigation</h3>
    <h4>Overview</h4>
    <p>A production AI application supporting healthcare service navigation and AI safety at Fraser Health.</p>
    <h4>Methodology</h4>
    <p>Built decision-support pipelines that combine deterministic models with LLM reasoning. The delivery workflow uses Python, Azure Machine Learning, offline evaluation, statistical analysis, and product-defined KPIs.</p>
    <h4>Results or impact</h4>
    <p>Deployed as a real-world healthcare application with an emphasis on routing quality, operational efficiency, and responsible AI safeguards. Confidential implementation details are intentionally omitted.</p>
  </article>

  <article class="project-card">
    <h3>Multimodal Deep Learning for Competing-Risks Survival Prediction</h3>
    <h4>Overview</h4>
    <p>A deep survival framework for continuous-time prediction in settings with multiple competing risks.</p>
    <h4>Methodology</h4>
    <p>Integrated electronic health records, ICU clinical notes, and longitudinal functional data using language-model embeddings, self-attention, and B-spline basis functions.</p>
    <h4>Results or impact</h4>
    <p>Extended deep competing-risks modeling beyond conventional discrete-time outputs to continuous survival probability prediction.</p>
  </article>

  <article class="project-card">
    <h3>Transformer-Based Credit Risk Assessment</h3>
    <h4>Overview</h4>
    <p>An NLP framework for predicting credit-risk ratings from override documents and structured financial information.</p>
    <h4>Methodology</h4>
    <p>Combined BERT contextual embeddings with structured financial features and Lasso-based feature selection.</p>
    <h4>Results or impact</h4>
    <p>Achieved over 90% prediction accuracy in the research evaluation described in the CV, supporting more consistent credit-risk assessment.</p>
  </article>

  <article class="project-card">
    <h3>Maternal–Infant Weight Modeling Using Functional Regression</h3>
    <h4>Overview</h4>
    <p>A statistical model for predicting newborn weight from maternal BMI trajectories observed over irregular time domains.</p>
    <h4>Methodology</h4>
    <p>Used kernel-weighted estimation and B-spline basis expansions, then translated the model into an interactive R Shiny application.</p>
    <h4>Results or impact</h4>
    <p>Produced interpretable trajectory-level insights for pregnancy weight management and maternal healthcare decision support.</p>
  </article>
</div>
