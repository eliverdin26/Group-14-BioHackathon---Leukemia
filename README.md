# Group-14-BioHackathon---Leukemia

## Leukemia Overview
Leukemia is a cancer of the blood and bone marrow, characterized by the rapid growth of abnormal blood cells. Leukemia is the most common cancer in children younger than 15, although it occurs most frequently in adults older than 55. 

#### Symptoms
From a clinical perspective some common symptoms of leukemia include: fatigue and weakness, frequent or severe infections, easy bruising or bleeding, fever or chills, night sweats, unexplained weight loss, swollen lymph nodes, bone pain or tenderness, and petechiae (tiny red spots under skin).

#### Diagnostic Criteria
The diagnosis of leukemia typically involves: physical examination, blood tests (CBC and peripheral blood smear), bone marrow biopsies, cytogenetic analysis, immunophenotyping, and various molecular testing for genetic abnormalities. 

#### Prognostic Criteria
The prognosis of leukemia varies depending on the type of leukemia. The key prognostic factors that physicians consider before predicting a patients clincal outcome include: age of patient, white blood cell count at diagnosis, cytogenic abnormalities, response to initial treatment, presence of minimal residual disease after treatment, and various comorbidities. 

#### Frontline Treatments
Treatment options for leukeumia include: Chemotherapy, Targeted Therapy using drugs focused on specific abnormalities within cancer cells (tyrosine kinase inhibitors, FLT3 inhibitors and IDH inhibitors, BCL-2 inhibitors, Ziftomenib or Revumenib are common examples), Immunotherapy, Stem Cell Transplantation, Radiation Therapy, and various clinical trials. 

#### Criteria for Successful Treatment
Success of treatment can be measured by the achievement of complete remission, minimal residual disease negativity, overall survival and disease-free survival, and overall quality of life improvements. 

#### Options if Frontline Therapy Fails
If the initial treatment is unsuccessful, options include: beginning alternative chemotheraphy regiments, clincal trials of new drugs or unique combinations, stem cell transplantation (if not done initially), CAR T-cell therapy, and Palliatve care for sympom management.

#### Organs Involved in Leukemia Expression
Leukemia primarily affects the blood-forming tissues and organs:
1. Bone marrow: Primary site of leukemia development
2. Blood: Circulating leukemic cells affect the entire body
3. Lymph Nodes: Often enlarged due to accumulation of leukemic cells
4. Spleen: Also may become enlarged (splenomegaly)
5. Liver: Can be affected, leading to an enlarged liver (hepatomegaly)
6. Central Nervous System: In some cases, leukemia can spread to the brain and spinal cord.

## Genes Underlying Leukemia
Leukemia is associated with the following abnormally expressed genes: 
1. FLT3
2. NPM1
3. DNMT3A
4. IDH1
5. IDH2
6. TET2
7. RUNX1
8. CEBPA
9. WT1
10. KIT
11. MLL

Promethus was used to aquire this list. Below are the prompts that were used:
* From a molecular perspective, what genes are associated with Leukemia?
* When are these genes normally expressed in development and in what tissue are they expressed?
* When are these genes abnormally expressed in Leukemia and in what tissue are they misexpressed?
* What is the molecular function of the genes that are abnormally expressed that lead to Leukemia?

## Protein-Protein Interaction (PPI) Network

* What is the difference between a protein:protein interaction (PPI) network and a gene co-expression network?

There are several differences in PPI and gene co-expression networks including the data source, the interpretation or results, and the application in bioinformatics. PPI networks use experimental data from protein-protein interaction pathways to understand protein relationships to cellular functions. The assay methods to collect experimental data focus at the protein level to understand protein interaction and diseases. Gene co-expression networks use data from gene expression assays to understand transcriptional regulation. The process specifically identifies genes that are expressed at similar levels. The interpretation of results from gene co-expression shows genes that are involved in similar biological processes. 

* How do I find interacting proteins with a seed protein?  Use the EBI Intact database as an example.  Also note how one can access Intact via Cytoscape.

To find the interacting proteins with a seed gene, the EBI Intact database should be used. This database is a publicly available database for protein interactions. The seed gene or UniProt accession number can be used to access all known interacting proteins. The different types of interactions such as binding, enzymatic regulation, or proximity will be displayed. The EBI Intact database is also linked to Cytoscape which can find interacting proteins with seed genes and directly import the data. Cytoscape and then be used for enrichment analysis and to build data visualizations. 
This is an example of the PPI network for underlying genes related to leukemia. 
 
* How can I visualize and analyze the PPI network?  For example, how can I determine if the network is scale-free? Use Cytoscape as an example tool. 

Cytoscape has a built in analyze software, using the network analysis functions under the tools menu will produce degree distribution, degree of each node, and the average degree. To determine if a network is scale free the degree of distribution must be plotted on a log-log scale. Scale-free networks will display a straight line showing a linear relationship. If the plot is not linear the network may not be scale free and could show a different distribution such as Poisson. 

* How can I find pathway and disease enrichment for these genes?  Use Toppfun as an example.

To find pathway and disease enrichment for seed genes Toppfun can be used to analyze based on 14 different annotations categories. These include GO terms, pathways, protein–protein interactions, protein functional domains, and transcription factor-binding sites for example. Toppfun allow the choice of analysis type such as pathway or disease. Pathway enrich identifies overrepresented pathways compared to a background set of genes. Disease enrichment uses databases such as OMIM to identify diseases associated with seed genes. Toppfun results interpretation provide information such as disease name, number of genes associated, and statistical significance score of pathway and disease enrichment results. This is an example of result visualization for Toppfun. 

## Tissue Specific eQTL's
1. Significant eQTLs have been identified in whole blood for FLT3 1 (Fms Related Receptor Tyrosine Kinase 3): Mutations in the FLT3 occur frequently with mutations in some other genes, especially the DNMT3A gene which is also another gene that is abnormally expressed that is associated with Leukemia:
      -SNP: rs2504232
      -p-value: 0.0000028
      -Effect Size: -0.11
2. NPM1 is expressed in whole blood but no significant eQTL's in whole blood was found.
3. DNMT3A has significant eQTLs in whole blood 1. Mutations in DNMT3A are often found in conjunction with FLT3 mutations in acute myeloid leukemia (AML). Ex eQTL:
      -SNP: rs4563176
      -p-value: 0.0000054
      -Effect Size: -0.27
4. Both IDH1 and IDH2 have eQTLs identified in whole blood 1. Mutations in these genes are known to affect hematopoiesis and play a role in leukemogenesis.
5. TET2 has significant eQTLs in whole blood 1. Mutations in TET2, along with DNMT3A and IDH1/2, are known to affect hematopoiesis and contribute to the development of pre-leukemic stem cells.

## Hypothesis
