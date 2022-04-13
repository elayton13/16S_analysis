the first step of 16S_analysis with raw fastq files is to run QIIME or similar
input files should already be demultiplexed
should also run a QC using fastQC or similar to verify sequencing quality before running qiime
this also ensures there are no contaminants / adaptors or barcodes remainig
the metadata file was created as per qiime guidelines using goolge sheets plug-in keemei
after running qiime I used the following packages in this order to further interrogate the data:

phyloseq
ggplot
picrust2
ALDEX2
phylosmith


