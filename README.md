# Miscellaneous notes

Notes and tools that don't fit into other notes.

* [Other notes](#other-notes)
* [Genes](#genes)
* [Sequencing](#sequencing)
* [Text mining](#text-mining)
* [Integrative](#integrative)
* [Teaching](#teaching)


## Other notes

- [Lists of bioinformatics, biostatistics, data science, machine learning resources](https://github.com/mdozmorov/blogs)
- [Cancer_notes](https://github.com/mdozmorov/Cancer_notes)
- [Immuno_notes](https://github.com/mdozmorov/Immuno_notes)
- [RNA-seq_notes](https://github.com/mdozmorov/RNA-seq_notes)
- [scRNA-seq_notes](https://github.com/mdozmorov/scRNA-seq_notes)
- [HiC_data](https://github.com/mdozmorov/HiC_data)
- [HiC_tools](https://github.com/mdozmorov/HiC_tools)
- [ChIP-seq_notes](https://github.com/mdozmorov/ChIP-seq_notes)
- [DNA_notes](https://github.com/mdozmorov/DNA_notes)
- [SNP_notes](https://github.com/mdozmorov/SNP_notes)
- [Brain_genomic_data](https://github.com/mdozmorov/Brain_genomic_data)
- [Microbiome_notes](https://github.com/mdozmorov/Microbiome_notes)
- [Jobs_notes](https://github.com/mdozmorov/Jobs_notes)

## Genes

- List of gene lists for genomic analyses. https://github.com/macarthur-lab/gene_lists
- Python package for interacting with SRAdb and downloading datasets from SRA, https://github.com/saketkc/pysradb, documentation, https://www.saket-choudhary.me/pysradb/
- Extract 3'UTR, 5'UTR, CDS, Promoter, Genes, Introns etc from GTF files, https://github.com/saketkc/gencode_regions
- Extract intron boundaries per transcript, https://gist.github.com/hiraksarkar/ce8a71a6953cb4e9823d868c283bf99d
- `CHESS` - database of novel genes, identified from GTeX data, protein-coding and lncRNA. http://ccb.jhu.edu/chess/
- GTEx Visualizations https://gtexportal.org, https://github.com/broadinstitute/gtex-viz
- Chromosome visualization with D3.js, ideogram. https://github.com/eweitz/ideogram. Wrappers for various languages, including R, https://github.com/freestatman/ideogRam. Examples, https://eweitz.github.io/ideogram/

## Sequencing

- `bamcov`, Quickly calculate and visualize sequence coverage in alignment files in command line. https://github.com/fbreitwieser/bamcov

## Text mining

- `Adjutant` - Pubmed articles analysis, word cloud, topic clustering. https://github.com/amcrisan/Adjutant
    - Crisan, Anamaria, Tamara Munzner, and Jennifer L Gardy. “Adjutant: An R-Based Tool to Support Topic Discovery for Systematic and Literature Reviews.” Edited by Jonathan Wren. Bioinformatics, August 23, 2018. https://doi.org/10.1093/bioinformatics/bty722.

## Integrative

- `JIVE` - Joint and Individual Variation Explained. Decomposition of (X) multiple (i) omics datasets into three terms: low-rank (constrained) matrices capturing joint variation (J), plus structured variation (A_i) and residual noise. Data are row-centered and scaled by its total variation. Main constrain: the rows of joint and individual matrices should be orthogonal. Estimate matrices by iteratively minimizing ||R||^2 (R=X-J-A). Relationship to PCA, CCA, PLS. Illustrated on TCGA GBM gene expression, methylation, and miRNA data, with interpretation. Matlab code https://genome.unc.edu/jive/, r.jive package, https://cran.r-project.org/web/packages/r.jive/vignettes/BRCA_Example.html
    - Lock, Eric F., Katherine A. Hoadley, J. S. Marron, and Andrew B. Nobel. “JOINT AND INDIVIDUAL VARIATION EXPLAINED (JIVE) FOR INTEGRATED ANALYSIS OF MULTIPLE DATA TYPES.” The Annals of Applied Statistics 7, no. 1 (March 1, 2013): 523–42. https://doi.org/10.1214/12-AOAS597.

## Teaching

- Free online data science environment, Jupyter notebooks for Python, R, Julia etc. https://notebooks.rmotr.com/. An extension to add exercises with hidden answers: https://github.com/rmotr/jupyterlab-solutions

- GitHub Classroom tutorials for teachers https://github.com/jfiksel/github-classroom-for-teachers and students https://github.com/jfiksel/github-classroom-for-students
