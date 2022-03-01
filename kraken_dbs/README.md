# Kraken databases used during the Capture-seq project


## databases
* [covid2](covid2): custom database with wuhan genome only
* [Twist panviral](twist_panviral):  custom database with 1160 viruses from the Twist panviral panel
* [Illumina panel viruses](twist_panviral) only: custom database with 83 viruses from the Illumina panel
* [Illumina panel human control](illumina_human_control) only:  custom database wit only the human control

We also used viral, bacteria and human databases, not provided here, from the standard dabases built with kraken2 command line.

## Other files:

* The file **accession_panel_illumina.txt** contains 83 viruses to be used in the Illumina panel v1. **This file excludes the human control**
* In v2, human control were added. We have 94 genes. Gene names are stored in **illumina_resp_human_control.txt**
* The file **accession_panel_twist.txt** contains 1160 viruses to be used in the twist panel.

