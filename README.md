# TCGA_homoDel
Deletion and nonsynnonymous mutation data of Interferon (IFN), defensin (DEF), CDKN2A and PTEN in 17 TCGA cancer types

The 17 TCGA cancer types 
=========================
1. BLCA : Bladder Urothelial Carcinoma
2. BRCA : Breast invasive carcinoma
3. ESCA : Esophageal carcinoma
4. GBM : Glioblastoma multiforme
5. HNSC : Head and Neck squamous cell carcinoma
6. LGG : Brain Lower Grade Glioma
7. LIHC : Liver hepatocellular carcinoma
8. MESO : Mesothelioma
9. OV : Ovarian serous cystadenocarcinoma
10. PAAD : Pancreatic adenocarcinoma
11. PRAD : Prostate adenocarcinoma
12. SARC : Sarcoma
13. SKCM : Skin Cutaneous Melanoma
14. STAD : Stomach adenocarcinoma
15. UCS : Uterine Carcinosarcoma
16. Colorectal (COAD & READ): Colon adenocarcinoma & Rectum adenocarcinoma
17. Lung (LUAD & LUSC): Lung adenocarcinoma & Lung squamous cell carcinoma

Description of each data file 
==============================

* Column 1: TCGA patient ID

* Column 2: Homo deletion status of *interferons* and *defensins*
  * I: Homozygous deletion of interferons
  * D: Homozygous deletion of defensins
  * C: Co-occurring homozygous deletion of Interferon and defensins
  * N: Other

* Column 3-4: Homo deletion status of *CDKN2A* and *PTEN*
  * -2: Deep deletion (homozygous deletion)
  * -1: Shallow deletion (loss)
  * 0: No change (copy neutral)
  * 1: Copy gain
  * 2: Amplification

* Column 5-8: Mutation status of *CDKN2A*, *PTEN*, *defensin* and *interferon*
  * 0: no mutation
  * 1: nonsynonymous mutation
