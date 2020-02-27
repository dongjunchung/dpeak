[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3687178.svg)](https://doi.org/10.5281/zenodo.3687178)

dpeak
=====

dPeak is a statistical framework for the high resolution identification of protein-DNA interaction sites using PET and SET ChIP-Seq and ChIP-exo data. It provides computationally efficient and user friendly interface to process ChIP-seq and ChIP-exo data, implement exploratory analysis, fit dPeak model, and export list of predicted binding sites for downstream analysis. You can track development of mosaics package at http://github.com/dongjunchung/dpeak. To install the development version of dpeak, it's easiest to use the devtools package:

```
#install.packages("devtools")
library(devtools)
install_github("dongjunchung/dpeak")
```

References
==========

Chung D, Park D, Myers K, Grass J, Kiley P, Landick R, and Keles S (2013), "dPeak: High resolution identification of transcription factor binding sites from PET and SET ChIP-Seq data," _PLoS Computational Biology_, 9(10): e1003246.

Welch R*, Chung D*, Grass J, Landick R, and Keles S (2017), "Data exploration, quality control, and statistical analysis of ChIP-exo/nexus experiments," _Nucleic Acids Research_, 45(15): e145. (* Joint first authors)
