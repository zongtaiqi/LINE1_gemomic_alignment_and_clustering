# LINE1-insertion-mapping
Usage: <read1.fq> <read2.fq> <barcode> <mapper option> <TF_to_scan>; 
<Mapper option>: options can be combined without spaces in between (i.e. 12, 123 or 1234); Mapping database is hg19. 
 1) bowtie2 for read2 single end alingment    
 2) bowtie2 for paired end alignment
 3) novoalign for read2 single end alignment
 4) novoalign for paired end alignment
<TF_to_scan>: underscore delimited transcription factors to scan; 

Output name: prefix is from the first "-"(hyphen) deliminated input name;
