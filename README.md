Esophagus Cancer Analysis
In this analysis, I explored Esophagus Cancer using RNA-Seq data retrieved from the GDC portal of TCGA (The Cancer Genome Atlas), a comprehensive resource provided by the National Cancer Institute.

I specifically selected untreated tumor samples to avoid treatment-related gene expression bias. The dataset includes both adenocarcinoma and squamous cell carcinoma tumor types, along with normal tissue samples for comparison.

🔧 Tools and Packages Used:
DESeq2 – for differential gene expression analysis

clusterProfiler – for gene set enrichment analysis (GSEA)

ggplot2, ComplexHeatmap, EnhancedVolcano – for data visualization

🧪 Objective:
To identify differentially expressed genes (DEGs) between tumor samples (Adenocarcinoma + Squamous) and normal esophageal tissues. This helps understand the molecular changes associated with tumor development.

