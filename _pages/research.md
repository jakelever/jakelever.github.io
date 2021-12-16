---
permalink: /research/
title: "Research"
---

My [university profile](https://www.gla.ac.uk/schools/computing/staff/jakelever/) provides a nice overview of some of my research interests, particularly using machine learning to do clever things with biomedical text. Below are a few recent projects.

### [CoronaCentral](https://coronacentral.ai)

The pandemic has caused an incredible surge in research on different aspects of the virus and its effects. It is very challenging to navigate this fire hose of papers. This [portal](https://coronacentral.ai) makes it more manageable to find the important papers for a variety of topics, from risk factors and forecasting to vaccines and the psychology impacts. The research uses a supervised learning approach with a set of classifiers trained on topic annotations for several thousand papers. It was published in [PNAS](https://doi.org/10.1073/pnas.2100766118). The machine learning code is on [Github](https://github.com/jakelever/corona-ml) and the data is on [Zenodo](https://doi.org/10.5281/zenodo.4383289).

### [PGxMine](https://pgxmine.pharmgkb.org/)

Pharmacogenomics studies the effect of genetic variation on drug response. The daunting task of curating the entire biomedical literature for relevant knowledge is taken on by the [PharmGKB team](https://www.pharmgkb.org/) at Stanford University. To assist in this task, I created the PGxMine tool that identifies important pharmacogenomics knowledge in literature and prioritises papers for their curation. This data is now integrated into the [PharmGKB resource (under Automated Annotations)](https://pharmgkb.blogspot.com/2019/10/pharmgkb-releases-automated-annotations.html) and is being used by curators. The data is [viewable online](https://pgxmine.pharmgkb.org/) and the work was published at the [Pacific Symposium for Biocomputing](https://pubmed.ncbi.nlm.nih.gov/31797632/).

### [CIViCmine](http://bionlp.bcgsc.ca/civicmine/)

CIViCmine aids curation of the CIViC database for known cancer biomarkers for diagnosis, prognosis, predisposition and drug resistance. This knowledge is invaluable for personalized cancer projects to help select treatments for individual patients. To assist in curation and to provide a high quality knowledge base in this area, cancer biomarkers have been mined from abstracts and full text papers. The resulting data can be viewed with the [associated web viewer](http://bionlp.bcgsc.ca/civicmine/). The work has been published in [Genome Medicine](https://doi.org/10.1186/s13073-019-0686-y).

### [CancerMine](http://bionlp.bcgsc.ca/cancermine/)

CancerMine uses text mining to extract known drivers, oncogenes and tumor suppressors discussed in the literature. Understanding the role of different genes in different cancer types is essential for precision cancer efforts. The project data can be viewed with the [associated web viewer](http://bionlp.bcgsc.ca/cancermine/) and downloaded at [Zenodo](https://doi.org/10.5281/zenodo.1156241). This work has been published in [Nature Methods](https://www.nature.com/articles/s41592-019-0422-y) and a preprint paper is available at [bioRxiv](https://doi.org/10.1101/364406). 

### [Kindred](https://github.com/jakelever/kindred)

Kindred is our relation extraction tool that uses a supervised learning approach. The [code](https://github.com/jakelever/kindred) and [associated paper](http://aclweb.org/anthology/W17-2322) are freely available. It is the successor to our [BioNLP'16 Shared Task](http://2016.bionlp-st.org/) winning [VERSE tool](https://github.com/jakelever/VERSE). 

