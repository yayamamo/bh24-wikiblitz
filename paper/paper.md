---
title: 'BioHackJP24 report: Template for the very long title'
title_short: 'BioHackJP24: Wikiblitz during the Biohackathon 24 '
tags:
  - iNaturalist
  - Wikidata
  - Biodiversity
  - Citizen science
authors:
  - name: Andra Waagmeester
    orcid: 0000-0001-9773-4008
    affiliation: 1
  - name: Yasunori Yamamoto
    orcid: 0000-0002-6943-6887
    affiliation: 2
  - name: sikeda_0124
    affiliation: 3
  - name: Heval Kinch
    affiliation: 4
  - name: Núria Queralt Rosinach
    affiliation: 5
  - name: Erick Antezana
    affiliation: 6
  - name: Julia Koblitz
    orcid: 0000-0002-7260-2129
    affiliation: 7
  - name: toreeriksson
    affiliation: 8
affiliations:
  - name: Micelio BV
    index: 1
  - name: Database Center for Life Science
    index: 2
  - name: Leibniz Institute DSMZ-German Collection of Microorganisms and Cell Cultures
    index: 7
date: 7 September 2024
cito-bibliography: paper.bib
event: BH24JP
biohackathon_name: "BioHackathon 2024"
biohackathon_url:   "https://2024.biohackathon.org"
biohackathon_location: "Sansuiso, Fukushima, Japan"
group: WikiBlitz
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/publication-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

As part of the BioHackathon Europe 2023, we here report...

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

## References
