# Fastq
## Process fastq files

### 1. Demultiplex multiplexed samples prepared by TruSeq library preparation.
  Usage:
  
  `perl demultiplex_Truseq.pl file.R1.fastq file.R2.fastq i1.fastq barcode.txt`
  
  a. R1 fastq file
  
  b. R2 fastq file
  
  c. barcode fastq file
  
  d. Barcode file (tab separated):
  
      Sample1 CTTGTA
      Sample2 ATCACG
