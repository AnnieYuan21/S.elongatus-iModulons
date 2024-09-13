# _S.elongatus_-iModulons

This repository contains the files and scripts needed to calculate the iModulon structures for the cyanobacteria _Synechococcus elongatus_

The paper can be found here: [Paper link](https://www.pnas.org/doi/10.1073/pnas.2410492121) <br>
The iModulons generated from this study can be found on the [iModulonDB page](https://imodulondb.org/dataset.html?organism=s_elongatus&dataset=elprecise300) <br>
The workflow is adapted from the [iModulonMiner](https://github.com/SBRG/iModulonMiner) workflow 

Please cite the papers above if you use these data and workflows

## **data**
- Figures: Contains all the figures in the publication
- Supplementary_data: Contains all the supplementary material in the publication
- all_strict: previous test on a different quality control threshold, not part of the final results
- external: external files such as annotations
- interim: interim files generated during the analysis
- processed_data: processed data in iModulon analysis

## **notebooks**: python notebooks used for analysis
- 1_create_the_gene_table: notebook for creating the gene annotation files
- 2_iModulon_characterization: notebook for generating iModulons and preliminary characterization
- 3_manual_iModulon_curation: detailed curation for th iModulons
- Figures: notebook for recreating all the figures presented in the paper

