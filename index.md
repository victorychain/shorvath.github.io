## Welcome!

---

I am a Professor of [Human Genetics](https://medschool.ucla.edu/human-genetics) and Biostatistics at [University of California, Los Angeles](https://www.ucla.edu). My methodological research area lies at the intersection of biostatistics, bioinformatics, computational biology, cancer research, genetics, epidemiology, machine learning, and systems biology. My group applies these methods to study a broad spectrum of diseases, e.g. aging research, cancer, cardiovascular disease, HIV, Huntington’s disease, neurodegenerative diseases.

---

### Projects

**Systems biology and systems genetics**: My group develops and applies methods for analyzing and integrating gene expression-, DNA methylation-, microRNA, genetic marker-, and complex phenotype data. In particular, we developed weighted correlation network analysis (also known as weighted gene co-expression network analysis WGCNA), which is a systems biologic data analysis method for analyzing high dimensional “-omics” data. These methods also lend themselves for comparing different species at the genomic level. A lot of material including articles, R software tutorials, and youtube lectures can be found [here](https://horvath.genetics.ucla.edu/CoexpressionNetwork/). [R package: WGCNA](/https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/)
<img src="images/wgcna.png?raw=true"/>

---

**Mammalian DNA Methylation Array**: Infinium methylation arrays are widely used to robustly measure methylation of DNA in humans. However, such arrays are not available for the vast majority of non-human mammals. Moreover, even if species-specific arrays were available, probe differences between them would confound cross-species comparisons. To address these challenges, we developed the Mammalian Methylation Array, a single custom Infinium array that measures cytosine methylation levels of over 35 thousand CpG sites that are well conserved across species within the mammalian class. By design, the probes on the array tolerate cross-species mutations. To design the array, we developed the Conserved Methylation Array Probe Selector (CMAPS) algorithm, which takes as input a multi-species sequence alignment and probe design constraints. A greedy search algorithm was used to identify oligonucleotide sequences (probes) with high coverage across different mammalian species. We annotate the probes on the array with respect to genes in 159 different species and provide details on the sequence context including CpG island status and chromatin states. Our calibration experiments demonstrate the high fidelity of this array in humans, rats, and mice. The mammalian methylation array has several strengths: it applies to all mammalian species even those that have not yet been sequenced, it provides deep coverage of specific cytosines facilitating the development of highly robust epigenetic biomarkers, and it covers highly conserved CpGs which greatly increases the probability that biological insights gained in one species will readily translate to others. The mammalian methylation array is expected to find many applications in preclinical studies, comparative biology, and epigenetic studies of aging and development. [bioRxiv](https://doi.org/10.1101/2021.01.07.425637)
<img src="images/chip_paper.png?raw=true"/>

---

[Epigenetic Predictors of Mammalian Lifespans](/images/mammal_predictors.jpg)
<img src="images/mammal_predictors.jpg?raw=true"/>

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attribute -->
