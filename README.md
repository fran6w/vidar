# VIDAR-19 - Visualization of Diseases At Risk in CORD-19

![VIDAR-19](https://fran6wol.eu.pythonanywhere.com/assets/img/vidar_wm2.png)

Online dash board available at: https://vidar-19.yotta-conseil.fr/

##### Introduction

With the COVID-19 disease, risk factors and co-morbidities are at stakes. Patients presenting such risks should indeed receive specific attentions and cares.

The fact is that risk factors and co-morbidities reports are spread in many publications which does not provide a global view with actionable information.

To cope with this problem, we developed a project, named **VIDAR-19** (**VI**sualization of **D**iseases **A**t **R**isk in CORD-**19**), able to extract automatically diseases from the ICD-11 in the coronavirus literature, and also diseases which might be considered as risk factors or co-morbidities.

This dashboard shows the outcome of the project. We present briefly below the different tabs of this dashboard.

##### Disease Maps

This tab shows the share of branches in 3 sets of diseases: diseases with a code in ICD-11, diseases found in the corpus and diseases which might be considered as risk factors.

It shows also 2 treemap graphics which compare by branch (or sub-branch) the occurrences of diseases in the corpus vs. the occurrences of risk factors.

##### Document Frequency

This tab highlights the diseases, or the branches, for which the document frequency for risk factors is higher than the one for diseases in the corpus.

##### Search Documents

This tab enables to search for documents which contain a disease or a branch. Then it is possible to view the document source.

##### Search Variants

This tab enables to search for documents which contain a variant. A short list is available: D614G, E484K, K417N, N501Y, P681H. Then it is possible to view the document source.

##### CORD-19

This tab presents the CORD-19 documents dataset. It gives some insights into the processed documents from the selected datasets: How many documents? How many documents mentioning at least one disease? How many documents mentioning at least one disease which might be considered as a risk factor?

##### ICD-11

This tab presents the ICD-11 documents dataset, i.e. the International Classification of Diseases from the World Health Organization. It gives some insights into the diseases which have been extracted: How many diseases in the database? How many diseases mentioned in the corpus? How many diseases which might be considered as risk factors?

##### Updates

The dashboard is updated on a weekly to monthly frequency by including new documents from CORD-19.

##### About this dashboard

The **VIDAR-19** project has been implemented in Python. The graphical part of the project has been encapsulated into the *Dash* framework from *plotly* to get this web application. It is hosted on *PythonAnywhere*.

##### About the name VIDAR

**VIDAR** sounds like *radar* or *sonar*. **Vi&#240;arr** is also the name of a god in Norse mythology.
