# data

## Summary of strain names, run names and accessions for genome data in [Almeida et al 2015](http://onlinelibrary.wiley.com/doi/10.1111/mec.13341/abstract)
**EBI-ENA Data Archive Scerevisiae DB.tsv**

## Data used in [Tilakaratna and Bensasson](http://www.g3journal.org/content/7/9/2919)

### TilakaratnaBensasson17

Tilakaratna, V., Bensasson, D., 2017. Habitat Predicts Levels of Genetic Admixture in Saccharomyces cerevisiae. G3: Genes, Genomes, Genetics g3.117.041806. https://doi.org/10.1534/g3.117.041806

**CEN1.tree** to **CEN16.tree**
 
These are 16 neighbour joining F84 distance trees in Newick format: one for each of 16 centromere loci in Saccharomyces cerevisiae. The bootstrap values shown are from a total of 10,000 bootstraps, and trees are unrooted. The 80 S. cerevisiae strains shown in each tree were completely homozygous and are fully described in Table S1 of Tilakaratna and Bensasson. 

**CEN1forcbyc.gfa** to **CEN1forcbyc.gfa**

These are 16 alignments in gapped fasta format for centromeres and flanking DNA used to generate the trees.

## Data used in Bensasson et al 2018

Bensasson, D., Dicks, J., Ludwig, J.M., Bond, C.J., Elliston, A., Roberts, I.N., James, S.A., 2018. Diverse lineages of Candida albicans live on old oaks. Genetics (in press). Previously in: bioRxiv 341032. https://doi.org/10.1101/341032

### Bensasson\_etal2018

Data for ploidy and admixture analysis in Candida albicans

## Data and scripts used in Bensasson et al 2018

Bensasson, D., Dicks, J., Ludwig, J.M., Bond, C.J., Elliston, A., Roberts, I.N., James, S.A., 2018. Diverse lineages of Candida albicans live on old oaks. Genetics (in press). Previously in: bioRxiv 341032. https://doi.org/10.1101/341032

**Bensasson etalTableS1.xlsx**

Table S1 referred to in the Bensasson et al 2018 paper.

**Bensasson_etalTableS3.tsv**

Table S3 referred to in the manuscript. This is a table in text format with tab separated values summarizing heterozygosity analyses for every strain. This includes exact counts of high quality heterozygous base calls (highQualityHetCount); the total length of high quality sequence (highQualityLength; bases with a phred-scaled quality score over 40); the proportion of high quality heterozygous sites; the length of regions that have undergone Loss of Heterozygosity (LOHlength) assessed in 100 kb windows;  heterozygosity analysis after excluding LOH regions, centromeres and annotated repeats (annotationLohFilteredHetCount, annotationLohFilteredLength, annotationLohFilteredHeterozygosity); heterozygosity analysis after excluding LOH regions, centromeres and annotated repeats, and regions with more than double the expected read depth (depthFilteredHetCount, depthFilteredLength, depthFilteredHeterozygosity); heterozygosity analysis at 948,860 nucleotide sites that are common to all strains (sitesIn950kbHetCount, sitesIn950kbLength, sitesIn950kbHeterozygosity).

**bchr1.mfa.zip** to **bchrR.mfa.zip**

The whole chromosome alignments of 62 strains that were concatenated (using alcat.pl) and used to generate the genome-wide phylogeny in Figure 2a. Note that all insertions relative to the reference strain SC5314 haplotype A version 22 (GCF\_000182965.3 from the NCBI reference database) were excluded. As a result, these alignments are on the same coordinate system as the reference and therefore it's corresponding annotations. These sequences were generated by mapping Illumina reads to a reference, therefore as well as insertions, large insertions, duplications, and all other rearrangements will be missed. Low quality sequence (phred-scaled quality below 1 in 10,000, ie q40) is represented with "n". Heterozygous sites are represented using IUPAC ambiguity codes.

**Alignments of Hirakawa et al (2015) genomes**

Our whole chromosome alignments of the short-read genome data published in Hirakawa et al (2015; doi: 10.1101/gr.174623.114) are the example dataset (chr1.mfa to chrR.mfa) in faChrompaintData/. They were generated in the same way as the bchr\*.mfa.zip alignments.

