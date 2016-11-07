# h2pp
**heritability (h2) partition pipeline**

Pipeline for partitioning the SNP heritability (i.e. proportion of narrow-sense heritability accounted for by commonly segregating variants tagged by GWAS-interrogated SNPs) 

Directories

**GREML** 
This folder will contain pipeline scripts for estimating and partitioning SNP heritabilty from genotype data. 
This involves:
  * Genetic relatedness matrix (GRM) calculation with linkage Disequilibrium Adjusted Kinship estimation software (LDAK)  
  * Restricted maximum likelihood estimation with Genomic Complex Trait Analysis software (GCTA)

**LDSR** 
This folder will contain pipeline scripts for running stratified LD score regression (Finucane et al. __Nat Genet__. 2015) 
This requires:
  * Summary statistics from genome wide association studies (GWAS) 
  * Pairwise LD estimates calculated in ancestry-matched reference panel 
