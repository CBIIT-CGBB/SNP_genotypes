SNP genotypes
=====================================================================

### The genotype file contains 2,000 samples and 95,954 SNPs, with each SNP represented by binary alleles. In this file, 0 denotes the first allele homozygous, 2 signifies the second allele homozygous, and 1 indicates heterozygous for the two alleles. The first 1,000 rows are case samples, while the second 1,000 rows are control samples. Due to GitHub's file size limitations, the genotype file was divided into three smaller files (xaa, xab, and xac). To merge these files effortlessly, use the following command:

###   *cat x?? > snp_geno.txt.zip*
