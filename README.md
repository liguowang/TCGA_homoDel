# TCGA_homoDel
Deletion and nonsynnonymous mutation data of Interferon (IFN), defensin (DEF), CDKN2A and PTEN in 17 TCGA cancer types

The 17 TCGA cancer types 
=========================
* BLCA
* BRCA
* ESCA
* GBM
* HNSC
* LGG
* LIHC
* MESO
* OV
* PAAD
* PRAD
* SARC
* SKCM
* STAD
* UCS
* Colorectal (COAD + READ)
* Lung (LUAD + LUSC)

Description of each data file 
==============================

* Column 1: TCGA patient ID

* Column 2: Homo deletion status of *interferons* and *defensins*
 * I: Homozygous deletion of interferons
 * D: Homozygous deletion of defensins
 * C: Co-occurring homozygous deletion of Interferon and defensins
 * N: Other

* Column 3-4:Homo deletion status of *CDKN2A* and *PTEN*
 * -2: Deep deletion (homozygous deletion)
 * -1: Shallow deletion (loss)
 * 0: No change (copy neutral)
 * 1: Copy gain
 * 2: Amplification

* Column 5-8: Mutation status of *CDKN2A*, *PTEN*, *defensin* and *interferon*
 * 0: no mutation
 * 1: nonsynonymous mutation
