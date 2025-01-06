# SPECK
![alt text](https://academic.oup.com/view-large/figure/409206348/vbad073f1.tif)
## Abstract
The rapid development of single-cell transcriptomics has revolutionized the study of complex tissues. Single-cell RNA-sequencing (scRNA-seq) can 
profile tens-of-thousands of dissociated cells from a tissue sample, enabling researchers to identify cell types, phenotypes and interactions that 
control tissue structure and function. A key requirement of these applications is the accurate estimation of cell surface protein abundance. Although 
technologies to directly quantify surface proteins are available, these data are uncommon and limited to proteins with available antibodies. While 
supervised methods that are trained on Cellular Indexing of Transcriptomes and Epitopes by Sequencing data can provide the best performance, these 
training data are limited by available antibodies and may not exist for the tissue under investigation. In the absence of protein measurements, 
researchers must estimate receptor abundance from scRNA-seq data. Therefore, we developed a new unsupervised method for receptor abundance estimation 
using scRNA-seq data called SPECK (Surface Protein abundance Estimation using CKmeans-based clustered thresholding) and primarily evaluated its performance 
against unsupervised approaches for at least 25 human receptors and multiple tissue types. This analysis reveals that techniques based on a thresholded 
reduced rank reconstruction of scRNA-seq data are effective for receptor abundance estimation, with SPECK providing the best overall performance.
