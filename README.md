# Classification and Cross-Platform Validation Using DNA Methylation Data
This project presents a valuable opportunity to apply advanced machine learning methods to a clinically
relevant health informatics problem, showcasing the ability to address the challenges associated with high-
dimensional epigenomic data (i.e., DNA methylation). The task emphasises feature selection and
dimensionality reduction, data visualisation (e.g. PCA, t-SNE, UMAP), supervised classification model
development, and rigorous analytical evaluation, including assessment of model robustness across
different methylation array platforms (Illumina 450K and EPIC).
## Objective:
To develop and evaluate supervised classification models capable of predicting molecular subtypes of
medulloblastoma using DNA methylation data, and to assess the robustness and generalisability of the
model across Illumina 450K and EPIC platforms.
## Data:
The dataset used in this project is derived from multiple peer-reviewed studies on DNA methylation-based
molecular subtyping of medulloblastoma, with particular emphasis on the international consensus
definition of Group 3 and Group 4 subtypes.
In particular, this coursework builds upon:
- The international meta-analysis establishing eight consensus molecular subtypes of Group 3 and
Group 4 medulloblastoma, published in Acta Neuropathologica (2019), which provides the
reference subtype labels used in this project:
(Sharma et al., Second-generation molecular subgrouping of medulloblastoma)
https://link.springer.com/article/10.1007/s00401-019-02020-0
- A subsequent machine learning study developing a cross-platform DNA methylation classifier
capable of predicting these eight subtypes using both Illumina HumanMethylation450 (450K) and
Illumina EPIC (850K) arrays. https://arxiv.org/pdf/2510.02416?
The dataset consists of:
- DNA methylation beta values (ranging from 0 to 1)
- Samples assayed on Illumina 450K and EPIC platforms
- Molecular subtype labels corresponding to the eight consensus Group 3/4 subtypes
The data are high-dimensional, containing tens of thousands of CpG probes/sites per sample, and therefore
require careful feature selection, preprocessing, and dimensionality reduction prior to classification.
