# Fork of absCNseq

This is Daniel Klevebrings fork of absCNseq. It has the following notable differences from the original source code:

- Minor changes to `plot.absCN()` to facilitate plotting multiple chrs using `layout()`, and setting `ylim`. 
- Mutation input is in [MAF format](https://wiki.nci.nih.gov/display/TCGA/Mutation+Annotation+Format+(MAF)+Specification). The columns `Chromosome`, `Start_Position`, `t_alt_count` and `t_ref_count` are required. Columns `tumor_var_freq` and `multiplicity` will be appended by absCNseq. 

#Acknowledgements

Big thanks to the original authors Lei Bao, Minya Pu and Karen Messer for their work on the algorithm, and making the source code publicaly available. 

- [source code](https://github.com/seqanswers/absCNseq) 
- [publication](http://bioinformatics.oxfordjournals.org/content/30/8/1056.long)