# A Step Toward Quantifying Independently Reproducible Machine Learning Research

What makes a paper independently reproducible? Debates on reproducibility center around intuition or assumptions but lack empirical results. Our field focuses on releasing code, which is important, but is not sufficient for determining reproducibility. We take the first step toward a quantifiable answer by manually attempting to implement 255 papers published from 1984 until 2017, recording features of each paper, and performing statistical analysis of the results. For each paper, we did not look at the authors code, if released, in order to prevent bias toward discrepancies between code and paper.

This repository hots a copy of my paper detailing this exercises, as well as an anonymized version of the raw data that the study produced. The data is anonymized because this effort should not be seen as an authoritative statement regarding any paper’s apparent lack of reproduction. We explicitly want to avoid any perceived “naming and shamming”.

My goal in this work is to move the conversation forward toward quantifying our communities’ effort toward more reproducible research. The content of the paper is likely not a complete evaluation of all the insights that may be derived from the data, and much work still remains to improve protocols, data, and address biases. 


## Citations

If you use this data or the paper, please cite the below (to be adjusted when NeurIPS official Bibtex is released)

```
@incollection{NeurIPS2019_Raff,
title = {A Step Toward Quantifying Independently Reproducible Machine Learning Research},
author = {Raff, Edward},
booktitle = {Advances in Neural Information Processing Systems},
year = {2019},
publisher = {Curran Associates, Inc.},
url = {https://arxiv.org/pdf/1909.06674.pdf}
}
```
