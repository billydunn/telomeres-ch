## Treelomeres: phylogenies of haematopoietic colonies annotated with telomere length 

This repo contains a R markdown file (and rendered HTML document) detailing the analysis of phylogenetic trees constructed from single-cell derived haematopoietic colonies from individuals with splicing factor-mutated clonal haematopoiesis. It accompanies the paper by McLoughlin, Cheloor Kovilakam & Dunn et al (in revision). 

Specifically, the script takes as input phylo objects and annotates these phylogenies with NGS-estimated telomere lengths for each individual colony, to visualise differences in telomere length between clades (see the example image below). It also details exploratory analysis of the dataset, before finally outlining the steps used to generate linear mixed-effects models to model telomere length with respect to driver mutation status and various possible confounders.  

![Example image of phylogeny annotated with telomere length](./example/example-annotated-phylogeny.png)
