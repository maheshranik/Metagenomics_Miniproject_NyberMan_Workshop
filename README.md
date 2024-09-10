# Metagenomics_Miniproject_NyberMan_Workshop
To document your metagenomics project on GitHub, here's a structured template you can use, based on the information from your study:
Characterization of Microbial Diversity in Drinking Water Systems using Qiime2

Project Team
Beutline Jebin, Deepthi Varughese, Mahesh Rani, Ritwika Nandi, Simmi Kharb, Tanushri Roy, Vidhyashri

Presented to
NyBerMan Bioinformatics Europe
Overview

This project focuses on identifying and characterizing the microbial composition in drinking water samples using metagenomics approaches, processed through Qiime2.
Project Objectives

    Identify the microbial diversity in drinking water samples.
    Characterize microbial functions and their roles within the ecosystem.
    Compare microbial composition between different water samples.

Sampling

Five water samples were collected from different locations, including drinking water and related sites.

    Number of Samples: 5
    Total Features Identified: 279 (Green Genes), 246 (SILVA)
    Sampling Depth: 11028

Data Analysis Workflow

    Import and Demultiplex Sequences: Initial quality control of raw sequence data.
    Data Denoising: Remove low-quality data and artifacts.
    Alpha and Beta Diversity Analysis: Assess within-sample and between-sample diversity.
    Taxonomic Classification: Assign taxonomies using Green Genes and SILVA databases.
    Phylogenetic Tree Construction: Build phylogenetic relationships between detected species.
    Core Microbiome Analysis: Identify common species across samples.

Results

    Number of Features Identified:
        279 (Green Genes)
        246 (SILVA)

    Diversity Analysis:
        Alpha Rarefaction: Measures species richness within samples.
        Beta Diversity: Comparison between samples using Bray Curtis, Jaccard, and Unifrac metrics.

    Taxonomic Classification:
        Green Genes database: Species-level classification for 11 species and 27 genera.
        SILVA database: Genus-level classification for 50 genera.

    Notable Microbes Identified:
        Commamonas: Significant for bioremediation and pollution degradation.
        Pseudomonadaceae: Linked with contamination in water systems.
        Cutibacterium: Indicator of human-related contamination.
        Fonsibacter: Important for water quality and ecosystem health.

Phylogenetic Tree

Phylogenetic analysis revealed relationships among identified microbial species, highlighting key microbial populations in the water samples.
Conclusion

    Significant microbial diversity was found across the water samples.
    Green Genes classifier performed species-level identification, while the SILVA classifier identified microbes at the genus level.
    The presence of certain microbes, like Commamonas and Pseudomonadaceae, indicates both ecological and potential health impacts of microbial communities in water systems.

Future Directions

    Implement real-time monitoring of microbial communities in water systems using metagenomics.
    Develop methods for early detection of pathogens and antibiotic-resistant bacteria.

Acknowledgments

We extend our gratitude to the NyBerMan Bioinformatics Europe team and our mentor Maya Jayachandran for their guidance during this project.
