---
title: 'Spatially explicit machine learning for assessing equality in urban green space accessibility'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shawn W. Laffan 
  - Graciela Metternicht


date: '2025-08-29T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *GIScience 2025 Conference*
publication_short: In *GIScience 2025*

abstract: Urban green spaces (UGS) offer multiple benefits to residents, including improved air quality, heat mitigation, and enhanced opportunities for exercise. For urban planners, aside from providing sufficient UGS, ensuring equitable access to these spaces is crucial for promoting environmental justice in cities. This study uses spatially explicit machine learning methods to help planners understand how socio-economic development affects equitable access to UGS and to predict the levels of equality. We investigate the potential driving factors behind UGS equality within the Taipei metropolis from 2019 to 2023. The Gini coefficient is utilised to assess equality levels of UGS access at the village level ("Li" in the local language, representing the smallest administrative unit). Spatial lagged variables are integrated into tree-based boosting models to reflect various spatial econometric specifications, allowing comparison of their performance with traditional spatial and non-spatial regression models. SHapley Additive exPlanations (SHAP) are applied to identify feature importance and explore non-linear relationships between socio-economic indicators and the calculated Gini coefficients. Results indicate that machine learning algorithms outperform traditional spatial statistical models. Furthermore, incorporating spatial lagged variables into machine learning models enhances their predictive accuracy compared to models lacking spatial consideration. The findings inform urban planners about spatial disparities in green space distribution, highlighting the need for location-specific interventions. This research supports inclusive urban green space development in Taipei, aligning with the Sustainable Development Goals, particularly target 11.7, which emphasises providing universal access to safe, inclusive, and accessible green spaces.

# Summary. An optional shortened abstract.
summary: This study applies spatial machine learning to assess and predict inequality in urban green space access across Taipei (2019–2023). Incorporating spatial lag variables improves model accuracy and reveals key socio-economic drivers, supporting equitable and sustainable urban planning aligned with SDG 11.7.

tags:
  - Spatially explicit machine learning

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Zih-Hong Lin**]'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

