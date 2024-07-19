---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Probabilistic forecasting of anti-VEGF treatment frequency in neovascular age-related
  macular degeneration
subtitle: ''
summary: ''
authors:
- Maximilian Pfau
- Soumya Sahu
- Rawan Allozi Rupnow
- Kathleen Romond
- Desiree Millet
- Frank G Holz
- Steffen Schmitz-Valckenberg
- Monika Fleckenstein
- Jennifer I Lim
- Luis de Sisternes
- Theodore Leng
- Daniel L Rubin
- Joelle A Hallak
tags: []
categories: []
date: '2021-06-01'
lastmod: 2024-07-19T23:41:33+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-07-19T21:41:32.844812Z'
publication_types:
- '2'
abstract: 'Purpose: To probabilistically forecast needed anti-vascular endothelial
  growth factor (anti-VEGF) treatment frequency using volumetric spectral domain-optical
  coherence tomography (SD-OCT) biomarkers in neovascular age-related macular degeneration
  from real-world settings. Methods: SD-OCT volume scans were segmented with a custom
  deep-learning-based analysis pipeline. Retinal thickness and reflectivity values
  were extracted for the central and the four inner Early Treatment Diabetic Retinopathy
  Study (ETDRS) subfields for six retinal layers (inner retina, outer nuclear layer,
  inner segments [IS], outer segments [OS], retinal pigment epithelium-drusen complex
  [RPEDC] and the choroid). Machine-learning models were probed to predict the anti-VEGF
  treatment frequency within the next 12 months. Probabilistic forecasting was performed
  using natural gradient boosting (NGBoost), which outputs a full probability distribution.
  The mean absolute error (MAE) between the predicted versus actual anti-VEGF treatment
  frequency was the primary outcome measure. Results: In a total of 138 visits of
  99 eyes with neovascular AMD (96 patients) from two clinical centers, the prediction
  of future anti-VEGF treatment frequency was observed with an accuracy (MAE [95%
  confidence interval]) of 2.60 injections/year [2.25-2.96] (R2 = 0.390) using random
  forest regression and 2.66 injections/year [2.31-3.01] (R2 = 0.094) using NGBoost,
  respectively. Prediction intervals were well calibrated and reflected the true uncertainty
  of NGBoost-based predictions. Standard deviation of RPEDC-thickness in the central
  ETDRS-subfield constituted an important predictor across models. Conclusions: The
  proposed, fully automated pipeline enables probabilistic forecasting of future anti-VEGF
  treatment frequency in real-world settings. Translational Relevance: Prediction
  of a probability distribution allows the physician to inspect the underlying uncertainty.
  Predictive uncertainty estimates are essential to highlight cases where human-inspection
  and/or reversion to a fallback alternative is warranted.'
publication: '*Transl. Vis. Sci. Technol.*'
---
