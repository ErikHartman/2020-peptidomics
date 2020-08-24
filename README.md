# !In construction!
# 2020-peptidomics
This git repository contains the code and data for a research project conducted by Erik Hartman (bachelor in Biomedical Engineering and Biomedicine) and Karl Wallblom (master in Medicine) at Lunds University during the summer of 2020.

The full scientific article can be found here: xxxxxxxxxxxxxxxxxxxxx

### Background
This project uses LC-MS/MS peptidomic data retrieved from dressing and acute wound fluid to investigate any potential differences between acute, non-infected and infected wound fluids. We used an unbiased results-based approach and simple algorithms and libraries in Python, as well as other open-source software like Deep-AmPEP30, Peptigram and Proteasix, to analyze our data. The git contains all the code necessary to recreate our project, except for the compatability of the web-based 3rd party algorithms, although we've included the necessary formatting, and the output data we retrieved. 

The separate folders contain instructions which hopefully allows you to understand and replicate the code.

### Dataset
The dataset retrieved from MS/MS when run through PEAKS X combined with the NCBI Human_20413_20190124 proteomic database resulted in 3 types of xlsx-files per sample: peptide-files, protein-peptide-files and protein-files.

### Results
Although are dataset was limited, our study resulted in interesting findings - showcasing the power of simple sorting algorithms on peptidomic data. Amongst other things, we showed that infected wounds contain more antimicrobial peptides (AMPs) than healthy ones. These AMPs are generally derived from hemoglobin subunit alpha or beta. Hemoglobin derived peptides exist in a larger extent in infected wounds than in healthy ones. 

### Code
Our code is divided into 3 sections and indexed accordingly. The inter-sample and inter-group general charactersitcs and sequence manipulation indexed 1.1 --> 7.3. Code generating supplementary figures and information is indexed S1.1 --> S1.3. Code used for formatting is indexed F1 --> F


