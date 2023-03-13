# GeNetOntology

GeNetOntology algorithm is proposed as a novel algorithm that improves classification performance by utilizing GO as external biological information while selecting the most relevant genes from gene expression datasets. The novelty and originality of our approach stems from its capability to explore the specific ontology groups to classify and find the most relevant groups for a disease. Our approach differs from conventional approaches where searching is done by considering individual genes.

# Data Preparation

Gene expression datasets for different types of human complex diseases is required to be downloaded from Gene Expression Omnibus (https://www.ncbi.nlm.nih.gov/geo/) 

The Gene Ontology  (http://www.geneontology.org) database provides the biological knowledge that will be used for the G grouping component. The GO data is required to be downloaded from the Molecular Signatures Database  (GSEA | MSigDB | Browse Human Gene Sets) (GSEA | MSigDB | Browse Human Gene Sets). Gene Ontology subsets, i.e., all GO gene sets, GO BP, GO CC, and GO MF, will be used separately for each run of workflow. 

  - The link for downloading KNIME: https://www.knime.com/downloads
  - For more information about the Knime platform, please visit https://www.knime.com/software-overview

# The Environment Settings of GeNetOntology
After installing KNIME Analytics platform, GeNetOntology workflow is downloaded and imported into the KNIME. The workflow contains R scripts therefore the following commands should be followed to prevent errors.
Before initiation of the workflow process in KNIME, R / RStudio is required to be run with following commands:
  - library(Rserve);
  - Rserve(args = "--vanilla") 
  -	library(tidyr)

Execution of R / RStudio and the workflow simultaneously enables the GeNetOntology analysis without retrieving any error. 

