# Miscellaneous notes

Notes and tools that don't fit into other notes.

* [Sequencing](#sequencing)
* [Genes](#genes)
* [miRNA](#mirna)
* [Text mining](#text-mining)
* [Clustering and visualization](#clustering-and-visualization)
* [Image analysis](#image-analysis)
* [Teaching](#teaching)
* [Lab notes](#lab-notes)
  * [Notes from Jeff Leek](#notes-from-jeff-leek)
* [Misc](#misc)

## Sequencing

- `SequencEnG` - Hierarchical summary of 66 sequencing technologies, computational algorithms, references to papers.http://education.knoweng.org/sequenceng/
    - Zhang, Y., Manjunath, M., Kim, Y., Heintz, J., and Song, J.S. (2019). SequencEnG: an interactive knowledge base of sequencing techniques. Bioinformatics 35, 1438–1440.

- Which human reference genome to use? https://lh3.github.io/2017/11/13/which-human-reference-genome-to-use

- Long list of bioinformatics tools developed by IHEC Int'l Human Epigenome Consortium researchers, http://ihec-epigenomes.org/research/tools/

- `adapters` - Adapters for trimming. https://github.com/stephenturner/adapters

- `bamcov`, Quickly calculate and visualize sequence coverage in alignment files in command line. https://github.com/fbreitwieser/bamcov

- `bamcount` - BigWig and BAM utilities, coverage, by Ben Langmead. https://github.com/BenLangmead/bamcount

- `bigwig-nim` - single static binary + liberal license of tool to convert bed to bigwig (and back) and get fast coverage stats from bigwig, by Brent Pedersen, https://github.com/brentp/bigwig-nim, [Source](https://twitter.com/brent_p/status/1162765386548305923?s=03)

- `cgpBigWig` - Package of C scripts for generation of BigWig coverage files. https://github.com/cancerit/cgpBigWig

- `indexcov` - Quickly estimate coverage from a whole-genome bam or cram index. https://github.com/brentp/goleft/tree/master/indexcov
- `covviz` - calculate and view coverage based variation, demo at https://brwnj.github.io/covviz/. https://github.com/brwnj/covviz

- `fastq-pair` - Match up paired end fastq files quickly and efficiently. https://github.com/linsalrob/fastq-pair

- `GenomicScores` - store and access genomewide position-specific scores, like conservation scores. https://bioconductor.org/packages/release/bioc/vignettes/GenomicScores/inst/doc/GenomicScores.html

- Illumina Instrument Type from fastq, https://www.biostars.org/p/198143/


## Genes

- List of gene lists for genomic analyses. https://github.com/macarthur-lab/gene_lists
- Python package for interacting with SRAdb and downloading datasets from SRA, https://github.com/saketkc/pysradb, documentation, https://www.saket-choudhary.me/pysradb/
- Extract 3'UTR, 5'UTR, CDS, Promoter, Genes, Introns etc from GTF files, https://github.com/saketkc/gencode_regions
- Extract intron boundaries per transcript, https://gist.github.com/hiraksarkar/ce8a71a6953cb4e9823d868c283bf99d
- `CHESS` - database of novel genes, identified from GTeX data, protein-coding and lncRNA. http://ccb.jhu.edu/chess/
- GTEx Visualizations https://gtexportal.org, https://github.com/broadinstitute/gtex-viz
- Chromosome visualization with D3.js, ideogram. https://github.com/eweitz/ideogram. Wrappers for various languages, including R, https://github.com/freestatman/ideogRam. Examples, https://eweitz.github.io/ideogram/
- OGEE, Online GEne Essentiality database for multiple organisms, including human and mouse. http://ogee.medgenius.info/browse/
- HGNChelper - Identify and Correct Invalid HGNC Human Gene Symbols and MGI Mouse Gene Symbols. https://waldronlab.io/HGNChelper/
- Enhancer-promoter (EP) pairs from Thurman et al., (2012) were obtained from: ftp://ftp.ebi.ac.uk/pub/databases/ensembl/encode/integration_data_jan2011/byDataType/openchrom/jan2011/dhs_gene_connectivity/genomewideCorrs_above0.7_promoterPlusMinus500kb_withGeneNames_32celltypeCategories.bed8.gz
- `CREEDS` - database of manually (and automatically) extracted gene signatures. Single gene perturbations, disease signatures, single drug perturbations. Batch effect correction, when necessary. Overall, good agreement with MSigDb C2. Characteristic Direction (CD) method to detect differential genes. Browse and download data at https://amp.pharm.mssm.edu/creeds/, API access in R, http://rpubs.com/wangz10/177826
    - Wang, Zichen, Caroline D. Monteiro, Kathleen M. Jagodnik, Nicolas F. Fernandez, Gregory W. Gundersen, Andrew D. Rouillard, Sherry L. Jenkins, et al. “Extraction and Analysis of Signatures from the Gene Expression Omnibus by the Crowd.” Nature Communications 7, no. 1 (November 2016). https://doi.org/10.1038/ncomms12846.


## miRNA

- http://www.pharmaco-mir.org/ - miRNA-drug associations

- `microRNAome` - read counts for microRNAs across tissues, cell-types, and cancer cell-lines. https://bioconductor.org/packages/devel/data/experiment/html/microRNAome.html

- `miRNAmeConverter` - Convert miRNA Names to Different miRBase Versions. [https://bioconductor.org/packages/release/bioc/html/miRNAmeConverter.html](https://bioconductor.org/packages/release/bioc/html/miRNAmeConverter.html)

## Text mining

- `rentrez` - Access NCIB databases, including PubMed, from R. https://github.com/ropensci/rentrez

- `PubScore` - Automatic calculation of literature relevance of genes, https://bioconductor.org/packages/devel/bioc/html/PubScore.html

- `Adjutant` - Pubmed articles analysis, word cloud, topic clustering. https://github.com/amcrisan/Adjutant
    - Crisan, Anamaria, Tamara Munzner, and Jennifer L Gardy. “Adjutant: An R-Based Tool to Support Topic Discovery for Systematic and Literature Reviews.” Edited by Jonathan Wren. Bioinformatics, August 23, 2018. https://doi.org/10.1093/bioinformatics/bty722.

- Where to get Twitter data for academic research, blog post by Justin Littman, https://gwu-libraries.github.io/sfm-ui/posts/2017-09-14-twitter-data. Collecting, Analysing and Sharing Twitter Data, blog post by Serah Rono, http://okfnlabs.org/blog/2018/03/08/open-data-day-tweets.html

- Julia's implementation of word2vec in R https://word2vec.news-r.org, https://github.com/news-r/word2vec.r

- Text Extraction, Rendering and Converting of PDF Documents https://docs.ropensci.org/pdftools, https://github.com/ropensci/pdftools

- Tesseract OCR engine in R, https://cran.r-project.org/web/packages/tesseract/vignettes/intro.html

## Clustering and visualization

- `circlize` - Circular visualization in R, https://github.com/jokergoo/circlize

- `Clust` - Python script for gene clustering without strict requirement of all genes being assigned to clusters. Also, clustering across multiple datasets to find similar patterns. Timecourse clustering. Outperforms seven clustering techniques (cross-clustering, k-means, SOM, MCL, HC, Click, WGCNA) using seven metrics (Davies-Bouldin, BIC, silhouette, Calinski-Harabasz, Ball-Hall, Xu, within-between indices). https://github.com/BaselAbujamous/clust
    - Abu-Jamous, Basel, and Steven Kelly. “Clust: Automatic Extraction of Optimal Co-Expressed Gene Clusters from Gene Expression Data.” Genome Biology 19, no. 1 (December 2018). https://doi.org/10.1186/s13059-018-1536-8.

- Venn diagrams, Twitter tread. https://twitter.com/tangming2005/status/1141733431253975040

## Image analysis

- The Engauge Digitizer tool accepts image files (like PNG, JPEG and TIFF) containing graphs, and recovers the data points from those graphs. http://markummitchell.github.io/engauge-digitizer/

- Medical image analysis framework merging ANTsR and deep learning. A collection of deep learning architectures ported to the R language and tools for basic medical image processing. Based on keras and tensorflow with cross-compatibility with our python analog ANTsPyNet. https://github.com/ANTsX/ANTsRNet

## Teaching

- Free online data science environment, Jupyter notebooks for Python, R, Julia etc. https://notebooks.rmotr.com/. An extension to add exercises with hidden answers: https://github.com/rmotr/jupyterlab-solutions

- GitHub Classroom tutorials for teachers https://github.com/jfiksel/github-classroom-for-teachers and students https://github.com/jfiksel/github-classroom-for-students

- RStudio Cloud - shared projects, assignments, private spaces. Guide, https://rstudio.cloud/learn/guide, and the main page, https://rstudio.cloud/. "RStudio Cloud in the Classroom" - webinar on using RStudio Cloud.

- Wilson, Greg. “Ten Quick Tips for Creating an Effective Lesson.” PLoS Computational Biology 15, no. 4 (April 2019): e1006915. https://doi.org/10.1371/journal.pcbi.1006915. - Guide for effective teaching, learning principles, tips for creating lessons. Define your audience, spread and mix topics, formulate problems, make summaries, appeal to visual and linguistic learning channels, identify and correct learner's mistakes, motivate and avoid demotivation, be inclusive.

## Lab notes

- Mega list of 1 on 1 meeting questions compiled from a variety to sources, https://github.com/VGraupera/1on1-questions

- Rules for good lab environment: promote the well-being of all, allow schedule flexibility, show gratitude, treat all like teammates, foster collaborative environment, adjust to unique needs of everyone, respect official off-work days, acknowledge achievements, accept failure and celebrate success, promote the professional development. Twitter thread: https://twitter.com/ftmaestre/status/1053154881077415936
    - Maestre, Fernando T. “Ten Simple Rules towards Healthier Research Labs.” Edited by Fran Lewitter. PLOS Computational Biology 15, no. 4 (April 11, 2019): e1006914. https://doi.org/10.1371/journal.pcbi.1006914.

- Code of Conduct, https://github.com/AlexsLemonade/RNA-Seq-Exercises/blob/master/code-of-conduct.md

- [Applicant_note.md](Applicant_note.md) - Advice to PhD student/post-doc applicants. [Source](https://twitter.com/davidsuter_epfl/status/1141959559654846464?s=20), [Code to extract text](https://gist.github.com/mdozmorov/eb9f8fbca57888fa6481be3d07441827)

- The PI spectrum, by Jean Fan. https://jean.fan/2019/05/09/pi-spectrum.html
- JEFworks Lab Transparency in Resource Allocation. https://jef.works/assets/docs/transparency
- JEFworks A Guide to Scientific Peer Review. https://jef.works/blog/2020/03/23/a-guide-to-scientific-peer-review/

- 10 ingredients for a successful supervisor/PhD student relationship. https://www.elsevier.com/connect/10-ingredients-for-a-successful-supervisor-phd-student-relationship

- Lists of format-free journals, journals conforming to Your Paper Your Way (YPYW) initiative, the bioRxiv to journals or peer review services (B2J) initiative. https://asntech.github.io/format-free-journals/

- Nature collection of articles on Research leadership, https://www.nature.com/collections/cigjfacfbg

- `awesome-expectations` - Examples of academic labs with explicitly stated expectations of themselves and their mentees in the form of written lab manuals. https://github.com/olgabot/awesome-expectations

### Notes from Jeff Leek

- [Writing your first academic paper](https://github.com/jtleek/firstpaper)
- [Reading academic papers](https://github.com/jtleek/readingpapers)
- [The Leek group guide to genomics papers](https://github.com/jtleek/genomicspapers)
- [Writing reviews of academic papers](https://github.com/jtleek/reviews)
- [Advanced Data Science knowledge and skills](https://github.com/jtleek/ads2020)

## Misc

- [Twitter-based Poster Session](http://photonicsonlinemeetup.org/poster-session/) - [instructions](http://photonicsonlinemeetup.org/wp-content/uploads/2020/04/Guidelines-for-poster-presentations.pdf) for organizing virtual poster session, and the [PPT template](http://photonicsonlinemeetup.org/wp-content/uploads/2020/04/poster-template.pptx) for making a 4-panel poster that [looks good on Twitter](http://photonicsonlinemeetup.org/wp-content/uploads/2020/04/poster-example.pdf). Created by [@PhotonicsMeetup](https://twitter.com/photonicsmeetup?lang=en)

- `googledrive` - an R package interface to Google Drive. https://googledrive.tidyverse.org. Alternative: Google Drive direct download of big files, https://github.com/circulosmeos/gdown.pl

- Using permutations, the recommended threshold was recently increased to $2.4 \times 10^{-7}$ for the 450K array and $3.6 \times 10^{-8}$ for genome-wide measurements. From Saffari A, Silver MJ, Zavattari P, Moi L, Columbano A, Meaburn EL, et al. Estimation of a significance threshold for epigenome-wide association studies. Genet Epidemiol. 2018;42(1):20-33.

- `philentropy`: Similarity and Distance Quantification Between Probability Functions. Computes 46 optimized distance and similarity measures for comparing probability functions. https://cran.r-project.org/web/packages/philentropy/index.html

- Project documentation with Markdown. http://www.mkdocs.org, GitHub, https://github.com/mkdocs/mkdocs/

- https://goodekat.github.io/ggResidpanel/ - ggResidpanel is an R package for creating panels of diagnostic plots for a model using ggplot2 and interactive versions of the plots using plotly.

- Fast ICD-10 and ICD-9 comorbidities, decoding and validation in R https://jackwasey.github.io/icd/, https://github.com/jackwasey/icd

- Easily generate information-rich, publication-quality tables from R https://gt.rstudio.com, https://github.com/rstudio/gt
- Presentation-Ready Data Summary and Analytic Result Tables http://www.danieldsjoberg.com/gtsummary, https://github.com/ddsjoberg/gtsummary

- Screencast keystrokes, record. https://twitter.com/dataandme/status/1163821213334102016?s=03