# **Exploring functional protein covariation across single cells using nPOP**


<!--![GitHub release](https://img.shields.io/github/release/SlavovLab/DO-MS.svg)-->
![GitHub](https://img.shields.io/github/license/SlavovLab/DO-MS.svg)


* [nPOP Website](https://scp.slavovlab.net/nPOP) &nbsp; | &nbsp; [Download data](https://scp.slavovlab.net/Leduc_et_al_2022)
* [Preprint](https://doi.org/10.1101/2021.04.24.441211) <!--  &nbsp; | &nbsp; [*Nature Biotechnology* Article](https://doi.org/10.1038/s41587-022-01389-w) -->


&nbsp;

<img src="https://scp.slavovlab.net/Figs/nPOP_SamplePrep.png" width="70%">



### Requirements

This application has been tested on R >= 3.5.0, OSX 10.14 / Windows 7/8/10. R can be downloaded from the main [R Project page](https://www.r-project.org/) or downloaded with the [RStudio Application](https://www.rstudio.com/products/rstudio/download/).



------------

## Reproducing the data analysis


1. Download all the data reports from the "search" section of MassIVE [MSV000089159](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=ae918c7ce5a94a4abd2c6b54a3806c9e](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=158ee6b0cc0b4d8b9f1883b3917793fb).

2. Download the metadata file from the Supplemental file 4 of the paper or here at https://docs.google.com/spreadsheets/d/1JtkihjpyDzy3eamB2tLc6-YSjzENClQh/edit?usp=sharing&ouid=105737144695616543623&rtpof=true&sd=true.

3. Create a new R project, and copy the .Rmd, .R, .py, and .txt files from the Code section (https://github.com/SlavovLab/nPOP) to it. There are several scrips related to preproccessing and full data set PCA (nPOP_Analysis_main.Rmd), cell cycle analysis (CDC.Rmd), melanoma subpopulation analysis (SubPOP.Rmd, and plexDIA/pSCoPE integrated analysis (plexDIA.R).

4. Please update the file paths in the .Rmd scrips.

5. Run!



## About the project

<!--
DO-MS is a project...


The manuscript for this tool is published at the Journal of Proteome Research: [https://pubs.acs.org/doi/10.1021/acs.jproteome.9b00039](https://pubs.acs.org/doi/10.1021/acs.jproteome.9b00039)
-->
The manuscript is freely available on bioRxiv: [Leduc et al., 2022 (version 4)](https://doi.org/10.1101/2021.04.24.441211). <!-- The peer reviewed version is available at *Nature Biotechnology*: [Derks et al., 2022](https://doi.org/10.1038/s41587-022-01389-w) -->

For more information, contact [Slavov Laboratory](https://slavovlab.net).

### License

The nPOP code is distributed by an [MIT license](https://github.com/SlavovLab/DO-MS/blob/master/LICENSE).

### Contributing

Please feel free to contribute to this project by opening an issue or pull request.

<!--
### Data
All data used for the manuscript is available on [UCSD's MassIVE Repository](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=ed5a1ab37dc34985bbedbf3d9a945535)
-->

<!--
### Figures/Analysis
Scripts for the figures in the DART-ID manuscript are available in a separate GitHub repository, [https://github.com/SlavovLab/DART-ID_2018](https://github.com/SlavovLab/DART-ID_2018)
-->

-------------

## Help!

For any bugs, questions, or feature requests,
please use the [GitHub issue system](https://github.com/SlavovLab/nPOP/issues) to contact the developers.
