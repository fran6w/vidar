# VIDAR-19 - Visualization of Covid-19 Risk Factors and Vaccine Side Effects

![VIDAR-19](https://vidar19.eu.pythonanywhere.com/assets/img/vidar_wm2.png)

## 1. Introduction

With the COVID-19 disease, risk factors and co-morbidities are at stakes. Patients presenting such risks should indeed receive specific attentions and cares. The fact is that risk factors and co-morbidities reports are spread in many publications which does not provide a global view with actionable information.

In 2020, to cope with this problem, we developed a project, named **VIDAR-19** (**VI**sualization of **D**iseases **A**t **R**isk in CORD-**19**), able to extract automatically diseases from the ICD-11 in the coronavirus literature, and also diseases which might be considered as risk factors or co-morbidities.

In 2021, with the extraordinary worldwide efforts to provide a medical care for this new disease, the emphasis was on side effects of such rapidly designed vaccines. To cope with this new challenge, we extended **VIDAR-19** so as to also extract vaccine side effects by using the techniques already used and developed for risk factors

This dashboard shows the outcome of the project. We present briefly below the different tabs. The online dashboard is available at: https://vidar-19.yotta-conseil.fr/

## 2. Disease Maps

This tab shows the share of branches in 3 sets of diseases: diseases with a code in ICD-11, diseases found in the corpus and diseases which might be considered as risk factors.

It shows also 2 treemap graphics which compare by branch (or sub-branch) the occurrences of diseases in the corpus vs. the occurrences of risk factors.

## 3. Document Frequency

This tab highlights the diseases, or the branches, for which the document frequency for risk factors, or side effects, is higher than the one for diseases in the corpus.

- [Document frequency of COVID-19 risk factors](covid-19-risk-factors.md)
- [Document frequency of vaccines side effects](vaccines-side-effects.md)

## 4. Search Documents
This tab enables to search for documents which contain a disease or a branch. Then it is possible to view the document source.

## 5. Search Variants

This tab enables to search for documents which contain a variant. A short list is available: D614G, E484K, E484Q, K417N, L452R, N439K, N501Y, P681H, P681R, R346K, S477N, V367F, Y453F. Then it is possible to view the document source.

## 6. CORD-19

CORD-19 is a corpus of academic papers about COVID-19 and related coronavirus  research.  It has been curated and maintained by the [Semantic Scholar](https://www.semanticscholar.org/) team at  the [Allen Institute for AI](https://allenai.org/) to support text mining and NLP research.

Reference:

- *Lucy Lu Wang, Kyle Lo, Yoganand Chandrasekhar, Russell Reas, Jiangjiang Yang, Doug Burdick, Darrin Eide, Kathryn Funk, Yannis Katsis, Rodney Kinney, Yunyao Li, Ziyang Liu, William Merrill, Paul Mooney, Dewey Murdick, Devvret Rishi, Jerry Sheehan, Zhihong Shen, Brandon Stilson, Alex Wade, Kuansan Wang, Nancy Xin Ru Wang, Chris Wilhelm, Boya Xie, Douglas Raymond, Daniel S. Weld, Oren Etzioni, Sebastian Kohlmeier*, **CORD-19: The COVID-19 Open Research Dataset**, arxiv, April-July 2020, https://arxiv.org/abs/2004.10706

This tab presents the CORD-19 documents dataset. It provides some insights into the processed documents from the selected datasets: How many documents? How many documents mentioning at least one disease? How many documents mentioning at least one disease which might be considered as a risk factor, or as a side effect? This tab enables also to select documents dealing with COVID-19 (virus or disease) or Vaccines.

## 7. ICD-11

ICD-11 is the International Classification of Diseases from the World Health Organization.

Reference:

- *World Health Organization*, **International Statistical Classification of Diseases and Related Health Problems (11th ed.)**, 2019, https://icd.who.int/

This tab presents the ICD-11 documents dataset. It gives some insights into the diseases which have been extracted: How many diseases in the database? How many diseases mentioned in the corpus? How many diseases which might be considered as risk factors?

## 8. Updates

As the final release of the CORD-19 dataset has been produced on June 2, 2022. They won't be any update of the dashboard after this last release.

## 9. About this dashboard

The **VIDAR-19** project has been implemented in Python. The graphical part of the project has been encapsulated into the *Dash* framework from *plotly* to get this web application. It is hosted on *PythonAnywhere*.

## 10. About the name VIDAR

**VIDAR** sounds like *radar* or *lidar*. **Vi&#240;arr** is also the name of a god in Norse mythology.

## 11. Publications of this work

Francis Wolinski, **Visualization of Diseases at Risk in the COVID-19 Literature**, arXiv, May 2020, https://arxiv.org/abs/2005.00848

Francis Wolinski, **Automatic Extractions of Risk Factors from COVID-19 Literature**, 1st SciNLP: Natural Language Processing and Data Mining for Scientific Text, June 2020,  [[poster abstract](https://scinlp.org/history/2020/pdfs/automatic-extraction-of-risk-factors-from-covid-19-literature.pdf)], presented at the SciNLP 2020 workshop hosted at AKBC 2020: [[poster video](https://youtu.be/8zug2s7yfUo)]

Francis Wolinski, **Systematic Extraction of Covid-19 Risk Factors and Vaccine Side Effects**, 2nd SciNLP: Natural Language Processing and Data Mining for Scientific Text, October 2021,  [[poster abstract](https://drive.google.com/file/d/1leIk3hPjovTZkdppZ7mcUkY9D96rEcF6/view?usp=sharing)], presented at the SciNLP 2021 workshop hosted at AKBC 2021: [[poster video](https://youtu.be/mFpkkN_930k)]

## 12. Known citations of this work

- *David Oniani, Guoqian Jiang, Hongfang Liu, Feichen Shen*, **Constructing  co-occurrence network embeddings to assist association extraction for  COVID-19 and other coronavirus infectious diseases,** *Journal of the American Medical Informatics Association*, Volume 27, Issue 8, August 2020, Pages 1259–1267, https://doi.org/10.1093/jamia/ocaa117
- *Carson K. Leung, Yubo Chen, Calvin S.H. Hoi, Siyuan Shang, Yan Wen, Alfredo Cuzzocrea*,  **Big Data Visualization and Visual Analytics of COVID-19 Data**, *2020 24th International Conference Information Visualisation (IV)*, Sept 2020, pp. 415-420, https://doi.org/10.1109/IV51561.2020.00073
- Daniel Kershaw, Rob Koeling, **Elsevier OA CC-By Corpus**, arXiv, September 2020, https://arxiv.org/abs/2008.00774
- *Jie Zhao, Maria A. Rodriguez, Rajkumar Buyya*, **High-Performance Mining of COVID-19 Open Research Datasets for Text Classification and Insights in  Cloud Computing Environments**, *2020 IEEE/ACM 13th International Conference on Utility and Cloud Computing (UCC)*, December 2020, pp. 302-309,  https://doi.org/10.1109/UCC48980.2020.00048
- *Lucy Lu Wang, Kyle Lo*, **Text mining approaches for dealing with the rapidly expanding literature on COVID-19**, *Briefings in Bioinformatics*, Volume 22, Issue 2, March 2021, Pages 781–799, https://doi.org/10.1093/bib/bbaa296
- *Qingyun Wang, Manling Li, Xuan Wang, Nikolaus Parulian, Guangxing Han, Jiawei Ma, Jingxuan Tu, Ying Lin, Haoran Zhang, Weili Liu, Aabhas Chauhan, Yingjun Guan, Bangzheng Li, Ruisong Li, Xiangchen Song, Yi R. Fung, Heng Ji, Jiawei Han, Shih-Fu Chang, James Pustejovsky, Jasmine Rah, David Liem, Ahmed Elsayed, Martha Palmer, Clare Voss, Cynthia Schneider, Boyan Onyshkevych*, **COVID-19 Literature Knowledge Graph Construction and Drug Repurposing Report Generation**, May 2021, https://arxiv.org/abs/2007.00576
- *Houcemeddine Turki, Mohamed Ali Hadj Taieb, Alejandro Piad-Morffis, Mohamed Ben Aouicha, René Fabrice Bile*, **Data Models for Annotating Biomedical Scholarly Publications: the Case of CORD-19**, *2nd International Workshop on Scientific Knowledge: Representation, Discovery, and Assessment*, April 2022, https://www2022.thewebconf.org/PaperFiles/130.pdf
- *Adil Bahaj, Safae Lhazmir, Mounir Ghogho, Houda Benbrahim*, **Covid19-related Scientific Literature Exploration: Short Survey and Comparative Study**, Preprint, April 2022, https://www.preprints.org/manuscript/202205.0004/v1
- *Girish Kumar D, Kavya B P, Kavyashree S, Asmiya Afsha*, **High-Performance Mining of COVID-19**, *International Journal for Research in Applied Science & Engineering Technology (IJRASET)*, Volume 10 Issue VII, July 2022, https://doi.org/10.22214/ijraset.2022.45702
- *Carson K. Leung, Evan W.R. Madill, Adam Pazdor*, **Visualization and Visual Knowledge Discovery from Big Uncertain Data**, 2022 26th International Conference Information Visualisation (IV), July 2022, pp. 330-335, https://doi.org/10.1109/IV56949.2022.00062
- *Dave Gibbon*, VIDAR-19 app listed in the **Plotly & Dash 500 Index**, November 2022, https://dash-demo.plotly.host/plotly-dash-500/snapshot-1667920357-bc166925
