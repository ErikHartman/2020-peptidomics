# Source code

The code is divided into 2 parts. 1. peptidomic_analysis. This contains all the analysis conducted on the data using Python libraries. 2. formatting. This contains all the formatting required to use open source software like Deep-AmPEP30, Proteasix and Peptigram. 

### peptidomic_analysis
The code is indexed as follows: 

```bash
0. Import and methods

1. Acute Wound fluid samples
1.1 Data import 
1.2 Amino acid profile
1.3 N/C-terminal table
1.4 N/C-terminal over spectral count graph
1.5 Grouped N/C-terminal table (supplementary)
1.6 Grouped N/C-terminal over spectral count graph (supplementary)
2. Non-infected samples
1.1 Data import
1.2 Amino acid profile
1.3 N/C-terminal table
1.4 N/C-terminal over spectral count graph
1.5 Grouped N/C-terminal table (supplementary)
1.6 Grouped N/C-terminal over spectral count graph (supplementary)
3. Infected samples
1.1 Data import
1.2 Amino acid profile
1.3 N/C-terminal table
1.4 N/C-terminal over spectral count graph
1.5 Grouped N/C-terminal table (supplementary)
1.6 Grouped N/C-terminal over spectral count graph (supplementary)
4. Group analysis
4.1 Import and create dataframes
4.2 Non-infected venn
4.3 Infected venn
4.4 Difference table
4.5 Between groups venn
5. Heatmap
5.1 Import and create dataframes
5.2 Import heatmap.xlsx and construct dataframes and antimicrobial score sum/mean/std
5.3 Create heatmap
6. Antimicrobial protein substrate pie charts
6.1 Infected
6.2 Non-infected
6.3 Acute Wound Fluid
7. Protein substrate pie charts
7.1 Acute Wound Fluid
7.2 Infected
7.3 Non-infected
8. Finding peptides from literature
8.1 Searching the dataset
8.2 Spectral counting of peptide sequences

### Supplementary 
S1. Exclude HB-proteins
S.1.1 Acute Wound Fluid
S.1.2 Infected
S.1.3 Non-infected

S2. Spectral count barcharts
S.2.1 Without SC cutoff value
S.2.2. With SC cutoff value
```
