---
abstract: "**Objectives:**
Despite their essential role in collecting and organizing published medical literature, indexed search engines are unable to cover all relevant knowledge. Hence, current literature recommends the inclusion of clinical trial registries in systematic reviews (SRs). This study aims to provide an automated approach to extend a search on PubMed to the ClinicalTrials.gov database, relying on text mining and machine learning techniques.

**Study Design and Setting:**
The procedure starts from a literature search on PubMed. Next, it considers the training of a classifier that can identify documents with a comparable word characterization in the ClinicalTrials.gov clinical trial repository. Fourteen SRs, covering a broad range of health conditions, are used as case studies for external validation. A cross-validated support-vector machine (SVM) model was used as the classifier.

**Results:**
The sensitivity was 100% in all SRs except one (87.5%), and the specificity ranged from 97.2% to 99.9%. The ability of the instrument to distinguish on-topic from off-topic articles ranged from an area under the receiver operator characteristic curve of 93.4% to 99.9%.

**Conclusion:**
The proposed machine learning instrument has the potential to help researchers identify relevant studies in the SR process by reducing workload, without losing sensitivity and at a small price in terms of specificity."
authors:
- admin
- Clara Minto
- Abhinav Sharma
- Dario Gregori
- Paola Berchialla
- Ileana Baldi
date: "2018-11-01"
doi: "10.1016/j.jclinepi.2018.06.015"
featured: true
image:
  caption: 'General procedure workflow'
  focal_point: ""
  preview_only: false
projects: []
publication: '*Journal of Clinical Epidemiology*, (103)'
publication_short: "JCE"
publication_types:
- "2"
publishDate: "2018-11-01"
slides: ""
summary: The proposed machine learning instrument has the potential to help researchers identify relevant studies in the SR process by reducing workload, without losing sensitivity and at a small price in terms of specificity.

tags:
- Systematic review
- Meta-analysis
- Clinical trial registry
- Indexed search engine
- Machine learning
- Text mining

title: Extending PubMed searches to ClinicalTrials.gov through a machine learning approach for systematic reviews

url_code: ""

links:
  - name: "GitHub repository"
    url: "https://github.com/UBESP-DCTV/costumer"
    
  - name: "View Journal Article"
    url: "https://www.sciencedirect.com/science/article/pii/S0895435618300854"
url_dataset: ""

url_pdf: ""

url_poster: ""

url_project: ""

url_slides: ""

url_source: ""

url_video: ""
---

{{% alert note %}}
The main data used are too huge to be included in an R package or in a
GitHub repository. You can click on the **Dataset** button above to find
a folder named `non_git_nor_build_derived_data/` (2.86 GB) which include
the full data used. You can find the description of the content on the
GitHub project's homepage (**Code** button).
{{% /alert %}}

