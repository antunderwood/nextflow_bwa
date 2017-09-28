# Simple Nextflow bwa pipeline
## Running using Docker
nextflow run aunderwo/nextflow_bwa -with-docker  --reference_file /path/to/ref.fasta --paired_read_dir /path/to/paired_fastqs/dir --pattern_match "*_{1,2}.fastq.gz" --output_dir /path/to/oytput/dir -with-trace -with-timeline -resume
 
