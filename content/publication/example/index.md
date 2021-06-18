---
abstract: >-
  Background:

  Recent research on metabolic changes that accompany oncogenesis offer opportunities for improved tumor classification and prognosis based on molecular profiling. Gene expression data can be used as a blueprint to reconstruct metabolic activity and identify predictors of patient survival. No previous study has estimated patient survival probability as a function of metabolic reaction activity across the entire spectrum of tumor tissue types.


  Methods:

  Cancer gene expression data from 5,980 donors spanning 23 tissue types was collected from 19 studies of the The Cancer Genome Atlas (TCGA), including patients' survival time, sex and age at diagnosis. Expression was normalized to transcripts per million (TPM). Human Metabolic Reaction core gene annotation (HMRcore) was used to select genes involved in metabolic pathways, and metabolic reaction activity scores were estimated using relative expression of enzyme subunits and enzyme isoforms. K-means clustering was used to classify tumors based on differentially regulated metabolic reactions, followed by Kaplan-Meier and Cox proportional hazard estimators of patient survival probabilities. Metabolic pathway reconstruction was performed using the MaREA pipeline, and upregulated and downregulated reactions in metabolic pathways were visualized. All analysis was done using R and Galaxy.

  Results:

  Across all tumor types analyzed, increased survival was associated with downregulation of glycolysis, the pentose phosphate pathway, and purine monophosphate production, even after controlling for age, sex, and tumor tissue type. Increased survival was also associated with upregulation of fatty acid synthesis, mitochondrial bicarbonate production, and glutamate/alpha-ketoglutarate conversion. Subgroup analysis by TCGA project revealed that, on the whole, the differential regulation of these metabolic pathways was conserved across tissue types. Assignment to clusters based on metabolic reaction activity scores remained a significant predictor of survival in six TCGA projects, including renal cell carcinoma, renal papillary cell carcinoma, low-grade glioma, ovarian serous cystadenocarcinoma, cutaneous melanoma, cervical squamous cell carcinoma and endocervical carcinoma. Our findings serve to inform development of molecular biology- informed tumor classifications, as well as search for drug targets to change cancer metabolism.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Jack Goodman
  - admin
author_notes:
  - Frank H. Netter MD School of Medicine
  - Frank H. Netter MD School of Medicine
publication: In *American Society for Clinical Oncology (ASCO) 2021*
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: In *ASCO2021*
url_source: ""
url_video: ""
title: Differential metabolic pathway activity estimated from tumor gene
  expression predicts prolonged cancer survival across 23 tissue types
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
