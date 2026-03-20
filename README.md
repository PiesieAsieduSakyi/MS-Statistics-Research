# MS-Statistics-Research
This is the Non-Thesis Research I conducted in partial fulfillment of my MS Statistics &amp; Data Science Degree from the The University of Texas at El Paso
Below is a **brief, clean, and “catchy” README-style summary** tailored to an **MS Statistics thesis repository**. It balances technical credibility with accessibility and highlights the Bayesian contribution without overwhelming the reader.



## Mandatory COVID‑19 Vaccination Statuses Across the Eight U.S. Regions

### A Bayesian Random Effects Analysis of Selected Socioeconomic Factors

### Thesis Overview

This thesis presents a **Bayesian hierarchical analysis** of mandatory COVID‑19 vaccination statuses across all **eight regions of the United States**, with a focus on understanding how key socioeconomic factors shape vaccination outcomes. By explicitly modeling regional heterogeneity, the study provides a statistically principled framework for evaluating both **individual-level characteristics** and **region-specific effects** in a nationwide public health context.

### Data and Variables

Let

$$
\boldsymbol{y} = (y_1, y_2, \ldots, y_n)'
$$

denote a binary response vector indicating mandatory COVID‑19 vaccination status for individuals sampled across the United States.

The vector of covariates $$\boldsymbol{x}$$ consists of selected socioeconomic predictors:

*   **Gender** (2 categories)
*   **Education level** (4 categories)
*   **Income level** (3 categories)

These predictors were chosen to reflect well-documented structural and socioeconomic contributors to vaccination behavior, while allowing for parsimonious modeling within a Bayesian framework.

### Modeling Strategy

To assess how assumptions about regional structure influence inference, three distinct Bayesian model specifications were considered:

1.  **Homogeneous Effects Model**
    *   Assumes a common set of covariate effects for all individuals nationwide.
    *   Serves as a baseline model, ignoring regional variation.

2.  **Random Intercept / Common Covariate Effects Model**
    *   Allows outcomes to vary by region through random effects, while keeping covariate effects fixed across regions.
    *   Captures unobserved regional heterogeneity without over-parameterization.

3.  **Region-Specific Covariate Effects Model**
    *   Allows covariate effects to remain constant within regions but vary across regions.
    *   Provides the most flexible structure, enabling differential socioeconomic impacts by region.

### Bayesian Framework

A Bayesian random effects approach was adopted to:

*   Account for hierarchical data structure induced by regions
*   Quantify uncertainty through posterior distributions rather than point estimates
*   Borrow strength across regions via partial pooling

This framework is particularly well-suited for policy-relevant inference, where uncertainty quantification is as important as effect estimation.

### Key Contribution

The thesis demonstrates how **Bayesian hierarchical modeling** can be used to disentangle national versus regional drivers of mandatory vaccination outcomes. By comparing increasingly flexible model structures, the analysis highlights the importance of accounting for geographic variation when evaluating public health mandates tied to socioeconomic conditions.

### Significance

This work contributes to applied Bayesian statistics and public health analytics by offering:

*   A principled comparison of hierarchical model assumptions
*   Statistically interpretable insights into vaccination disparities
*   A reusable modeling blueprint for future studies of regional health policy outcomes

***

If you want, I can:

*   Tighten this further into a **GitHub landing README**
*   Make it more **policy-facing** for non-statistical audiences
*   Add a **methods-at-a-glance box** (priors, likelihood, inference strategy)
*   Rewrite it for inclusion in a **thesis appendix or abstract companion**

Just say the word.
