# TRGN-Capstone-2021Fall

Zeyuan Dong zeyuando@usc.edu

TRGN -Capstone Project

November 25, 2021


1.   Title:
Differential Gene Expression of African American with Prostate Cancer
2.   Mentor:
Enrique I. Velazquez-Villarreal  eivelazq@usc.edu
3.  
(1) Traditional thesis, turned in as a PDF consisting of no-less than six pages written with 0.5" margins, Ariel 11 or Times New Roman 12, with sections of Introduction, Methods, results, and discussion.

(2) Prostate cancer is one of the leading causes of cancer death in American men. Many studies now suggest that race plays a crucial role in prostate cancer. With the development of next-generation sequencing technology, RNA-Seq has become an important tool for transcriptome analysis and quantification. Rna-seq primarily helps researchers identify differences in gene expression. The RNA-Seq approach could help researchers gain insight into the development of prostate cancer and identify potential therapeutic targets. Data analysis was performed by Bioinductor in this study.

(3) Data were obtained through HPC (CARE2 Bioinformatics, Statistical & Methodological Shared Resources BSMSR CORE). All patients are African Americans. Biomarkers can guide clinical diagnosis and treatment decisions, so this study focused on investigating differences in gene expression before and after treatment in African American prostate cancer patients to look for potential biomarkers. -In the exploration results and visualization, the visualization results help me understand the sample information and structure more clearly. In many studies, heat maps are often an intuitive way to explore enumeration matrices. In DESeq2, two transformation methods are proposed. One is variance-stable transformation (VST) and the other is regular logarithmic transformation (Rlog). Since VST has a shorter running time than Rlog, I chose VST (FPKM) for all the colors in the heat map.

(4) Different contrasts of sample type, Gleason number and treatment conditions were conducted to explore the expression patterns, visualized by heatmap. Contrasting of pre-treatment and post-treatment between 34&36 and 35&36 controlling over sample types was finally chosen in this study, and top 200 gene list ranked by adjusted p-value were generated respectively. The shared genes of two lists were subsequently displayed by heatmap and analyzed by Ingenuity Pathway Analysis (IPA) and STRING（protein-protein interaction prediction）to obtain the candidate genes. After literature research, genes of interest, potential biomarkers in this case, were eventually selected and rationalized.

(5)  I will show and explain my work and result for each step in R. I will analyze and discuss candidate genes in the discussion section of the paper.



