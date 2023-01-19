## Danio rerio Gene Sets and Pathways

This is the repository for pathways for Danio rerio (Zebrafish) generated from original sources. 

Sources currently used for .gmt files. Versions from each resource are noted on the gmt file name.

### Reactome
Downloaded from https://reactome.org/download/current/NCBI2ReactomeReactions.txt
(note this links to the current version)

### Gene Ontology
Source: ZFIN
Translated gaf file into a gmt on GO IDs, then transformed the GO ID into the descriptive name using Bioconductor's org.Dr.eg.db_3.16.0. 
Separated into GO BP, GO CC and GO MF trees by annotations in the gaf.

Link source: https://zfin.org/downloads

Link sourced as https://current.geneontology.org/annotations/zfin.gaf.gz

Also findable as http://current.geneontology.org/products/pages/downloads.html

Method: Parsed out the GO ZFIN_GO file w.python based on danio rerio species.

#Decisions for which tree based on the relationship in the gaf.

#Relationship example_goterm  Assigned_home_tree

#involved_in  GO:0007224  bp

#acts_upstream_of_or_within	GO:0007399	bp

#acts_upstream_of	GO:0006556	bp

#acts_upstream_of_negative_effect	GO:0006412	bp

#acts_upstream_of_or_within_positive_effect	GO:0030318	bp

#acts_upstream_of_positive_effect	GO:0044332	bp

#acts_upstream_of_or_within_negative_effect	GO:0030509	bp

#part_of	GO:0031105	cc

#located_in	GO:0016020	cc

#colocalizes_with	GO:0097649	cc

#is_active_in	GO:0030027	cc

#enables	GO:0019215	mf

#contributes_to	GO:0008176	mf



