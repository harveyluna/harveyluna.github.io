---
layout: page
title: Abalone Case Study
description: Data science project demonstrating exploratory analysis, interactive visualization, and RAG implementation
img: assets/projects/abalone-rag/plots/abalone_banner.jpg
importance: 1
category: work
related_publications: false
---

## Executive Summary

This project leverages the UCI Abalone Dataset to demonstrate various data science competencies. The initiative encompasses exploratory data analysis, an interactive R Shiny application, and a retrieval-augmented generation (RAG) system focused on abalone research.

## Key Deliverables

### RAG Application
Implemented cutting-edge methodology (2025) with comprehensive documentation in a Jupyter notebook explaining the development process. This retrieval-augmented generation system enables advanced querying and analysis of abalone research data.

[View RAG Development Notebook]({{ site.baseurl }}/assets/projects/abalone-rag/build_abalone_RAG_app.ipynb){:target="_blank"}

### R Shiny Application
Developed an interactive tool enabling users to examine how different variables are distributed across the dataset. The application provides dynamic visualizations and exploration capabilities for the abalone data.

### Research Presentation
Presented findings through a comprehensive Canva presentation titled "Abalone Case Study," showcasing the project's methodology, results, and insights.

## Research Findings

The exploratory data analysis informed the development of a predictive model for estimating abalone age. A Lasso Regularization model emerged as the top performer with the following metrics:

- **Mean Absolute Error**: 1.35 years
- **Mean Absolute Percentage Error**: 12.74%
- **Root Mean Square Error**: 2.02
- **R² Score**: 0.62

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/abalone-rag/plots/correlogram.png" title="Feature Correlations" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/abalone-rag/plots/analysis_of_residuals.png" title="Residual Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Correlation analysis of abalone features. Right: Residual analysis of the predictive model.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/abalone-rag/plots/distribution_of_size.png" title="Size Distribution" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/abalone-rag/plots/distribution_of_weight.png" title="Weight Distribution" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Distribution analysis of abalone size and weight measurements across the dataset.
</div>

## Methodology

The analysis was conducted in R, with complete results documented in an accompanying analysis PDF. The project demonstrates proficiency in:

- Exploratory data analysis
- Statistical modeling and validation
- Interactive web application development
- Modern RAG implementation
- Data visualization and communication

## Project Resources

- [Complete Analysis Report (PDF)]({{ site.baseurl }}/assets/projects/abalone-rag/analysis.pdf){:target="_blank"}
- [RAG Development Notebook]({{ site.baseurl }}/assets/projects/abalone-rag/build_abalone_RAG_app.ipynb){:target="_blank"}
- [Project Documentation](https://lone-wolfgang.github.io/abalone-rag/){:target="_blank"}
- [Interactive Demo](https://lone-wolfgang.github.io/abalone-rag/#executive-summary){:target="_blank"}
