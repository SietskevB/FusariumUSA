# Microbiome responses to natural Fusarium infection in field-grown soybean plants

This repository contains code and files that support the analyses presented in "Microbiome responses to natural Fusarium infection in field-grown soybean plants".
Raw sequencing data is available in the European Nucleotide Archive (ENA) at EMBL-EBI under accession number PRJEB87115 (https://www.ebi.ac.uk/ena/browser/view/PRJEB87115). 

The ITS2 and 16S data was preprocessed separately. Therefore, in directory "Preprocessing", there is one directory for ITS2 and one for 16S preprocessing steps.
Directory "Figures and tables" contains code and files used for the figures and tables in the manuscript.

Unfortunately, some files were too large to include on GitHub. This includes several tables for the 16S preprocessing steps.

## IMPORTANT
The field work originally included four fields. In the manuscript, data from three fields is shown.
One field was later excluded due to low disease severity and uncertainty regarding the identity of the disease that was observed.
You can check the metadata for all fields, including the excluded field, in [USfields_samplingdata.xslx](USfields_samplingdata.xlsx).

In the files and code provided here, this excluded field was called "field 1".
Fields 1-3 in the manuscript correspond to fields 2-4 in the files and code.

**Because steps such as feature calling depend on all data that is supplied, the files here include the unpublished field (field 1 in the files on GitHub).
These files are not included as raw sequencing data in the ENA!**
