  [1] "Row.names"                              	transcript ID
  [2] "logFC"                                  	limma test output
  [3] "AveExpr"                                	limma test output, the average FPKM, filtered transcript will show NA values in this colunm
  [4] "t"                                      	limma test output
  [5] "P.Value"                                	limma test output
  [6] "adj.P.Val"                              	limma test output
  [7] "B"                                      	limma test output
  [8] "decision"                               	results used in the manuscript
  [9] "gene_id"                                	same as  "Row.names"      
 [10] "gene"                                   	annotation by Gencode v25 if at leaset 1bp overlap
 [21] "seqnames"                               	hg38 locus
 [22] "start"                                  	hg38 locus
 [23] "end"                                    	hg38 locus
 [24] "strand"                                 	hg38 locus
 [25] "coord"                                  	hg38 locus
 [26] "width"                                  	transcript width
[31] "overlap_coding"                          	"yes" is at least 1bp overlap with protein-coding transcripts in Gencode v25 on the same strand; eitherwise "antiCoding" or "no"
[32] "ChromHMM_enhancer"                       	"strongEnhancer" or "weakEnhancer" means the transcript pverlaps at least 1bp with ChromHMM Strong/weak enahncer, respectively, otehrwise "no"
[71] "K562_H3K9me3_ENCFF371GMJ.bed"            	"yes" means transcript overlapped with the ChIP signal of interest
[131] "POLR2A"                                  "yes" means transcript overlapped with the ChIP signal of interest	
[135] "GROseq"                                  "yes" means transcript overlapped with the ChIP signal of interest	
[138] "class1_TE"                               "yes" means transcript overlapped with the ChIP signal of interest	
[139] "class2_TE"                               "yes" means transcript overlapped with the ChIP signal of interest	
[140] "Anno"                                    "yes" is voerlap with one or more transcripts in Gencode v25
[146] "TSS_coord"                               a 2k window around the TSS 
[185] "TSS_K562_H3K9me3_ENCFF371GMJ.bed"        yes means a 2k window around the TSS overlaps with the signal of H3K9me3
[243] "antiCoding_coord"                        the coding gene's coordinates when it overlaps with an asRNA
[244] "antiCoding_TSS_coord"                    a 2k window around the TSS of the coding gene that overlaps with a asRNA
[245] "antiCoding_pos"                          5=promoter asRNA; 3=3'UTR asRNA
[246] "FANTOM_blood"                   		yes=at least 1 bp overlap with FATOM-predicted enahncer prediction in blood
