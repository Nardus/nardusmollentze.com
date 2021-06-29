---
title: "Zoonotic risk assessment from viral genomes"
authors:
- Nardus Mollentze
- Simon Babayan
- Daniel Streicker
date: "2020-11-12"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-11T00:00:00Z"

# Associated publications:
link_publications: 

# Associated Projects (optional, untested).
#   Simply enter your project's folder or file name without extension.
#   Otherwise, set `projects: []`.
projects: []

# Link to raw data:
raw_data: https://github.com/nardus/zoonotic_rank

# Brief description:
abstract: "Virus species ranked by their predicted probabilities of being capable of human infection. Ranking was performed using a [genome composition-based machine learning model](https://github.com/nardus/zoonotic_rank) using a representative genome for each species. Derived from Table S1 of [Mollentze, Babayan & Streicker (2020)](https://doi.org/10.1101/2020.11.12.379917). This table includes both training and holdout viruses (see \"current status\" column).


___Note that this work has not undergone peer-review yet, and should not be regarded as established information or results.___"


# Shorter summary for overview pages:
summary: "Viruses ranked by their predicted probabilities of human infection."

# A data file to display (optional):
#   Note that the *number* of columns named determines how many columns are loaded
#   "filter_columns" specifies the indices of columns which should be present in the "filter records" pane, starting at 0
#   "order_column" specifies the index of a single column to order by
#   "order_direction" can be "asc" or "desc"
csv_file: "/csv/combined_virus_ranks_rounded.csv"
col_names: [Species, Family, Current status, Accession, Predicted probability, Confidence interval, Zoonotic potential]
filter_columns: [1,2,6]
order_column: 4
order_direction: "desc"
---