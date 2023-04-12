# SNP genotypes

The genotype file contains 2,000 samples and 95,954 SNPs. The first 1,000 rows represent case samples, while the latter 1,000 rows correspond to control samples. Due to GitHub's file size limitations, the genotype file was split into multiple smaller files. To easily merge the files, utilize the following command:

cat x?? > snp_geno_combined.txt.zip
