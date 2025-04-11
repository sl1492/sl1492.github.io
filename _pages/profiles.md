---
layout: page
permalink: /research/
title: 📊 Research Experiences
description: "Academic and applied research projects I've conducted in statistics and data science."
nav: true
nav_order: 7
---

<!-- Embedded CSS for styling research cards -->
<style>
.research-card {
  border: 1px solid #ddd;
  border-radius: 12px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  background-color: white;
}

.research-header {
  display: flex;
  flex-direction: column;
  gap: 0.3rem;
}

.research-header h3 {
  margin: 0;
}

.research-meta {
  font-size: 0.95rem;
  color: #666;
  margin-bottom: 0.5rem;
}

.research-body ul {
  padding-left: 1.2rem;
  margin-top: 0.5rem;
}
</style>


<div class="research-card">
  <div class="research-header">
    <h3> <strong>Length Bias Estimation of Small Businesses Lifetime</strong></h3>
    <em>Mathematical Economics Honor Thesis</em>
    <div class="research-meta">📅 Sept 2022 – Apr 2023</div>
  </div>
  <div class="research-body">
    <ul>
      <li>Conducted in-depth analysis of lifetime data for 24 restaurants on Carytown Commercial Street using advanced statistical techniques to estimate average lifespan while minimizing impacts of length bias and right-censoring.</li>
      <li>Implemented Kaplan-Meier estimators to account for right-censored observations and conducted rigorous goodness-of-fit tests.</li>
      <li>Validated the developed estimator against the exponential distribution, resulting in precise estimates devoid of length bias.</li>
    </ul>
  </div>
</div>

<div class="research-card">
  <div class="research-header">
    <h3> <strong>Analyzing the Statistical Effectiveness of Diagnostic Tests for COVID-19 Using the ROC Curve</strong></h3>
    <em>Summer Research Fellowship</em>
    <div class="research-meta">📅 May 2022 – Aug 2022</div>
  </div>
  <div class="research-body">
    <ul>
      <li>Developed a preliminary ROC curve using patient age as a threshold on a COVID hospitalization dataset, achieving an AUC-ROC of 0.81.</li>
      <li>Constructed multivariate logistic regression models incorporating age, comorbidities, and vital statistics to improve survival prediction accuracy (AUC improved to 0.86).</li>
      <li>Evaluated trade-offs between sensitivity and specificity to optimize decision thresholds under limited medical resource conditions.</li>
    </ul>
  </div>
</div>
