# Kraken databases used during the Captureseq project


* covid2 only:
* Twist panviral:
* Illumina panel:
* Viruses:
* bacteria:
* human:




* The file accession_panel_illumina.txt contains 83 viruses to be used in the Illumina panel v1. **This file excludes the human control**
* In v2, human control were added. We have 94 genes. Gene names are stored in illumina_resp_human_control.txt**** 
* The file accession_panel_twist.txt contains 1160 viruses to be used in the twist panel.


**kraken DB notes:**

there were unmapped accession numbers. We had to add those seqid to taxon mapping in the seqid2tax file of the librarry before building it. 

```
   NC_027201 taxon:11587
   NC_027203 taxon:11587
   NC_028101 replaced by NC_012042 taxon is 573977
   NC_006947 obsolete according to NCBI taxon is 64287
   NC_027202 taxon: 11587
   NC_004355 taxon: 172148
   NC_001347 taxon: 10359
   NC_002617 139270
   NC_004148 162145
```
