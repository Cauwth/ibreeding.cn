---
title: Bioinformatics
type: landing

sections:
  - block: markdown
    content:
      title: Bioinformatics
      text: |
        #### An intelligent marker-selection system for crop (rice, maize, wheat) genetic breeding

        Previous GWAS and resequencing analysis of crop germplasm has identified millions SNP markers that can be selected for breeding purposes. One of the projects in the lab is to collect all previous published GWAS datasets, and to perform a meta-GWAS analysis to define significant haplotype block, SNP marker and genes in association with important agronomic traits. Similar to the concept in precision medicine, the basic idea of this work is to build up the link at different levels of biological entities with a series of feature tags. When a user define a trait or a breeding goal, the system will be automatically searching the databases with feature tags and finally result in collecting a panel SNP markers that can be used for molecular breeding or calculation of breeding values.


        Behind the database, we are using a set of machine learning techniques to organize the data. For instance, association rule learning (ARL) methods to automatically infer the relationships between different entities; when extracting a desired trait for improvement, a Random Forest (RF) model will be used to compile the best set of markers. In addition, we are also integrating a series of tools that are frequently used for molecular breeding in the database, so that user can do a one-stop analysis for crop breeding.
        {{< figure src="Bioinformatics.png" width="100%" >}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
