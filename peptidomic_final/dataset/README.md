# Files

### peptidomic_data
The dataset retrieved from MS/MS when run through PEAKS X combined with the NCBI Human_20413_20190124 proteomic database resulted in 3 types of xlsx-files per sample: peptide-files and protein-peptide-files. The filetypes contained unique information regarding sequence and protein-distribution, and was utilized when deemed appropriate. 

### antimicrobial_map.xlsx
This file was a result of merging the Deep-AmPEP30 data with python dataframes, in order to create the antimicrobial score. This was used to get the antimicrobial score and to create the piecharts of protein substrates for antimicrobial peptides.

### Data_litterature.xlsx
This file was the result of searching the litterature for sequences. It also contains the result form cross-checking that data with our dataset using a python script.

### output_proteasix.xlsx
This file contains the output from Proteasix. 


### trombin.xlsx
This file contains the data from Rathi et al. regarding trombin degradation by aureolysin.

### heatmap.xlsx
This file contains the result from Deep-AmPEP30 and was used to create the heatmap. 

### difference_data.xlsx
This file contains the top 50 most distinct peptides in the infected and non-infected group. This was calculated by subtracting spectral counts between the infected and non-infected group.
