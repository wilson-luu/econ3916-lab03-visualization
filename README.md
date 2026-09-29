# Honest vs. Misleading Visualizations
## Objective
To rigorously evaluate data visualization ethics and methodologies by quantifying visual distortions, exposing the limitations of pure summary statistics, and applying systematic exploratory data analysis to macroeconomic datasets.
## Methodology
- Statistical Reconstruction: Recreated Anscombe's Quartet to demonstrate how datasets with identical mathematical properties (means, variances, and correlations) can exhibit fundamentally different structural realities when visualized.
- Distortion Quantification: Calculated a Lie Factor of 49.0 for a misleading, truncated-axis revenue chart (which visually inflated a 4% actual effect into a 200% perceived effect) and redesigned it into an honest zero-baseline dot plot.
- Narrative Framings: Engineered four distinct visual interpretations—honest baseline, truncated y-axis, cherry-picked time window, and log-scaled—of the exact same real average hourly earnings time series (FRED: AHETPI) to prove how formatting alters economic conclusions.
- Systematic EDA: Executed a comprehensive four-step exploratory data analysis framework (evaluating structure, distributions, relationships, and anomalies) on a global World Bank GDP panel dataset encompassing 262 economies over 63 years.
- Interactive Tooling: Developed an interactive chart toggler running a live Lie Factor readout to dynamically demonstrate how axis manipulation instantly impacts data integrity.
## Key Findings
- The Peril of Blind Aggregation: Anscombe's Quartet decisively proves that relying purely on summary metrics while ignoring data visualization obscures critical non-linear relationships and outliers.
- Quantifiable Manipulation: Manipulating the y-axis floor in bar charts breaks the data-to-ink ratio, generating massive Lie Factors that completely misrepresent modest economic realities to stakeholders.
- Rhetorical Flexibility: A single macroeconomic dataset can simultaneously "prove" that wages are flat, surging, or collapsing, simply by adjusting the observation window or axis scale.
- MNAR Vulnerabilities: The EDA process revealed that raw global economic data is deeply right-skewed and riddled with Missing Not At Random (MNAR) gaps, which structurally bias datasets if not properly log-transformed and contextually understood.
