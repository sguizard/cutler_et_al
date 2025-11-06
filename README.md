# Serum microRNA Profiles Identify French Bulldogs Requiring BOAS Surgery

miRNAs from dogs have been identified throught the analysis of short reads sequences by the pipeline nf-core/smrnaseq. 
Results have been classified based their existence in the mirbase database. 
Two differential expression analysis has been done with nf-core/differentialabundance. 
The first one was on miRNA detected and present in mirbase [diffExpr_mirbase](https://github.com/sguizard/cutler_et_al/tree/master/diffExpr_mirbase/results_mirbase) and a second one wirh the putative new ones [diffExpr_mirbase_novel](https://github.com/sguizard/cutler_et_al/tree/master/diffExpr_mirbase_novel/results_mirbase_novel). 

You can find the results in HTML format in the `report` directory, or if you prefere Grephical User Interface, you can load the shinyNGS app present in the `shinyngs` directory.

The putative novel miRNA identified `CTAAA72` in the paper, correspond the miRNA `ugugccucggaggccucgugagc` in the `diffExpr_mirbase_novel` analysis.

