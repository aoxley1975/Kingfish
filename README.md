# Antibiotic-induced alterations and repopulation dynamics of yellowtail kingfish microbiota

Overview

The use of antibiotics in aquaculture is a common infection treatment and is increasing in some sectors and jurisdictions. While antibiotic treatment can negatively shift gut bacterial communities, recovery and examination of these communities in fish of commercial importance is not well documented. Examining the impacts of antibiotics on farmed fish microbiota is fundamental for improving our understanding and management of healthy farmed fish. This work assessed yellowtail kingfish (Seriola lalandi) skin and gut bacterial communities after an oral antibiotic combination therapy in poor performing fish that displayed signs of enteritis over an 18-day period. In an attempt to promote improved bacterial re-establishment after antibiotic treatment, faecal microbiota transplantation (FMT) was also administered via gavage or in the surrounding seawater, and its affect was evaluated over 15 days post-delivery. Antibiotic treatment greatly perturbed the global gut bacterial communities of poor-performing fish – an effect that lasted for up to 18 days post treatment. This perturbation was marked by a significant decrease in species diversity and evenness, as well as a concomitant increase in particular taxa like an uncultured Mycoplasmataceae sp., which persisted and dominated antibiotic-treated fish for the entire 18-day period. The skin-associated bacterial communities were also perturbed by the antibiotic treatment, notably within the first 3 days; however, this was unlike the gut, as skin microbiota appeared to shift towards a more ‘normal’ (though disparate) state after 5 days post antibiotic treatment. FMT was only able to modulate the impacts of antibiotics in some individuals for a short time period, as the magnitude of change varied substantially between individuals. Some fish maintained certain transplanted gut taxa (i.e. present in the FMT inoculum; namely various Aliivibrio related ASVs) at Day 2 post FMT, although these were lost by Day 8 post FMT. As we observed notable, prolonged perturbations induced by antibiotics on the gut bacterial assemblages, further work is required to better understand the processes/dynamics of their re-establishment following antibiotic exposure. In this regard, procedures like FMT represent a novel approach for promoting improved microbial recovery, although their efficacy and the factors that support their success requires further investigation.

Sequencing reads from the demultiplexed samples analysed in this study have been deposited in the NCBI Sequence Read Archive (SRA) under the BioProject accession PRJNA602789.

This repository contains following folders -

data/ # raw data generated using QIIME2-2018.6

filtered-table.qza # OTU table
tax.txt # OTU taxonomy
metadata.txt # metadata file
rooted-tree.qza # OTU tree
code/ # QIIME commands and phyloseq scripts

analysis.sh # QIIME2-2018.6 analysis steps
PupFish.RMD # Phyloseq scripts
