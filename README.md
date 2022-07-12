# running_process_in_parallel

###Suppose all fastq of a folder is required to zip in parallel then run following commmand in linux terminal
parallel bgzip -l 9 {} ::: *.fastq &
