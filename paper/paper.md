---
title: 'INTOXICOM Workshop Report: ...'
title_short: 'INTOXIOM #2: ...'
tags:
  - toxicology
  - PubChem
  - unknown chemical substances
# order now alphabetical
authors:
  - name: Jente Houweling
    affiliation: 1
    orcid: 0009-0005-3680-0645
  - name: Marvin Martens
    affiliation: 2
    orcid: 0000-0003-2230-0840
  - name: Egon Willighagen
    affiliation: 3
    orcid: 0000-0001-7542-0286
affiliations:
  - name: RIVM, Bilthoven, Netherlands, Department of Bioinformatics - BiGCaT, NUTRIM, Maastricht University, 6229 ER Maastricht, NL
    index: 1
  - name: Dept of Translational Genomics, NUTRIM, FHML, Maastricht University, Maastricht, NL
    index: 2
    ror: 8s72v
date: 1 December 2024
cito-bibliography: paper.bib
event: INTOXICOM
biohackathon_name: "INTOXICOM Workshops"
biohackathon_url:   "[https://biohackathon-europe.org/](https://elixir-europe.org/internal-projects/commissioned-services/integrating-toxicology-community)"
biohackathon_location: "Basel, 27-29 Nov 2024"
group: Workshop 2
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/BiGCAT-UM/INTOXICOM_Workshop_2/
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Martens \emph{et al.}
---


# Introduction

As part of the INTOXICOM Implementation Study for the ELIXIR Toxicology Community a series of workshops is organized. The first INTOXICOM workshop was held in May 2024 [@citesAsRecommendedReading:citesAsEvidence:Martens2024INTOXICOM]. Here, we here report on the 2nd workshop...

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## Funding

This workshop was funded by the ELIXIR Europe INTOXICOM grant (Grant No. NL-2023-INTOXICOM).

## References
