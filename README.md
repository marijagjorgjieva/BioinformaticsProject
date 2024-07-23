# Step 1: Data Generation and Preprocessing
## 1.1 Data Generation
### Obtain Gene Expression Data:

- Source gene expression data from TCGA (The Cancer Genome Atlas) and PCAWG (Pan-Cancer Analysis of Whole Genomes).
- Normalize the data and screen out samples that have undergone prior therapy to ensure consistency and reliability.

### Generate TIDE Results:

- Use the TIDE (Tumor Immune Dysfunction and Exclusion) method to generate prediction scores.
- TIDE provides CTL (Cytotoxic T Lymphocyte) level, Dysfunction score, and Exclusion score for each sample.

## 1.2 Data Preprocessing
### Align TIDE Results with Gene Expression Data:

- Align the TIDE results with miRNA expression data based on sample IDs to ensure each sample has corresponding miRNA expression and TIDE scores.
