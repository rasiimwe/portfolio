# Portfolio

---
## Sample Projects:

#### [Whole genome profiling for stratifying and deriving insights into the underpinnings and treatment of triple negative breast cancer](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

This research project was aimed at developing, optimizing and utilizing a database-driven approach to integrate, store, query, statistically analyze and visualize large-scale whole genome profiling data from tumors of breast cancer patients to support inferences of the genomic events underpinning a patient’s disease while providing an in-depth understanding and elucidation of the landscape of mutations occurring in patient genomes that may reflect specific mutational processes as targetable vulnerabilities in the treatment of this, and other human cancers. Please see [publication](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4) for details on methods applied for this project. 

[<img src="images/TNBC_project.png?raw=true"/>](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

---

#### {\color{red}Single-cell transcriptomics (scRNA-Seq) Projects}
#### Single-cell transcriptomics (scRNA-Seq) Project \textcolor{red}

<span style="color: red;">Single-cell transcriptomics (scRNA-Seq) Project</span>

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

Over the past year I have had the privilege of conducting single‐cell RNA sequencing analyses of millions of cells from over 100 libraries and experiments including single nuclear RNA seq (snRNA-Seq) analyses. Transcriptomic profiling of complex tissues identifies known and novel features of the transcriptome and provides insights into tissue cell type diversity and dynamics that have a great impact on disease diagnostics, prevention, and drug discovery, all based on measures of gene and transcript abundance.

I have also conducted analyses of CITE-seq data based on transcriptome and cell surface protein epitope measurements while leveraging available antibodies on a single cell level. Studying cells concurrently at transcriptomic and proteomic levels can offer unprecedented insights into new cell types, disease states, or other conditions.

I have also conduced single cell ATAC-Seq analyses to study cell type-specific chromatin accessibility in tissue samples containing heterogeneous cellular populations for the identification of transcription factors that are active in a phenotype or condition being investigated. The transcription factor binding sites and positions of nucleosomes identified from the analysis of ATAC-Seq data, potentially allows for the elucidation of important genetic pathways in a samples.

Besides sc/sn-RNA-, CITE- and ATAC-seq, I have worked with spatial transcriptomics to characterize transcriptional patterning and regulation in tissues. I have also worked with [Cell2location]( https://www.nature.com/articles/s41587-021-01139-4) to map single-cell RNA-seq (scRNA-seq) profiles to spatial transcriptomic data.
I have also worked with tools such as [soupX]( https://academic.oup.com/gigascience/article/9/12/giaa151/6049831) to remove ambient RNA, [scrublet](https://www.cell.com/cell-systems/fulltext/S2405-4712(18)30474-5?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2405471218304745%3Fshowall%3Dtrue) to remove doublets, [monocle](http://cole-trapnell-lab.github.io/monocle-release/) for single cell trajectory inference and [souporcell](https://www.nature.com/articles/s41592-020-0820-1) and [demuxlet](https://www.nature.com/articles/nbt.4042) for sample identity deconvolution. 

All analyses are conducted using R and Python using respective packages to accomplish all necessary tasks.


<img src="images/scRNA-Seq1.pdf?raw=true"/>
<!---<img src="https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq1.pdf">-->
<!--- (https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq1.pdf)-->

<img src="images/scRNA-Seq2.pdf?raw=true"/>
<!---<img src="https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq2.pdf">-->

<!--- (https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq2.pdf)-->

---

### Improving read alignment

Allele specific expression (ASE) refers to the preferential expression of one allele over the other in a diploid genome. In humans, the widespread allelic variation at both gene and single nucleotide level between individuals is commonly associated with complex traits. ASE analysis, quantifies the relative expression of two alleles and when integrated with expression quantitative trait locus (eQTL) analysis is a powerful tool for identifying biologically meaningful regulatory signals such as imprinting and cis-regulated gene expression variations that underlie phenotypic differences among individuals. RNA-seq can be used to measure allele-specific expression (ASE) by assigning sequence reads to individual alleles; however, this analysis remains limited by mapping bias, where sequence reads are aligned to a conventional linear reference genome with each position represented only by the reference/most abundant allele. Together with Dr. Alexander Dobin, we are working on improving STAR, a widely adopted read alignment tool to reduce reference bias. 

<img src="images/Alignment_project_cropped.png?raw=true"/>

<!--- <img src="drawing.jpg" alt="drawing" style="width:200px;"/> -->


#### [Understanding tissue-specific temporal changes after SIV infection to guide HIV treatment](https://github.com/rasiimwe/Galaxy_Transcriptomics)

Human immunodeficiency virus (HIV) has continued to be a public health issue on a global scale and over 35 million people have died due to the onset of acquired immunodeficiency syndrome (AIDS)-related diseases. Early diagnosis is crucial as it enables the control of infection via antiretroviral therapy in addition to reducing the risk of transmission, however, it is estimated that half of the patients with HIV worldwide are “late-presenters” because of the asymptomatic nature of the virus; a rationale for which more knowledge is needed to understand the early stages of HIV infection, and immune response. Simian immunodeficiency virus (SIV), a retrovirus infecting nonhuman primates, has similar symptoms and viral life cycle to that of HIV. Phylogenetic analysis also shows that SIV and HIV are ancestrally related and are closely related in viral replication and propagation, making it a good model for understanding early development of infection. This project aimed at evaluating tissue-specific transcriptomic changes in the first ten days after SIV infection in rhesus monkeys. We leveraged various statistical methods such as fitting linear models, cluster analysis, PCA, gene enrichment and pathway analysis, using various CRAN/Bioconductor R packages, and found that significant transcriptomic changes occur as early as day 1 post infection throughout host tissues. This knowledge is crucial for development of treatment as well as vaccines and more effective post-exposure prophylaxis drugs. Please visit the [GitHub project repo](https://github.com/rasiimwe/Galaxy_Transcriptomics/blob/main/README.md) for more details.

[<img src="images/HIV_project.png?raw=true"/>](https://github.com/rasiimwe/Galaxy_Transcriptomics/blob/main/Poster/Poster-FINAL.pdf)

---
#### [Database design, development and optimization](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

Experience with database design, development, optimization and administration. I have worked with Microsoft Access, Oracle, MySQL and PostgreSQL Database Management Systems (DBMSs). 

[<img src="images/Databases.png?raw=true"/>](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

---

#### [DNA methylation and Genotyping Data Analyses](https://assets.researchsquare.com/files/rs-764250/v1_covered.pdf?c=1628604236)

Provided below is an overview of extracts from developed data preprocessing pipelines and up/downstream analyses on various projects (some ongoing). The images shown are extracts from either up/downstream project data analyses such as those conducted in this [manuscript](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-021-00428-1). Similar projects I have conducted in this domain (DNA methylation and genotyping) follow similar pipelines and analyses - some soon to be published and released into the public domain as well. 

<img src="images/DNAm.png?raw=true"/>

---

#### [Using Machine Learning to Predict Breast Cancer](https://github.com/rasiimwe/Code_Examples/blob/main/Predicting_Breast_Cancer_Using_Machine_Learning.ipynb)

This project utilizes the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) for predictive analysis in breast cancer. Key tools largely used include: Jupyter Notebook, Python - numpy, pandas, matplotlib, plotly, seaborn and scikit-learn and plotly to run and compare Logistic Regression, Random Forest, KNeighbors, SVC, DecisionTree, GradientBoosting, AdaBoost, and XGB classification models.

[<img src="images/Breast_Cancer_Prediction.png?raw=true"/>](https://github.com/rasiimwe/Code_Examples/blob/main/Predicting_Breast_Cancer_Using_Machine_Learning.ipynb)



---

#### Shiny Apps and Dashboards

I have developed a number of Shiny-based tools, apps and/dashboards, most of which are internal to the institutions I have worked with. Below are some of the few examples that are public. I have also had some experience conducting data analysis and visualizations using Dash (Python).

Not accessible publicly, but this app can be viewed in my [thesis (pages 75 - 87)](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

[<img src="images/Shinyapp1.png?raw=true"/>](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

Below is another tool that is under development.  It compares DNA methylation patterns in immune cell types between cord and adult blood:

<img src="images/Shinyapp2.png?raw=true"/>

<!--- 
Developed for training purposes, this is an elementary [dashboard](https://rasiimwe.shinyapps.io/NHS_A_and_E_Example_App/) that utilises a subset of the NHS England A&E (Accident and Emergency) dataset, and shows the weekly and monthly attendances and emergency admissions in a specified period for all A&E types.

[<img src="images/shiny4.png?raw=true"/>](https://rasiimwe.shinyapps.io/NHS_A_and_E_Example_App/)
-->

---

### Publications
- Asiimwe, R. (2019). [Database-driven whole genome profiling for stratifying Triple Negative Breast Cancers (TNBC)](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4) (T). University of British Columbia. Retrieved from https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4
- Asiimwe, R., Lam, S., Leung, S., Wang, S., Wan, R., Tinker A., McAlpine, N, J., Woo, M., Huntsman, D., Talhouk, A.  [From biobank and data silos into a data commons: convergence to support translational medicine](https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-021-03147-z). *Journal of Translational Medicine* 
- Konwar, C., Asiimwe, R., Inkster, M, A., Merrill, S., Negri, L, G., Aristizabal, J, Ma., Rider, C., MacIsaac, L, J., Carlsten, C., Kobor, S, M. [Risk-focused differences in molecular processes implicated in SARS-CoV-2 infection: Corollaries in DNA methylation and gene expression](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-021-00428-1). *Epigenetics & Chromatin* 
- Asiimwe, R., Konwar, C., Merrill, S., MacIsaac, L, J., Katia, R., Crowell, E, S., Kobor, S, M., Conradt, E. Placental DNA methylation changes associated with opioid use during pregnancy. (In preparation for submission) 


---
<p style="font-size:11px">Page powered by <a href="https://jekyllrb.com">jekyll</a></p>
<!-- Remove above link if you don't want to attibute -->
