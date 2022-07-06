# MBAO 
## Mutation-based Binary Aquila optimizer for gene selection in cancer classification
 
A binary version of Aquila optimizer (BAO) is implemented to tackle Feature Selection(FS) problem in high-dimensional microarray data. This algorithm mimics the Aquila's behaviors in nature during the process of catching the prey. To build a Binary version of AO, twofold adjustments were made: i) a time-varying mirrored S-shaped (TVMS) transfer function is utilized to transform the continuous domain into a binary one. ii) A mutation operator is also suggested to ensure the efficiency of the proposed method for the FS domain. 

##### This is the source codes of the paper: Pashaei, E (2022), Mutation-based Binary Aquila optimizer for gene selection in cancer classification, Computational Biology and Chemistry. 


## How to get started
- Install R 4.1.3 and RStudio 
- Install R Packages
- Download Microarray datasets
- Download the zip files

#### Required dependencies (R packages)
- foreign
- farff
- praznik
- caret
- randomForest
- FSelector
- plyr
- class
- e1071
- pracma

## Usage
To reproduce the full results in the paper, run "main.R" file. 
