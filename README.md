# README #

FindCleavageSite.py takes as input sorted BAM files, generated by bwa.

### What is this repository for? ###

* This is a repository for programs associated with analysis of Comprehensive In vitro Reporting of CLeavage Effects by Sequencing (CIRCLE-seq).
* The main program is FindCircularCleavageSites.py
    
```
python /data/joung/bitbucket/invitro-guide-seq/FindCleavageSites.py --reads 3 \ 
--bam /data/joung/sequencing_fastq/150529_M01326_0203_000000000-AEENP/BAM/SQT01_S1.bam \
--ref /data/joung/genomes/Homo_sapiens_assembly19.fasta --targetsite GGGTGGGGGGAGTTTGCTCCNGG > VEGFA_1_ivgs.bed
```