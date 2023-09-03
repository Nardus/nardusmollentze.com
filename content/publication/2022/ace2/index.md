---
title: "Variation in the ACE2 receptor has limited utility for SARS-CoV-2 host prediction"
authors:
- Nardus Mollentze
- Deborah Keen
- Uuriintuya Munkhbayar
- Roman Biek
- Daniel Streicker
date: "2022-11-23"
doi: "10.7554/eLife.80329"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*eLife*, 11: e80329"
publication_short: "eLife"

abstract: "Transmission of SARS-CoV-2 from humans to other species threatens wildlife conservation and may create novel sources of viral diversity for future zoonotic transmission. A variety of computational heuristics have been developed to pre-emptively identify susceptible host species based on variation in the angiotensin-converting enzyme 2 (ACE2) receptor used for viral entry. However, the predictive performance of these heuristics remains unknown. Using a newly compiled database of 96 species, we show that, while variation in ACE2 can be used by machine learning models to accurately predict animal susceptibility to sarbecoviruses (accuracy = 80.2%, binomial confidence interval [CI]: 70.8–87.6%), the sites informing predictions have no known involvement in virus binding and instead recapitulate host phylogeny. Models trained on host phylogeny alone performed equally well (accuracy = 84.4%, CI: 75.5–91.0%) and at a level equivalent to retrospective assessments of accuracy for previously published models. These results suggest that the predictive power of ACE2-based models derives from strong correlations with host phylogeny rather than processes which can be mechanistically linked to infection biology. Further, biased availability of ACE2 sequences misleads projections of the number and geographic distribution of at-risk species. Models based on host phylogeny reduce this bias, but identify a very large number of susceptible species, implying that model predictions must be combined with local knowledge of exposure risk to practically guide surveillance. Identifying barriers to viral infection or onward transmission beyond receptor binding and incorporating data which are independent of host phylogeny will be necessary to manage the ongoing risk of establishment of novel animal reservoirs of SARS-CoV-2.


See also: [eLife Digest.](https://elifesciences.org/articles/80329#digest)"

# Summary. An optional shortened abstract.
summary: A large number of publications have shown suprisingly accurate predictions of which species are susceptible to SARS-CoV-2 infection using just the variation in ACE2 proteins found in different species. This would seem to imply that receptor-binding is the primary barrier to cross-species transmission for this virus. However, we show that the predictive power of ACE2-based models derives from strong correlations with host phylogeny rather than processes which can be mechanistically linked to infection biology. Further, biased availability of ACE2 sequences leads to misleading projections of the number and geographic distribution of at-risk species. Models based on host phylogeny reduce this bias, but identify a very large number of susceptible species, implying that model predictions must be combined with local knowledge of exposure risk to practically guide surveillance.

tags:
- SARS-CoV-2
- cross-species transmission


featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://elifesciences.org/articles/80329.pdf
url_code: https://github.com/nardus/ace2
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Spatial distribution of wild mammals predicted as susceptible to sarbecoviruses"
  focal_point: ""
  preview_only: true

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

{{< altmetric "10.7554/eLife.80329" >}}