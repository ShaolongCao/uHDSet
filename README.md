# uHDSet
R code for uHDSet test and uFineMap test.

# Abstract
In searching for genetic variants for complex diseases with deep sequencing data, genomic marker sets of high-dimensional genotypic data and sparse functional variants are quite common. Existing sequence association tests are incapable of identifying such marker sets or individual causal loci, although they appeared powerful to identify small marker sets with dense functional variants. In sequence association studies of admixed individuals, cryptic relatedness and population structure are known to confound the association analyses.

We here propose a unified marker wise test (uFineMap) to accurately localize causal loci and a unified high-dimensional set based test (uHDSet) to identify high-dimensional sparse associations in deep sequencing genomic data of multi-ethnic individuals with random relatedness. These two novel tests are based on scaled sparse linear mixed regressions with Lp (0 < p < 1) norm regularization. They jointly adjust for cryptic relatedness, population structure and other confounders to prevent false discoveries and improve statistical power for identifying promising individual markers and marker sets that harbor functional genetic variants of a complex trait.

# Installation
install.packages("uHDSet_1.0.zip")
Source code is "uHDSet_package.R"
An example is attached: "example.R"

# Reference
Shaolong Cao, Huaizhen Qin, Alexej Gossmann, Hong-Wen Deng and Yu-Ping Wang. “Unified tests for fine scale mapping and identifying sparse high-dimensional sequence associations”, Bioinformatics, (2016) 32 (3): 330-337 doi:10.1093/bioinformatics/btv586
