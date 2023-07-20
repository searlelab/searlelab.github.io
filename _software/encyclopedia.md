---
name: EncyclopeDIA
position: active
avatar: encyclopedia_image.png
url: https://bitbucket.org/searleb/encyclopedia
started: 2018
---

<img width="300" src="{{site.baseurl}}/images/software/{{page.avatar}}" data-action="zoom">

_Library Searching for Data Independent Acquisition_

### Download
[https://bitbucket.org/searleb/encyclopedia](https://bitbucket.org/searleb/encyclopedia)

### Description

Data independent acquisition (DIA) mass spectrometry is a powerful technique that is improving the reproducibility and throughput of proteomics studies. EncyclopeDIA is library search engine comprised of several algorithms for DIA data analysis and can search for peptides using either DDA-based spectrum libraries or DIA-based chromatogram libraries. Check out our manuscript describing EncyclopeDIA at Nature Communications ([Searle et al, 2018](https://doi.org/10.1038/s41467-018-07454-w)) for more information. EncyclopeDIA contains Walnut, an implementation of the PECAN ([Ting et al, 2017](https://www.ncbi.nlm.nih.gov/pubmed/28783153)) scoring system, to enable chromatogram library generation from FASTA protein sequence databases when spectrum libraries are unavailable. EncyclopeDIA also supports [Prosit](https://www.proteomicsdb.org/prosit/), a deep learning tool for generating peptide fragmentation spectra, as described in our new methods paper ([Searle et al, 2020](https://www.nature.com/articles/s41467-020-15346-1)).

### Citation
Searle BC, Pino LK, Egertson JD, Ting YS, Lawrence RT, MacLean BX, Villén J,
MacCoss MJ.
Comprehensive peptide quantification for data independent acquisition mass
spectrometry using chromatogram libraries. Nat Commun. 2018 Dec 3;9(1):5128. [Publication](https://doi.org/10.1038/s41467-018-07454-w)

Searle BC, Swearingen KE, Barnes CA, Schmidt T, Gessulat S, Kuster B, Wilhelm M. Generating high quality libraries for DIA MS with empirically corrected peptide predictions. Nat Commun. 2020 Mar 25;11:1548.
[Publication](https://www.nature.com/articles/s41467-020-15346-1)
