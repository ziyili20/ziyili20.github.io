---
layout: page
title: Software
---


Our group developed and maintains freely-available, open-source software packages in R/Bioconductor/CRAN/GitHub to analyze biomedical data. 

<!--
<p float="left">
  <img src="./assets/pics/DSS_hex.png" width="125" height="144" />
  <img src="./assets/pics/NeuCA_hex.png" width="125" height="144" />
 	<img src="./assets/pics/ISLET_hex.png" width="125" height="144" />
<!--   		<img src="/img3.png" width="100" /> 	-->
</p>

---------------


- <a style="color: blue;" class="btn btn-primary" href="http://bioconductor.org/packages/release/bioc/html/TOAST.html">TOAST</a> 
  <a style="color: black;" class="btn" href="http://bioconductor.org/packages/stats/bioc/TOAST/">Usage Stats</a> 
  <img src="https://bioconductor.org/shields/years-in-bioc/TOAST.svg"><br/>
  (**TO**ols for the **A**nalysis of heterogeneou**S** **T**issues): Devoted to analyzing high-throughput data (e.g. gene expression microarray, DNA methylation microarray, RNA-seq) from complex tissues. Current functionalities include 1. detect cell-type specific or cross-cell type differential signals 2. tree-based differential analysis 3. improve variable selection in reference-free deconvolution 4. partial reference-free deconvolution with prior knowledge.. Available on [Bioconductor](http://bioconductor.org/packages/release/bioc/html/TOAST.html).

- <a  style="color: blue;" class="btn btn-primary" href="https://bioconductor.org/packages/NeuCA/">NeuCA</a>
  <a style="color: black;" class="btn" href="http://bioconductor.org/packages/stats/bioc/NeuCA/">Usage Stats</a> 
  <img src="https://bioconductor.org/shields/years-in-bioc/NeuCA.svg"><br/>
  (**Neu**ral-network based **C**ell type **A**nnotation): R/Bioconductor package for single-cell RNA-seq data cell type annotation, using neural-network approaches. NeuCA is flexible and adjust the classification method it will adopt, depending on cell types' correlation level. Available on [Bioconductor](https://bioconductor.org/packages/NeuCA/) and [Shiny app](https://statbioinfo.shinyapps.io/NeuCA/). 
  
- <a  style="color: blue;" class="btn btn-primary" href="https://cran.r-project.org/web/packages/CondiS/index.html">CondiS</a><br/>
  (**Con**ditional survival distribution**S** for missing survival data imputation): R/Bioconductor package for imputing the survival times for censored observations based on their conditional survival distributions derived from the Kaplan-Meier estimator. 'CondiS' can replace the censored observations with the best approximations from the statistical model, allowing for direct application of machine learning-based methods. When covariates are available, 'CondiS' is extended by incorporating the covariate information through machine learning-based regression modeling ('CondiS_X'), which can further improve the imputed survival time. Available on [CRAN](https://cran.r-project.org/web/packages/CondiS/index.html) and [Shiny app](https://biostatistics.mdanderson.org/shinyapps/CondiS/). 
  
- <a  style="color: blue;" class="btn btn-primary" href="https://bioconductor.org/packages/devel/bioc/html/EasyCellType.html">EasyCellType</a>
  <a style="color: black;" class="btn" href="http://bioconductor.org/packages/stats/bioc/EasyCellType/">Usage Stats</a> 
  <img src="https://bioconductor.org/shields/years-in-bioc/EasyCellType.svg"><br/>
R/Bioconductor package that can automatically examine the input marker lists obtained from existing software such as Seurat over the cell markerdatabases. Two quantification approaches to annotate cell types are provided: Gene set enrichment analysis (GSEA) and a modified versio of Fisher's exact test. The function presents annotation recommendations in graphical outcomes: bar plots for each cluster showing candidate cell types, as well as a dot plot summarizing the top 5 significant annotations for each cluster. Available on [Bioconductor](https://bioconductor.org/packages/devel/bioc/html/EasyCellType.html) and [Shiny app](https://biostatistics.mdanderson.org/shinyapps/EasyCellType/). 
				            
- <a  style="color: blue;" class="btn btn-primary" href="https://cran.r-project.org/web/packages/caROC/index.html">caROC</a><br/> 
(**c**ovariate **a**djusted **R**eceiver **O**perating **C**haracteristics for continuous biomarkers) R/CRAN package for computing covariate-adjusted specificity at controlled sensitivity level, or covariate-adjusted sensitivity at controlled specificity level, or covariate-adjust receiver operating characteristic curve, or covariate-adjusted thresholds at controlled sensitivity/specificity level. All statistics could also be computed for specific sub-populations given their covariate values. Available on [CRAN](https://cran.r-project.org/web/packages/caROC/index.html).
		    
- <a  style="color: blue;" class="btn btn-primary" href="https://github.com/ziyili20/CAMLU">CAMLU</a><br/> (**C**ell **A**nnotation using **M**achine **L**earning-based method for the presence of **U**nknown cells) An R package that provides an autoencoder based method for annotating cell types from scRNA-seq data. The function can identify unknown cells with the input training data. It also can annotate the full lists of cell types with consideration of unknown cell types. This vignette introduces the CAMLU function and the things it can do for you. Available on [GitHub](https://github.com/ziyili20/CAMLU).

- <a  style="color: blue;" class="btn btn-primary" href="https://github.com/ziyili20/TransCox">TransCox</a><br/> (**Trans**fer learning with the **Cox** proportional hazards model) An R package that perform transfer learning in Cox model. It can effectively borrow risk estimation from a larger cohort to improve inference and analysis of the current cohort. Available on [GitHub](https://github.com/ziyili20/TransCox).

- <a  style="color: blue;" class="btn btn-primary" href="https://github.com/ziyili20/partCNV">PartCNV</a> <br/> An R package to improve the detection of locally aneuploid cells by incorporating cytogenetic information. It implements a statistical framework for rapid and accurate detection of aneuploid cells with local copy number deletion or amplification. Our method uses an EM algorithm with mixtures of Poisson distributions while incorporating cytogenetics information to guide the classification (partCNV). When applicable, we further improve the accuracy by integrating a Hidden Markov Model for feature selection (partCNVH). Available on [GitHub](https://github.com/ziyili20/partCNV).

- <a  style="color: blue;" class="btn btn-primary" href="https://github.com/ziyili20/DistributedLearningPredictor">DistributedLearningPredictor</a><br/> 
A python package to perform distributed learning prediction models while protecting patients' privacy. Available on [GitHub](https://github.com/ziyili20/DistributedLearningPredictor).

- <a  style="color: blue;" class="btn btn-primary" href="https://github.com/ziyili20/GBC">GBC</a><br/> 
The R package for generalized biclustering. Available on [GitHub](https://github.com/ziyili20/GBC).