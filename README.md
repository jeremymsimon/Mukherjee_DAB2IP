# "DAB2IP expression among TCGA-BRCA tumor samples"  
3/03/2023


The code presented here supports the Mukherjee _et al_ publication entitled 
"DAB2IP-Low Luminal A Breast Cancer Patients Exhibit Gene Expression Profiles Overlapping with More Aggressive Cancer Partly Related to IKK/NF-kB Activation" (2023),
_under review_. The steps outlined here recapitulate the analysis performed for preparation of the figures, 
however, the figures will be subtly different given slight changes in software versions that occurred during manuscript preparation.

The data utilized here were obtained from cBioPortal in February 2019 corresponding to the PanCan Atlas 2018 release and Firehouse Legacy data. 
The latter contains ER/PR/HER2 status for each patient sample.

Note that the GDC portal no longer includes HTseq gene quantifications but rather includes `augmented_star_gene_counts`, which should be similar,
and RNA-seq data also now utilize RSEM whereas the data used here do not.

The fully rendered `RMarkdown` html is deployed here:  
https://jeremymsimon.github.io/Mukherjee_DAB2IP/TCGA-BRCA_DAB2IP_github.html
