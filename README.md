# Data-Visualization-for-RNA-seq-of-Xenopus-Brain-Development

*Note: For the .html file, download it and open on your browser. For previews, click on this link*: http://rpubs.com/nguyenminhvinhky/1038721


### Background information
*Xenopus*, commonly known as the clawed frog, is a genus of highly aquatic frogs native to sub-Saharan Africa that is genetically surprisingly similar to humans. Among the 20 species that is currently described within the *Xenopus* genus, the two best-known species of this genus are *Xenopus laevis* and *Xenopus tropicalis* - the former of which is used in this project - and has long been used to study developmental and cell biology, and is an increasingly important model for human birth defects and disease, genomics, proteomics and toxicology.


<p align = "center">
  <img src = "https://github.com/nguyenminhvinhky/-Data-Visualization-for-RNA-seq-of-Xenopus-Brain-Development/assets/110079224/548d35ed-ed29-4bee-a617-197de6ed2f54" height = "300" width = "450">
 </p>


### Project goal
We're looking at the gene expression of the *Xenopus laevis*'s midbrain region at different developmental stages. Particularly, we wanted to perform data visualization techniques to "represent" those different developmental stages and identify the differentially expressed genes between the middle and late developmental stages 


### Data Visualization techniques
Data visualization allow us to comprehend the data as well as extract insightful trend, knowledge, and pattern from it, especially from 250,000+ datapoints. For this project, we'll use the following data visualizations techniques:

1. *Boxplot*: To represent the distribution of
    * Raw counts before and after TPM, log-transformed, which illustrate the need for gene count normalization
    * Principal Component (PC) scores (PC1 and PC2) in relation to the midbrain developmental stages.
2. *PCA*: Form clusters/groups of the three midbrain developmental stages: Early, Middle, and Late
3. *Volcano Plot*: Identify statistically significant, differentially expressed genes that are up- or down-regulated between the middle and late midbrain developmental stages
4. *Heatmap*: Display the expression levels of the top 10 most statistically significant genes and the patterns between the middle and late developmental stages
 

### Results
Through the data visualizations, we are able to

1. Obtain a clear separation between the three developmental stages: Early, Middle, and Late using PCA 
2. Discover that the top 10 statistcally significant genes are down-regulated in the late developmental stages
