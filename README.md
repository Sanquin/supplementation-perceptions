# Knowledge, Confidence, and Willingness to Take Iron Supplementation Among Blood Donors Across Multiple Countries

**Collaborators:** BEST Collaborative, The Netherlands (Sanquin), Finland (Finnish Red Cross Blood Service), Sweden (Västerbotten region), Japan (Japanese Red Cross Tokyo Region), Germany	(Greifswald region, Northeast Germany), The United States (American Red Cross)

This repository contains the code and analysis for evaluating knowledge and confidence of knowledge and it's effect on willingness to take iron supplements in different donor populations.

---

## Abstract

Frequent blood donation can deplete iron stores, increasing the risk of iron deficiency anemia. Post-donation iron supplements may help preserve donor health, but willingness to take supplements likely depends on donor knowledge and confidence. We conducted a cross-sectional survey among 5,691 whole blood donors from six countries (Netherlands, USA, Japan, Finland, Sweden, Germany). Knowledge was assessed using 16 true-or-false statements on four blood donation-related topics; confidence by asking if donors were "certain" or "guessing". Willingness to take supplements was assessed using three scenarios: to continue donating, when advised by a donor physician, and general iron supplementation rejection. Using logistic regressions, we assessed associations between knowledge, confidence, and willingness to take iron supplements for each scenario, adjusted for sex, age, country, prior supplement use, and trust in the blood service. Most donors exhibited medium to high knowledge and underconfidence in that knowledge. Willingness to take supplements was high (80.6–84.2% across scenarios). Knowledge and confidence were not consistently associated with willingness to take supplements. In contrast, trust in the blood service (OR = 1.64, p < .001) and prior supplement use (OR = 1.87, p < .001) were strongly associated with willingness when supplements were required to continue donating, with similar effects across other scenarios. Willingness varied across countries, with higher willingness in Nordic countries. These findings suggest that trust-building approaches may be more promising than education-focused strategies, though causal relationships require further research. High acceptance rates suggest that post-donation iron supplementation may be a feasible strategy for donor iron management.

## Repository layout and running order
Analyses are implemented as numbered R scripts. 
- 1_data.Rmd: loads the specified data
- 2_descriptives.Rmd: creates descriptive statistics for the data
- 3_assumptions.Rmd: tests regression assumptions
- 4_models.Rmd: specifies and saves the models
- 5_barchart.Rmd: creates the barcharts of the manuscript and supplementary materials
- 6_forestplot.Rmd: creates the forestplots of the manuscript and supplementary materials
- 7_countryspecific.Rmd: country specific analyses

## Data availability
Data availability should be discussed with the corresponding author of the manuscript (to be added to this repository after publication).