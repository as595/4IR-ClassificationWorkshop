
# Supporting Material: 4IR-Classification Workshop

Material supporting the talk "Classification in Time Domain Astrophysics", delivered Wednesday Nov 22nd 2017.

## Author: Rob Lyon
## Email : robert.lyon@manchester.ac.uk
## Web   : www.scienceguyrob.com

### Talk Overview
This talk explores a time domain classification task, concerned with the automatic categorisation of periodic radio signals in astronomical data. Our aim is to perform the categorisation as accurately as possible, facilitating the rapid identification of signals of scientific utility. Good performance is crucial to enable the discovery of important phenomena, from fast radio bursts (FRBs), to rare stellar remnants known as a radio pulsars. This is a difficult classification task, primarily due to the presence of radio frequency interference (RFI) (caused by human activity), and the ability of random noise to mimic genuine signals of interest. It is complicated further by the advancement of modern technology. Improvements in computing power and receiver technology are permitting the construction of extremely sensitive observing instruments. Such instruments not only return more candidates than ever before, but also produce data in such large volumes, that they impede the effectiveness of our existing categorisation strategies. This talk reviews these challenges, and the issues which reduce the effectiveness of machine learning methods.

### Repository Contents
This repository simply consists of this readme file, and the talk slides.

We kindly request that if you make use of this work, or any of the linked resources, please reference it accordingly (using a repository DOI where possible).

### Links

This repository has a basic introduction to machine learning, in particular with Scikit-learn:

[Basic ML tutorial](https://github.com/scienceguyrob/JACS-ML-Tutorial)

---

Notebook: Fifty Years of Candidate Pulsar Selection - What next? This notebook explores the main issues which reduce the accuracy of Machine Learning (ML) algorithms, used for candidate classification. It was written to support a talk delivered at IAU Symposium No. 337, Pulsar Astrophysics: The Next Fifty Years (2017).

[![DOI](https://zenodo.org/badge/102269399.svg)](https://zenodo.org/badge/latestdoi/102269399)

---

A pipeline useful for generating time domain data products:

[Test vector generation pipeline](https://github.com/scienceguyrob/SKA-TestVectorGenerationPipeline)

---

An ipython notebook used to model SKA Science Data Processor (SDP) data rates. This resource was used to calculate the SKA data rates described in the talk.

[![DOI](https://zenodo.org/badge/92536926.svg)](https://zenodo.org/badge/latestdoi/92536926)

---

Example data (feature data):

[The HTRU 2 Pulsar dataset](https://doi.org/10.6084/m9.figshare.3080389.v1)

### License
The code and the contents of this notebook are released under the GNU GENERAL PUBLIC LICENSE, Version 3, 29 June 2007. We kindly request that if you make use of the notebook, you cite the work appropriately.

### Change log

First version.
