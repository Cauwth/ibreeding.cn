---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: About us
      subtitle:
      text: |
        
        {{< figure src="hezhao.jpg" width="100%" >}}
        [Professor Xiangfeng Bryan Wang and his members](people#current) in the Lab at China Agricultural University are working on a series of topics in Systems Biology, including:
        1. [Crop Genomics](research/crop-genomics), particularly interested in understanding the domestication process from ancestral plant species to modern crops, such as rice, maize, wheat. His Lab has recently sequenced and assembled the wild African rice Oryza barthii genome using the third generation sequencing platform, PacBio system. Comparison between O. barthii and its cultivated rice, Oryza glaberrima, revealed a long DNA fragment (200Kb) subject to strong domestication selection.
        2. [Population Genetics](research/population-genetics), particularly interested in developing novel methodologies for GWAS analysis, and identifying important genes, QTL, and genetic variations that are associated with important agronomic traits. We are currently working on integrating crop germplasm resequencing data for meta-GWAS analysis.
        3. [Genomic Breeding](research/genomic-breeding), particularly interested in using different methods to build Genomic Selection (GS) -assisted breeding models in rice and maize, and computational methods of Genomic Estimate of Breeding Values (GEBV). For instance, when a small training population of genotypes and phenotypes are given, these models can be used to predict values of phenotypic traits of the offspring hybridized from two parental lines. This is very useful for crop breeding.
        4. [Systems Biology](research/systems-biology), Big Data, particularly interested in developing new methods to infer, analyze, and decipher gene networks. Previously, we used machine learning methods to build gene co-expression network, and to identify novel genes that involved in stress response. Currently, we are working on integrating multiple sources of biological data, such as Protein-Protein interaction data, GWAS data, regulatory data, phenotypic data to infer genetic interactions of genes that contribute to important yield traits in wheat, maize and rice.
        5. [Bioinformatics Software, Databases, and Models](research/bioinformatics). All of the algorithms, analysis pipelines, integrated datasets will be developed as public bioinformatic tools and databases for the crop community to freely downloaded and use. We have developed several packages for plant biologists, such as rsgcc, mlDNA, KGBassembler, CrusView.
        6. [Human Genetics and Health](research/human-health). Prof. Wang recently received a fund from [Beijing Advanced Innovation Center for Food Nutrition and Human Health](http://baicfnhh.cau.edu.cn/) at the CAU . As a Guest PI for the center, we have started working on human genetics related to nutritional genomics. For instance, genetic defects in utilization of folic acids, vitamin A for a pregnant woman, may cause serious problems of human embryo development, and deliver a problematic baby. We are working on identifying the genetic variations and developing risk evaluation models for precise nutrition guidance.
        7. [Bioinformatics Education](education). As the demands for Bioinformatican has intensively growing, the College of Agronomy and Biotechnology has recently established a Department of Crop Genomics and Bioinformatics. As the chair for this new department, Prof. Wang is working on several core classes for undergraduate education for Bioinformatics and Genomics major. We are also helping the college to build a Crop Systems Biology Education Lab, equipped with high-performance computational clusters and terminals with bioinformatics tools and databases, so that undergraduate students interested in this major will have a place to receive scientific training in systems biology.  
    design:
      columns: '1'
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
