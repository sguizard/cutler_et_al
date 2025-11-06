# Serum microRNA Profiles Identify French Bulldogs Requiring BOAS Surgery

miRNAs from dogs have been identified throught the analysis of short reads sequences by the pipeline nf-core/smrnaseq. 
Results have been classified based their existence in the mirbase database. 
Two differential expression analysis has been done with nf-core/differentialabundance. 
The first one was on miRNA detected and present in mirbase (diffExpr_mirbase) and a second one wirh the putative new ones (diffExpr_mirbase_novel). 

You can find the results in HTML format in the `report` directory, or if you prefere Grephical User Interface, you can load the shinyNGS app present in the `shinyngs` directory.
