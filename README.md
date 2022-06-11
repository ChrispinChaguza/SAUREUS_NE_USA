### Data associated with paper "Prophage-encoded immune evasion factors are critical for Staphylococcus aureus host infection, switching and adaptation"

## Output files from the GWAS analysis using FaST-LMM
FaST-LMM output filename | Genetic variant type | Phenotype | Phenotype type
-- | -- | -- | -- 
GENE_ALL.GWAS.FaST-LMM.tar.gz | Gene presence/absence | Human vs animal | Categorical
SNP_ALL.GWAS.FaST-LMM.tar.gz | SNP | Human vs animal | Categorical
Unitigs_ALL.FaST-LMM.tar.gz | Unitigs presence/absence | Human vs animal | Categorical


## Output files from the GWAS analysis using GEMMA
GEMMA output filename | Genetic variant type | Phenotype | Phenotype type
-- | -- | -- | --
GENE_ALL.GWAS.GEMMA.tar.gz | Gene presence/absence | Human vs animal | Categorical     
SNP_ALL.GWAS.GEMMA.tar.gz | SNP | Human vs animal | Categorical
Unitigs_ALL.GEMMA.tar.gz | Unitigs presence/absence | Human vs animal | Categorical 

## SNPs, accessory gene sequences, and unitig sequences
Variants/sequences | Filename | Description
-- | -- | -- 
Unitig presence and absence | Unitigs_ALL.matrix.tar.gz | All unitigs
Unitig presence and absence | Unitigs_ALL.T.tar.gz | Unitigs present in 5-95% isolates
Gene presence and absence | pan_genome_reference_R.tar.gz | All gene sequences
SNPs | SNP.tar.gz | All SNPs
Unitig sequences | UNITIGS.tar.gz | All unitig sequences
Prophage sequences | Prophage_sequences_from_denovo_assemblies.tar.gz | Prophage sequences extracted from de novo assemblies

## Scripts used to annotate SNPs and unitig sequences
Script name | Description
-- | -- 
annotate_SNPs.py | Generates a summary of gene features in a reference genome given SNP position
blast_annotate_fasta.py | Generates a summary of genetic features in GenBank-formatted reference genome(s) associated with given unitig sequences

## Reference
Chrispin Chaguza, Joshua T. Smith, Spencer A. Bruce, Robert Gibson, Isabella W. Martin, and Cheryl P. Andam. ***Prophage-encoded immune evasion factors are critical for Staphylococcus aureus host infection, switching and adaptation***. Under review.
