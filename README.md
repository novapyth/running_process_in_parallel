# running a process in parallel

## Suppose all fastq/vcf of a folder is required to zip in parallel then run following command in linux terminal

parallel bgzip -l 9 {} ::: *.fastq 

parallel bgzip -l 9 {} ::: *.vcf
