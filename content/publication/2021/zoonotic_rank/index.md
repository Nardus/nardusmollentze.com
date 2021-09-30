---
title: "Identifying and prioritizing potential human-infecting viruses from their genome sequences"
authors:
- Nardus Mollentze
- Simon Babayan
- Daniel Streicker
date: "2021-09-28"
doi: "10.1371/journal.pbio.3001390"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLOS Biology, 19(9): e3001390"
publication_short: "PLOS Biology"

abstract: "Determining which animal viruses may be capable of infecting humans is currently intractable at the time of their discovery, precluding prioritization of high-risk viruses for early investigation and outbreak preparedness. Given the increasing use of genomics in virus discovery and the otherwise sparse knowledge of the biology of newly-discovered viruses, we developed machine learning models that identify candidate zoonoses solely using signatures of host range encoded in viral genomes. Within a dataset of 861 viral species with known zoonotic status, our approach outperformed models based on the phylogenetic relatedness of viruses to known human-infecting viruses (AUC = 0.773), distinguishing high-risk viruses within families that contain a minority of human-infecting species and identifying putatively undetected or so far unrealized zoonoses. Analyses of the underpinnings of model predictions suggested the existence of generalisable features of viral genomes that are independent of virus taxonomic relationships and that may preadapt viruses to infect humans. Our model reduced a second set of 645 animal-associated viruses that were excluded from training to 272 high and 41 very high-risk candidate zoonoses and showed significantly elevated predicted zoonotic risk in viruses from non-human primates, but not other mammalian or avian host groups. A second application showed that our models could have identified SARS-CoV-2 as a relatively high-risk coronavirus strain and that this prediction required no prior knowledge of zoonotic SARS-related coronaviruses. Genome-based zoonotic risk assessment provides a rapid, low-cost approach to enable evidence-driven virus surveillance and increases the feasibility of downstream biological and ecological characterisation of viruses.


See also: [Accompanying primer written by Jason Ladner.](https://doi.org/10.1371/journal.pbio.3001403) 
"


# Summary. An optional shortened abstract.
summary: We describe a machine learning model that identifies candidate zoonoses using evolutionary signals of host range encoded in viral genomes. This allows identification of high-risk viruses immediately upon discovery, increasing both the feasibility and likelihood of downstream virological and ecological characterization and allowing for evidence-driven virus surveillance.

tags:
- zoonoses
- interferome
- virus discovery
- zoonotic risk


featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.plos.org/plosbiology/article/file?id=10.1371/journal.pbio.3001390&type=printable
url_code: https://github.com/nardus/zoonotic_rank
url_dataset: dataset/zoonotic_rank/
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Novel viruses ranked by their predicted probability of being able to infect humans"
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

{{< altmetric "10.1371/journal.pbio.3001390" >}}