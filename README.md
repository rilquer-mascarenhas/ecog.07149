# Investigating the relative role of dispersal and demographic traits in predictive phylogeography

Dataset for manuscript:

[Investigating the relative role of dispersal and demographic traits in predictive phylogeography](https://doi.org/10.1111/ecog.07149).

Description:
- `data/afmtdna.csv` - metadata of all specimens, including their GenBank accession number, OTU, locality coordinates, locus and fasta sequence.
- `data/alignments/` - alignments for each OTU and locus.
- `data/rf_data.rds` - input matrix for Random Forest models. Each row represents a pair of localities and their associated information, i.e., mid-point coordinates; geographic, genetic and environmental distances; OTU and their ecological traits; locus.
- `data/spp_trait_data.csv` - original trait information utilized for each OTU. 

Code for this manuscript can be found [here]([https://rmascarenhas.org/resources](https://github.com/rilquer-mascarenhas/ecog.07149_code).
