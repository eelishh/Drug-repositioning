## 🔬 Exploring Drug Repurposing Success Stories Through a Network-based Approach: Insights from a Case Study 💊

**Abstract:** 
Drug repositioning is a promising strategy to discover new therapeutic applications for existing drugs, significantly reducing the time and costs associated with traditional drug development. This study employs a network medicine approach to analyze successful cases of drug repositioning, focusing on the exploratory hypothesis that the efficacy of repositioning may be determined by functional similarity between between diseases for which the drug was originally designed and diseases for which the same drug is reused. Network medicine tools were employed to investigate the connections between disease-associated genes, proteins, and approved drugs. Biological networks, including protein-protein interactions and functional interactions networks, as well as gene- and drug-disease association data are analyzed to identify functional similarities and possible molecular connections between diseases and treatments. 
Using clustering techniques and topological analysis, the results reveal a suggestive overlap of involved genes and functional interactions, emphasizing the value of computational methods in accelerating drug repositioning efforts and improving understanding of drug repositioning dynamics for more efficient therapeutic interventions.


### In this repository you will find:

- 📊**DATA**: This repository includes all the data used: https://drive.google.com/drive/folders/1e0icTHDygktdkV4UO5Zgw9l1PmcIW6CE?usp=drive_link
    - DRUG_GENE_ASSOCIATION (DGA)
      - Source: DGIdb
      - Description: Provides drug-gene interaction data, linking drugs to their effects on gene expression and interactions.
    - GENE-DISEASE ASSOCIATION (GDA)
      - Source: DisGeNET
      - Description: Integrates gene-disease association information from scientific literature and curated databases.
    - FUNCTIONAL INTERACTIONS (FI)
      - Source: Reactome
      - Description: Represents interactions between molecules within biological pathways, such as metabolism, gene regulation, and signal transmission.
    - PROTEIN-PROTEIN INTERACTIONS (PPI)
      - Source: BioGRID
      - Description: Provides a curated repository of gene and protein interactions across major species. Focused on Homo sapiens for this work.
      
- 💻**CODE**: This repository includes all the notebooks used:
    - PE_Project.ipynb:  Includes the analysis of gene set overlaps along with functional and topological analysis
    - Clustering_all_db.ipynb: Focuses on the clustering analysis
 
- 🗃️**RESULTS**: This repository includes the results of the three levels of investigation conducted in this work:
    - Overlap Between Gene Sets
        - Contains analyses on the overlaps between gene sets, including original disease genes (OD), repurposed disease genes (RD), and drug target genes (T).
          Results include the Overlap Index (OI) calculations and comparisons to assess the similarity between these gene sets.
    - Functional Similarity
        - Includes results of functional enrichment analysis using GSEApy, covering pathways (Reactome, KEGG) and gene ontology categories (Biological Process,               Cellular Component, Molecular Function).
          Results highlight enrichment matrices, clustering analysis, and Principal Component Analysis (PCA) for disease pairs.
    - Topological Proximity
        - Contains results of topological analysis, measuring network proximity between disease gene modules using PPI and FI networks.
          Includes calculations of topological separation (sAB) and clustering based on proximity metrics, along with visualization of network-based similarities.
