<style> 
H1{color:SteelBlue !important;}
</style> 

# Portfolio


---
## Sample Projects: 

#### 1. [Whole Genome Profiling for Stratifying Triple Negative Breast Cancers (TNBC): Identifying somatic alterations in tumor genomes of TNBC patients for subgroup discovery, and the identification of potentially actionable molecular events that could provide insights into treatment options for TNBC patients](https://open.library.ubc.ca/soa/cIRcle/collections/ubctheses/24/items/1.0377717)

The aim of this research project was to design, develop, optimize and utilize a relational database to structure, integrate, store, query, mine, statistically analyze and visualize large-scale whole genome profiling data from tumors of triple negative breast cancer patients, alongside orthogonally collected clinical data. Overall, the study was conducted to support the elucidation of genomic events underpinning a patient’s disease while providing an in-depth understanding and exploration of the landscape of characteristic mutations occurring in patient genomes that may reflect specific mutational processes as targetable vulnerabilities in the treatment of TNBCs. We further stratified our cohort of TNBC patients and discovered for the first time, and to the best of our knowledge, five genomic and clinically distinct subgroups, revealed by unsupervised hierarchical clustering, based on mutation signatures, and somatic mutations in patient genomes. This work further supported the utility of the genome as a potential discriminant biomarker in subgroup discovery, from which we can draw valuable insights into options for novel therapeutic modalities, and the identification of patients most likely to respond to specific forms of treatment. Please see [publication](https://open.library.ubc.ca/soa/cIRcle/collections/ubctheses/24/items/1.0377717) for details on this project including methods applied. 

[<img src="images/TNBC_project.png?raw=true"/>](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

---

#### 2. Single-Cell RNA Sequencing (scRNA-Seq), CITE-Seq and Spatial Transcriptomics Projects

Transcriptomic profiling of complex tissues identifies known and novel features of the transcriptome and provides insights into tissue cell type diversity and dynamics that have a great impact on disease diagnostics, prevention, and drug discovery - all based on measures of gene and transcript abundance. I have had the privilege of conducting single‐cell and single-nuclear RNA sequencing analyses of thousands of cells from over 100 libraries and experiments. 

I have conducted analyses of CITE-seq datasets based on transcriptome and cell surface protein epitope measurements while leveraging available antibodies at a single cell level. Studying cells concurrently at transcriptomic and proteomic levels can offer unprecedented insights into new cell types, disease states, or other conditions.

I have also conduced single cell ATAC-Seq analyses to study cell type-specific chromatin accessibility in tissue samples containing heterogeneous cellular populations for the identification of transcription factors that are active in a phenotype or condition(s) being investigated. The transcription factor binding sites and positions of nucleosomes identified from the analysis of ATAC-Seq data, potentially allows for the elucidation of important genetic pathways in a sample.

Besides sc/sn-RNA-, CITE- and ATAC-seq, I have also worked with [spatial transcriptomics](https://github.com/PorrettLab/Spatiotemporal-immune-atlas-of-the-1st-clinical-grade-gene-edited-pig-to-human-kidney-xenotransplant/tree/main) to characterize transcriptional patterning and regulation in tissues. Besides spatial transcriptomic analyses using Seurat, I have worked with [cell2location](https://www.nature.com/articles/s41587-021-01139-4) for cell-type deconvolution of spatial transcriptomics data. I have also worked with tools such as [soupX]( https://academic.oup.com/gigascience/article/9/12/giaa151/6049831) to remove ambient RNA, [scrublet](https://www.cell.com/cell-systems/fulltext/S2405-4712(18)30474-5?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2405471218304745%3Fshowall%3Dtrue) to remove doublets, [monocle](http://cole-trapnell-lab.github.io/monocle-release/) for single cell trajectory inference and [souporcell](https://www.nature.com/articles/s41592-020-0820-1) and [demuxlet](https://www.nature.com/articles/nbt.4042) for sample identity deconvolution. 

All analyses are conducted using Python and R using respective packages to accomplish necessary tasks (Images shown below are from works I conducted and published or in preparation for publication. Code examples are on [GitHub](https://github.com/PorrettLab/Spatiotemporal-immune-atlas-of-the-1st-clinical-grade-gene-edited-pig-to-human-kidney-xenotransplant)).


<img src="images/scRNA-Seq1.pdf?raw=true"/> 
<!---  <img src="https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq1.pdf"> --->
<!--- (https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq1.pdf)--->

<img src="images/scRNA-Seq2.pdf?raw=true"/>
<!---  <img src="https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq2.pdf"> --->

<!--- (https://github.com/rasiimwe/portfolio/blob/master/images/scRNA-Seq2.pdf) --->


---

#### 3. Improving Read Alignment

Allele specific expression (ASE) refers to the preferential expression of one allele over the other in a diploid genome. In humans, the widespread allelic variation at both gene and single nucleotide levels between individuals is commonly associated with complex traits. ASE analysis, quantifies the relative expression of two alleles and when integrated with expression quantitative trait locus (eQTL) analysis is a powerful tool for identifying biologically meaningful regulatory signals such as imprinting and cis-regulated gene expression variations that underlie phenotypic differences among individuals. RNA-seq can be used to measure allele-specific expression (ASE) by assigning sequence reads to individual alleles; however, this analysis remains limited by mapping bias, where sequenced reads are aligned to a conventional linear reference genome with each position represented only by the reference/most abundant allele. Together with Dr. Dobin, we are working on assessing reference bias towards improving [STAR](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3530905/), a widely adopted read alignment tool, by reducing this bias.

<img src="images/Alignment_project_cropped.png?raw=true"/>

<!--- <img src="drawing.jpg" alt="drawing" style="width:200px;"/> -->

---

#### 4. [DNA Methylation and Genotyping Data Analyses](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-021-00428-1)

Provided below is an overview of extracts from various projects for developed data preprocessing pipelines, and up or downstream analyses such as those conducted in this [manuscript](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-021-00428-1). Projects I have conducted in this domain (DNA methylation and genotyping) follow similar [pipelines and analyses](https://github.com/kobor-lab/Public-Scripts/blob/master/COVID-19/DNAme%20preprocessing.Rmd). 

<!--- - some soon to be published and released into the public domain as well. --->

<img src="images/DNAm.png?raw=true"/>

---

#### 5. Select Machine Learning and Deep Learning Projects
##### i) [Malarial Detection Using Deep Learning: A Convolutional Neural Networks (CNN) Approach](https://github.com/rasiimwe/Code_Examples/blob/main/Malarial_Detection_Using_Deep_Learning_A_Convolutional_Neural_Networks_(CNN)_Approach.ipynb)
Malaria is an infectious and sometimes a fatal disease caused by plasmodium parasites that are transmitted through mosquito bites from female anopheles mosquitoes. Based on World Health Organization reports, there were 228 million cases and 405,000 deaths in 2018 alone. Of these deaths, Africa represented 93% and 94% of the total cases and deaths respectively. More recently (2020), it was estimated that there were 241 million cases of malaria worldwide, of which 627,000 people died from the disease, most of whom were children from sub-Saharan African countries. Many deaths have been attributed to poor health care services and lack of early and effective screening for malaria. It is therefore key to have measures for early detection, diagnosis, and treatment, to reduce these high mortality rates and the malaria burden worldwide. Current efforts towards malaria detection often involve examining a drop of a patient’s blood under a microscope. The specimen, often spread out on a thin blood smear is stained with Giemsa to give the parasites a distinctive appearance which is used to distinguish healthy from infected cells. Despite its ability to aid malaria detection, this process is quite tedious as it requires manual counting of cells by a trained technician or pathologist. Accuracy could in part depend on the technicians or expatriates examining the slides. This may leave many cases to go undiagnosed including late diagnoses that could contribute to the global malaria burden. Solving this problem is therefore imperative to aid early and accurate detection of malaria and consequently contribute to reducing severe illness and deaths caused by malaria.

The overall objective of this project was to build an automated and efficient computer vision model to detect malaria by distinguishing malaria parasitized red blood cells from uninfected red blood cells, and to classify which cells are parasitized - that is cells that have the Plasmodium parasite - and which cells are not (uninfected), in the midst of other cellular impurities. Key tools and packages used for this project include: Python (Pandas, numpy, seaborn, cv2, matplotlib, scikit-learn, tensorflow, keras), Jupyter Notebook and Google Colab.


<img src="images/Malaria_CNN.png?raw=true"/>


##### ii) [Image Processing Using Neural Networks and Convolutional Neural Networks](https://github.com/rasiimwe/Code_Examples/blob/main/Image_processing_using_Neural_Networks_and_Convolutional_Neural_Networks.ipynb)
One of the most interesting tasks in deep learning is to recognize objects in natural scenes. The ability to process visual information using machine learning algorithms can be very useful as demonstrated in various applications. This project leveraged the SVHN dataset - a popular image recognition dataset, which contains over 600,000 labeled digits cropped from street-level photos. It has been used in neural networks created by Google to improve the map quality by automatically transcribing the address numbers from a patch of pixels. The transcribed number with a known street address helps pinpoint the location of the building it represents. The objective of this project was to predict the number depicted inside the image by using Artificial or Fully Connected Feed Forward Neural Networks and Convolutional Neural Networks. Key tools and packages used for this project include: Python (Pandas, numpy, seaborn, cv2, matplotlib, scikit-learn, tensorflow, keras), Jupyter Notebook and Google Colab.


<img src="images/Digit_Prediction_CNN.png?raw=true"/>


##### iii) [Using Machine Learning to Predict Breast Cancer](https://github.com/rasiimwe/Code_Examples/blob/main/Predicting_Breast_Cancer_Using_Machine_Learning.ipynb)

This project utilized the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) for predictive analysis in breast cancer. Key tools largely used include: Jupyter Notebook, Python - numpy, pandas, matplotlib, plotly, seaborn and scikit-learn to run and compare Logistic Regression, Random Forest, KNeighbors, SVC, DecisionTree, GradientBoosting, AdaBoost, and XGB classification models.

[<img src="images/Breast_Cancer_Prediction.png?raw=true"/>](https://github.com/rasiimwe/Code_Examples/blob/main/Predicting_Breast_Cancer_Using_Machine_Learning.ipynb)

---

#### 6. [Understanding Tissue-Specific Temporal Changes after SIV Infection to Guide HIV Treatment](https://github.com/rasiimwe/Galaxy_Transcriptomics)

Human immunodeficiency virus (HIV) has continued to be a public health issue on a global scale, and over 35 million people have died due to the onset of acquired immunodeficiency syndrome (AIDS)-related diseases. Early diagnosis is crucial as it enables the control of infection via antiretroviral therapy in addition to reducing the risk of transmission. However, it is estimated that half of the patients with HIV worldwide are “late-presenters” because of the asymptomatic nature of the virus; a rationale for which more knowledge is needed to understand the early stages of HIV infection, and immune response. Simian immunodeficiency virus (SIV), a retrovirus infecting non-human primates, has symptoms and a viral life cycle similar to that of HIV. Phylogenetic analysis also shows that SIV and HIV are ancestrally related and are closely related in viral replication and propagation, making it a good model for understanding early development of infection. This project aimed at evaluating tissue-specific transcriptomic changes in the first ten days after SIV infection in rhesus monkeys. We leveraged various statistical methods such as fitting linear models, cluster analysis, PCA, gene set enrichment and pathway analysis, using various CRAN/Bioconductor R packages, and found that significant transcriptomic changes occur as early as day 1 post infection throughout host tissues. This knowledge is crucial for development of treatment as well as vaccines and more effective post-exposure prophylaxis drugs. Please visit this [GitHub repo](https://github.com/rasiimwe/Galaxy_Transcriptomics/blob/main/README.md) for more details on this project.

[<img src="images/HIV_project.png?raw=true"/>](https://github.com/rasiimwe/Galaxy_Transcriptomics/blob/main/Poster/Poster-FINAL.pdf)

---
#### 7. [Database Design, Development and Optimization](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

I have experience designing, developing, optimizing and managing large-scale databases, especially PostgreSQL and MySQL Database Management Systems (DBMSs). I have also worked with Oracle and Microsoft Access.

[<img src="images/Databases.png?raw=true"/>](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

---

#### 8. Shiny Apps and Dashboards

I have developed a number of Shiny-based tools, apps and/or dashboards, most of which are internal to the institutions I have worked with. Below are some of the few examples that are public. I have also had some experience conducting data analysis and visualizations using Dash (Python).

Not accessible publicly, however, this app's functionality can be viewed in my [thesis (pages 75 - 87)](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

[<img src="images/Shinyapp1.png?raw=true"/>](https://open.library.ubc.ca/media/stream/pdf/24/1.0377717/4)

Below is another tool [(CoADD)](https://rasiimwe.shinyapps.io/CoADD/) that is under development.  It compares DNA methylation patterns in immune cell types between cord and adult blood:

<img src="images/Shinyapp2.png?raw=true"/>

<!--Developed for training purposes, this is an elementary [dashboard](https://rasiimwe.shinyapps.io/NHS_A_and_E_Example_App/) that utilizes a subset of the NHS England A&E (Accident and Emergency) dataset, and shows the weekly and monthly attendances and emergency admissions in a specified period for all A&E types.

[<img src="images/shiny4A.png?raw=true"/>](https://rasiimwe.shinyapps.io/NHS_A_and_E_Example_App/) -->


---

### [Publications](https://orcid.org/0009-0002-1285-1614)
- **Asiimwe, R**. (2019). [**Database-driven whole genome profiling for stratifying Triple Negative Breast Cancers (TNBC)**](https://open.library.ubc.ca/collections/ubctheses/24/items/1.0377717) (T). University of British Columbia. Retrieved from https://open.library.ubc.ca/collections/ubctheses/24/items/1.0377717
- **Asiimwe, R.,** Lam, S., Leung, S., Wang, S., Wan, R., Tinker A., McAlpine, N, J., Woo, M., Huntsman, D., and Talhouk, A. [**From biobank and data silos into a data commons: convergence to support translational medicine**](https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-021-03147-z). *Journal of Translational Medicine* 19, 493 (2021). 
- Konwar, C., **Asiimwe, R.,** Inkster, M, A., Merrill, S., Negri, L, G., Aristizabal, J, Ma., Rider, C., MacIsaac, L, J., Carlsten, C., and Kobor, S, M. [**Risk-focused differences in molecular processes implicated in SARS-CoV-2 infection: Corollaries in DNA methylation and gene expression**](https://doi.org/10.1186/s13072-021-00428-1). *Epigenetics & Chromatin*. 14, 54 (2021).   
- Cheung, M.\*, **Asiimwe, R.\*,** Erman, E., Fucile, C., Liu, S., Sun, C., Hanumanthu, V., Pal, H., Wright, E., Ghajar-Rahimi, G., Epstein, D., Orandi, B., Kumar, V., Anderson, D., Greene, M., Bell, M., Yates, S., Moore, K., LaFontaine, J., Killian, J., Baker, G., Perry, J., Reed, R., Little, S., Rosenberg, A., George, J., Locke, J., and Porrett, P**. [**Spatiotemporal immune atlas of a clinical-grade, gene-edited pig-to-human kidney xenotransplant**](https://doi.org/10.1038/s41467-024-47454-7), *Nature Communications* 15, 3140 (2024). 
- **Asiimwe, R.,** and Alexader, D. **STAR+WASP reduces reference bias in allele-specific mapping of RNA-seq reads**. BioRxiv 576391 [Preprint]. January 23, 2024. Available from: DOI: https://doi.org/10.1101/2024.01.21.576391 (Submitted for review to Bioinformatics).
- **Asiimwe, R.,** Knott, B., Greene, E, M., Wright, E., Bell, M., Epstein, D., Yates, D, S., Cheung, D, M., Gonzalez, V, M., Fry, S., Boydston, E., Clevenger, S., Locke, E, J., George, F, J., Burney, R., Arora, N., Duncan, E, V., Richter, E, H., Gunn, D., Freud, G, A., Little, C, S., Porrett, M, P. **Inhibition of NFAT promotes loss of tissue resident uterine natural killer cells and attendant pregnancy complications in humans**. BioRxiv 583906 [Preprint]. March 12, 2024. Available from: DOI: https://doi.org/10.1101/2024.03.07.583906 (Submitted for review to Science Translational Medicine).
- Greene, E, M.\*, **Asiimwe, R.\*,** Wright, E., Bell, M., Epstein, D., Yates, D, S., Knott, B., Fry, S., Clevenger, S., Locke, E, J., Little, C, S., Richter, E, H., Freud, G, A., Porrett, M, P. **Sequential Transcriptional Programs of Tissue Residency Drive Human Uterine NK Cell Development**. BioRxiv 582684 [Preprint]. March 12, 2024. Available from: DOI: https://doi.org/10.1101/2024.02.29.582684 (In preparation for submission).
- Meijer, M., Konwar, C., **Asiimwe, R.,** Maclsaac, J., Lin, D., Garland, E., Ostlund, B., Kobor, S, M., Crowell, E, S., Conradt, E. **Prenatal opioid usage is associated with placental DNA methylation patterns in newborns independent of genetic predisposition**. (In preparation for submission). 
- Jones, J, M., Konwar, C., Dinh, L., **Asiimwe, R.,** Razzaghian, R, H., Olivia de Goede, MacIsaac, L, J., Morin, A, A., Kolsun, K., Gervin, K., Ng, R., Duijts, L., C van Zelm, M., Moll, A, H., Lyle, R., Robinson, P, W., Koestler, C, D., Felix, F, J., Lavoie, M, P., Mostafavi, S., and Kobor, S, M. **DNA methylation differences between cord and adult white blood cells reflect postnatal immune cell maturation**. Nature (Undergoing revisions).  
  * **Asiimwe, R.,** further developed [CoADD](https://rasiimwe.shinyapps.io/CoADD/), a tool that supplements this manuscript for utility by the broader research community in comparing DNA methylation patterns across six immune cell types, between cord blood and adult blood, at specific CpG sites.

<!-- - Asiimwe, R., Konwar, C., Merrill, S., MacIsaac, L, J., Katia, R., Crowell, E, S., Kobor, S, M., Conradt, E. Placental DNA methylation changes associated with opioid use during pregnancy. (In preparation for submission) -->

---
<p style="font-size:11px">Page powered by <a href="https://jekyllrb.com">jekyll</a></p>
<!-- Remove above link if you don't want to attibute -->
