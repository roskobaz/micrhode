# MicRhoDE - Microbial Rhodopsin Diversity & Evolution 
[![Release](https://img.shields.io/badge/release-1.0-blue.svg)
![Date](https://img.shields.io/badge/date-01%20July%202020-lightgrey.svg)
![Github Downloads
(total)](https://img.shields.io/github/downloads/roskobaz/micrhode/total.svg)](https://github.com/roskobaz/micrhode/releases)

## Welcome to the MicRhoDE database!
<p>Rhodopsins are photochemically active membrane proteins that are composed of seven transmembrane helices with a retinal chromophore. According to their protein sequences, they are classified in two families known as either type-1 rhodopsins, that are all of microbial origin and type-2 rhodopsins that are animal photosensitive receptors. Microbial rhodopsins are found in all three domains of life and in viruses.</p>

<p>The aim of MicRhoDE is to provide the scientific community with a comprehensive, high-quality and freely accessible resource that facilitates analysis of the diversity and evolution of microbial rhodopsins, with an emphasis on proteorhodopsins. Proteorhodopsin is an abundant homolog of bacteriorhodopsin firstly discovered in a marine proteobacterium, known to be present in a wide diversity of microbes and in viruses. Proteorhodopsin-containing microorganisms are widespread in terrestrial, freshwater and marine photic environments.</p>

<p>Based on the analysis of marine and terrestrial metagenomic data, microbial rhodopsins were suggested as prominent phototrophic mechanism on Earth. More investigations are needed to fully understand the physiological functions and fitness benefits obtained from microbial rhodopsins and their actual role in microbial ecology and in energetic balance of ecosystems.</p>

## What we provide.
<p>We provide about 7900 manually curated sequences of type-1 rhodopsins from more than 450 environmental samples and organisms. All sequences were aligned according to the predicted secondary structure of the protein and a robust phylogenetic tree was constructed. Based on a robust phylogenetic analysis, we introduce an operational classification system with multiple phylogenetic levels ranging from superclusters to species-level operational taxonomic units.</p>

<p>MicRhoDE tools allow sequence searches either by keywords, taxonomic unit, or sequence similarity (BLAST). Results can be sorted in raw or aligned nucleic or amino-acid sequences or visualized on a map.</p>

Numerous supporting data are also provided including:
* type of rhodopsin, putative function and activity (type of residue at position 97 and 108),
* predicted spectral tuning of the rhodopsin (type of residue at position 105),
* isolation province, biome and geographical coordinates (geolocation on a map),
* taxonomy (according NCBI) and databases cross-references,
* classification in taxonomic units according a global phylogeny of microbial rhodopsins (see phylogeny)
* literature citations, year of isolation and publication

## Current version
* Current version : 1.0
* Last update : 1st of July, 2020 
* DOI
* [Link](https://github.com/roskobaz/micrhode/releases)
* Documentation

## Curators

* [Dominique BOEUF](mailto:dboeuf@sb-roscoff.fr), Sorbonne Université · Laboratoire de Biodiversité et Biotechnologie Microbienne USR 3579, 66650 Banyuls-sur-Mer FRANCE
* [Christian JEANTHON](mailto:jeanthon@sb-roscoff.fr), CNRS-Sorbonne Université · Station Biologique, 29680 Roscoff FRANCE

## How to Cite
Boeuf, D., Audic, S., Brillet-Guéguen, L., Caron, C., and Jeanthon, C. MicRhoDE: a curated database for the analysis of microbial rhodopsin diversity and evolution. Database (Oxford). 2015. doi: 10.1093/database/bav080

Links: [PubMed](https://pubmed.ncbi.nlm.nih.gov/26286928/)
[DATABASE (Oxford)](https://academic.oup.com/database/article/doi/10.1093/database/bav080/2433213)

## Provided Files

|File suffix             |File Content                                                                          |
|------------------------|--------------------------------------------------------------------------------------|
|contextual_data.csv.gz  |A tabulated file containing all contextual data, including environmental parameters.  |
|dada2.fasta.gz          |A fasta of all reference sequences with DADA2-formatted headers                       |
|mothur.fasta.gz         |A fasta of all reference sequences with MOTHUR-formatted headers                      |
|mothur.tax.gz           |A text file of taxonomies for MOTHUR                                                  |
|taxo_long.fasta.gz      |A fasta of all reference sequences with long "n-ranked" taxonomy                      |
|UTAX.fasta.gz           |A fasta of all reference sequences with VSEARCH-formatted headers                     |


## Report issues

-   Please report any issue on [GitHub](https://github.com/roskobaz/micrhode/issues)
