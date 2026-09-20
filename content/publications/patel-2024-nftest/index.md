---
title: "NFTest: automated testing of Nextflow pipelines"
authors:
  - Yash Patel
  - me
  - Takafumi N. Yamaguchi
  - Yuan Zhe Bugh
  - Mao Tian
  - Aaron Holmes
  - Sorel Fitz-Gibbon
  - Paul C. Boutros
date: "2024-02-01T00:00:00Z"
publishDate: "2024-02-01T00:00:00Z"
publication_types: [article-journal]
publication:
  name: Bioinformatics
abstract: >-
  Motivation
  The ongoing expansion in the volume of biomedical data has contributed to a growing complexity in the tools and technologies used in research with an increased reliance on complex workflows written in orchestration languages such as Nextflow to integrate algorithms into processing pipelines. The growing use of workflows involving various tools and algorithms has led to increased scrutiny of software development practices to avoid errors in individual tools and in the connections between them.

  Results
  To facilitate test-driven development of Nextflow pipelines, we created NFTest, a framework for automated pipeline testing and validation with customizability options for Nextflow features. It is open-source, easy to initialize and use, and customizable to allow for testing of complex workflows with test success configurable through a broad range of assertions. NFTest simplifies the testing burden on developers by automating tests once defined and providing a flexible interface for running tests to validate workflows. This reduces the barrier to rigorous biomedical workflow testing and paves the way toward reducing computational errors in biomedicine.

  Availability and implementation
  NFTest is an open-source Python framework under the GPLv2 license and is freely available at https://github.com/uclahs-cds/tool-NFTest. The call-sSNV Nextflow pipeline is available at: https://github.com/uclahs-cds/pipeline-call-sSNV.
hugoblox:
  ids:
    doi: 10.1093/bioinformatics/btae081
links:
  - type: code
    url: https://github.com/uclahs-cds/tool-NFTest
---
