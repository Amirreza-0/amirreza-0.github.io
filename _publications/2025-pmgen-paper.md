---
title: "PMGen: From Peptide-MHC Prediction to Neoantigen Generation"
collection: publications
category: manuscripts
permalink: /publication/2025-pmgen-paper
excerpt: 'An integrated framework for predicting, modeling, and generating peptides across both MHC classes with applications in personalized immunotherapy.'
date: 2025-11-14
venue: 'bioRxiv'
paperurl: 'https://doi.org/10.1101/2025.11.14.688404'
citation: 'Asgary, A. H., Aleyassin, A., Mehl, J. A., Ludewig, B., Mishto, M., Liepe, J., & Soeding, J. (2025). &quot;PMGen: From Peptide-MHC Prediction to Neoantigen Generation.&quot; <i>bioRxiv</i>, 2025.11.14.688404.'
---

## Abstract

Major histocompatibility complexes (MHCs) present peptides to T cells, playing a central role in adaptive immunity against cancer and infections. Accurate structural modeling of peptide–MHC (pMHC) complexes is essential for developing personalized immunotherapies. Existing tools often focus on either MHC class I or II, support limited peptide lengths, and address isolated tasks such as pMHC binding prediction or structure modeling. We introduce Peptide MHC Generator (PMGen), an integrated framework for predicting, modeling, and generating peptides across both MHC classes and a broad range of peptide lengths.

## Key Achievements

* **High Structural Accuracy**: Mean peptide core RMSD of 0.54 Å for MHC-I and 0.33 Å for MHC-II, improving over state-of-the-art methods
* **Dual MHC Class Support**: Supports both MHC class I and class II with broad peptide length ranges
* **Anchor-Guided Modeling**: Enhances AlphaFold predictions by incorporating anchor residue information into the structural module
* **Peptide Generation**: Generates diverse, high-affinity peptides with minimal structural deviation using ProteinMPNN
* **Neoantigen Modeling**: Accurately models the impact of single-point mutations in benchmark neoantigen–wildtype pairs

## Technical Innovation

PMGen integrates three core components:
1. **Anchor Feeding Module**: Predicts anchor residues using NetMHCpan and provides them as constraints to AlphaFold2
2. **Structure Prediction**: Implements two approaches - Initial Guess (IG) and Template Engineering (TE) for incorporating anchor information
3. **Peptide Generation**: Employs ProteinMPNN to sample alternative peptides aligned with predicted backbones

## Applications

* **Personalized Immunotherapy**: Rational design of neoantigens with enhanced pMHC binding affinity
* **Cancer Vaccine Development**: Combining MHC-I and MHC-II epitopes for improved therapeutic efficacy
* **Structural Immunology**: Understanding T-cell recognition and immune response mechanisms
* **CAR-T Cell Design**: Development of Fab fragments and antibodies that specifically recognize neoantigen–MHC complexes

## Availability

PMGen is freely available at [https://github.com/soedinglab/PMGen](https://github.com/soedinglab/PMGen)

## Authors

Amir H. Asgary, **Amirreza Aleyassin**, Jonas A. Mehl, Burkhard Ludewig, Michele Mishto, Juliane Liepe, Johannes Soeding
