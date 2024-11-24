## 🔬 Exploring Drug Repurposing Success Stories Through a Network-based Approach: Insights from a Case Study 💊

**Abstract:** 
Drug repositioning is a promising strategy to discover new therapeutic applications for existing drugs, significantly reducing the time and costs associated with traditional drug development. This study employs a network medicine approach to analyze successful cases of drug repositioning, focusing on the exploratory hypothesis that the efficacy of repositioning may be determined by functional similarity between between diseases for which the drug was originally designed and diseases for which the same drug is reused. Network medicine tools were employed to investigate the connections between disease-associated genes, proteins, and approved drugs. Biological networks, including protein-protein interactions and functional interactions networks, as well as gene- and drug-disease association data are analyzed to identify functional similarities and possible molecular connections between diseases and treatments. 
Using clustering techniques and topological analysis, the results reveal a suggestive overlap of involved genes and functional interactions, emphasizing the value of computational methods in accelerating drug repositioning efforts and improving understanding of drug repositioning dynamics for more efficient therapeutic interventions.


### In this repository you will find:

- 📊 **DATA**: There are all the data used in this work
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
- **CODE**: there are all the notebook used in this work    
    - PE_Project.ipynb
    - databases_1.ipynb
    - Clustering_all_db.ipynb     
