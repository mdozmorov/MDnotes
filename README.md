# Miscellaneous notes

Notes and tools that don't fit into other notes.

* [All notes](#all-notes)
* [Genes](#genes)
* [Sequencing](#sequencing)
* [Text mining](#text-mining)
* [Integrative](#integrative)
* [Machine learning](#machine-learning)
* [Teaching](#teaching)
* [Data](#data)
* [Misc](#misc)

## All notes

- [Lists of bioinformatics, biostatistics, data science, machine learning resources](https://github.com/mdozmorov/blogs)
- [Brain_genomic_data](https://github.com/mdozmorov/Brain_genomic_data)
- [Cancer_notes](https://github.com/mdozmorov/Cancer_notes)
- [ChIP-seq_notes](https://github.com/mdozmorov/ChIP-seq_notes)
- [DNA_notes](https://github.com/mdozmorov/DNA_notes)
- [GWAS notes](https://github.com/mdozmorov/gwas2bed)
- [HiC_data](https://github.com/mdozmorov/HiC_data)
- [HiC_tools](https://github.com/mdozmorov/HiC_tools)
- [Immuno_notes](https://github.com/mdozmorov/Immuno_notes)
- [Methylation_notes](https://github.com/mdozmorov/Methylation_notes)
- [Microbiome_notes](https://github.com/mdozmorov/Microbiome_notes)
- [RNA-seq_notes](https://github.com/mdozmorov/RNA-seq_notes)
- [scRNA-seq_notes](https://github.com/mdozmorov/scRNA-seq_notes)
- [SNP_notes](https://github.com/mdozmorov/SNP_notes)

- [Grant_notes](https://github.com/mdozmorov/Grants_notes)
- [Conference_notes](https://github.com/mdozmorov/Conference_notes)
- [Jobs_notes](https://github.com/mdozmorov/Jobs_notes)

## Genes

- List of gene lists for genomic analyses. https://github.com/macarthur-lab/gene_lists
- Python package for interacting with SRAdb and downloading datasets from SRA, https://github.com/saketkc/pysradb, documentation, https://www.saket-choudhary.me/pysradb/
- Extract 3'UTR, 5'UTR, CDS, Promoter, Genes, Introns etc from GTF files, https://github.com/saketkc/gencode_regions
- Extract intron boundaries per transcript, https://gist.github.com/hiraksarkar/ce8a71a6953cb4e9823d868c283bf99d
- `CHESS` - database of novel genes, identified from GTeX data, protein-coding and lncRNA. http://ccb.jhu.edu/chess/
- GTEx Visualizations https://gtexportal.org, https://github.com/broadinstitute/gtex-viz
- Chromosome visualization with D3.js, ideogram. https://github.com/eweitz/ideogram. Wrappers for various languages, including R, https://github.com/freestatman/ideogRam. Examples, https://eweitz.github.io/ideogram/
- OGEE, Online GEne Essentiality database for multiple organisms, including human and mouse. http://ogee.medgenius.info/browse/


## Sequencing

- Long list of bioinformatics tools developed by IHEC Int'l Human Epigenome Consortium researchers, http://ihec-epigenomes.org/research/tools/

- `adapters` - Adapters for trimming. https://github.com/stephenturner/adapters

- `bamcov`, Quickly calculate and visualize sequence coverage in alignment files in command line. https://github.com/fbreitwieser/bamcov

- `indexcov` - Quickly estimate coverage from a whole-genome bam or cram index. https://github.com/brentp/goleft/tree/master/indexcov

- `fastq-pair` - Match up paired end fastq files quickly and efficiently. https://github.com/linsalrob/fastq-pair

## Text mining

- `Adjutant` - Pubmed articles analysis, word cloud, topic clustering. https://github.com/amcrisan/Adjutant
    - Crisan, Anamaria, Tamara Munzner, and Jennifer L Gardy. “Adjutant: An R-Based Tool to Support Topic Discovery for Systematic and Literature Reviews.” Edited by Jonathan Wren. Bioinformatics, August 23, 2018. https://doi.org/10.1093/bioinformatics/bty722.

- Where to get Twitter data for academic research, blog post by Justin Littman, https://gwu-libraries.github.io/sfm-ui/posts/2017-09-14-twitter-data. Collecting, Analysing and Sharing Twitter Data, blog post by Serah Rono, http://okfnlabs.org/blog/2018/03/08/open-data-day-tweets.html


## Integrative

- `JIVE` - Joint and Individual Variation Explained. Decomposition of (X) multiple (i) omics datasets into three terms: low-rank (constrained) matrices capturing joint variation (J), plus structured variation (A_i) and residual noise. Data are row-centered and scaled by its total variation. Main constrain: the rows of joint and individual matrices should be orthogonal. Estimate matrices by iteratively minimizing ||R||^2 (R=X-J-A). Relationship to PCA, CCA, PLS. Illustrated on TCGA GBM gene expression, methylation, and miRNA data, with interpretation. Matlab code https://genome.unc.edu/jive/, r.jive package, https://cran.r-project.org/web/packages/r.jive/vignettes/BRCA_Example.html
    - Lock, Eric F., Katherine A. Hoadley, J. S. Marron, and Andrew B. Nobel. “JOINT AND INDIVIDUAL VARIATION EXPLAINED (JIVE) FOR INTEGRATED ANALYSIS OF MULTIPLE DATA TYPES.” The Annals of Applied Statistics 7, no. 1 (March 1, 2013): 523–42. https://doi.org/10.1214/12-AOAS597.

## Machine learning

- `janggu` - Janggu is a python package that facilitates deep learning in the context of genomics. FASTA/BAM/BIGWIG/BED/GFF as input, trained neural network for classification as an output. [https://github.com/BIMSBbioinfo/janggu](https://github.com/BIMSBbioinfo/janggu)

- `maui` - Multi-omics Autoencoder Integration. Latent factors from different data types (stacked variational autoencoders), and their clustering, testing for association with survival. Tested vs. latent factors extracted using Multifactor Analysis (MFA) and iCluster+, on TCGA colorectal cancer RNA-seq, SNPs, CNVs. https://github.com/bimsbbioinfo/maui
    - Ronen, Jonathan, Sikander Hayat, and Altuna Akalin. “Evaluation of Colorectal Cancer Subtypes and Cell Lines Using Deep Learning,” November 12, 2018. https://doi.org/10.1101/464743.

- "Gradient Boosting Essentials in R Using XGBOOST", http://www.sthda.com/english/articles/35-statistical-machine-learning-essentials/139-gradient-boosting-essentials-in-r-using-xgboost/


## Teaching

- Free online data science environment, Jupyter notebooks for Python, R, Julia etc. https://notebooks.rmotr.com/. An extension to add exercises with hidden answers: https://github.com/rmotr/jupyterlab-solutions

- GitHub Classroom tutorials for teachers https://github.com/jfiksel/github-classroom-for-teachers and students https://github.com/jfiksel/github-classroom-for-students

- RStudio Cloud - shared projects, assignments, private spaces. Guide, https://rstudio.cloud/learn/guide, and the main page, https://rstudio.cloud/

## Data

- CORGIS Datasets Project - The Collection of Really Great, Interesting, Situated Datasets. https://think.cs.vt.edu/corgis/

-  Inter-university Consortium for Political and Social Research (ICPSR) provides leadership and training in data access, curation, and methods of analysis for the social science research community. https://www.icpsr.umich.edu/icpsrweb/ICPSR/

- Google dataset search, https://toolbox.google.com/datasetsearch. Overview, https://www.blog.google/products/search/making-it-easier-discover-datasets/

- U.S. General Services Administration. 2018. The home of the U.S. Government’s open data. https://www.data.gov/

## Misc

- Using permutations, the recommended threshold was recently increased to $2.4 \times 10^{-7}$ for the 450K array and $3.6 \times 10^{-8}$ for genome-wide measurements. From Saffari A, Silver MJ, Zavattari P, Moi L, Columbano A, Meaburn EL, et al. Estimation of a significance threshold for epigenome-wide association studies. Genet Epidemiol. 2018;42(1):20-33.

- `philentropy`: Similarity and Distance Quantification Between Probability Functions. Computes 46 optimized distance and similarity measures for comparing probability functions. https://cran.r-project.org/web/packages/philentropy/index.html

- Project documentation with Markdown. http://www.mkdocs.org, GitHub, https://github.com/mkdocs/mkdocs/