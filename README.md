# Serum microRNA Profiles Identify French Bulldogs Requiring BOAS Surgery

miRNA have been identified through the analysis of short read sequences using the pipeline nf-core/smrnaseq.
Results have been classified based on their existence in the mirbase database. 
Two differential expression analyses have been done with nf-core/differentialabundance. 
The first analysis focused on the detection of miRNA which were present in mirbase ([diffExpr_mirbase](https://github.com/sguizard/cutler_et_al/tree/master/diffExpr_mirbase/results_mirbase)) and the second analysis concentrated on putative novel miRNA ([diffExpr_mirbase_novel](https://github.com/sguizard/cutler_et_al/tree/master/diffExpr_mirbase_novel/results_mirbase_novel)).

A public repository has been created with the differential expression results: https://github.com/sguizard/cutler_et_al

Results can be accessed in several ways: HTML format, graphical user interface or via the shinyNGS app present in the shinyngs directory.

The putative novel miRNA identified corresponds to the miRNA `ugugccucggaggccucgugagc` in the `diffExpr_mirbase_novel` analysis.
