# Characterization of the Psidium guajava Chloroplast Genome

## 1. Introduction

Plastids are organelles found in plant cells that perform important functions, including photosynthesis and other metabolic processes. Chloroplasts contain their own DNA, which encodes proteins and RNA molecules needed for various chloroplast activities.

In this activity, the complete chloroplast genome of *Psidium guajava* L. (guava), belonging to the family Myrtaceae, was selected for characterization. The genome sequence was obtained from the National Center for Biotechnology Information (NCBI), accession NC_033355.1.

The analysis involved retrieving the genome sequence and annotation, using Galaxy to determine basic sequence characteristics, and examining the organization and gene content of the chloroplast genome. The results were documented in a GitHub repository for reproducibility.

## 2. Objectives

The objectives of this activity were to:

1. Retrieve and verify a complete chloroplast genome from NCBI.
2. Determine genome length, sequence count, and GC content using Galaxy.
3. Describe the organization of the chloroplast genome, including the LSC, SSC, and inverted-repeat regions.
4. Identify annotated protein-coding genes, tRNA genes, rRNA genes, introns, and pseudogenes.
5. Explain the functions of selected chloroplast genes.
6. Compare plastid and mitochondrial genomes.
7. Discuss the advantages and limitations of plastid genomes in biological research.
8. Document the procedures, results, and interpretations in GitHub.

## 3. Materials and Methods

### 3.1 Selection of the Chloroplast Genome

The plant genus *Psidium* was selected for this activity. The complete chloroplast genome of *Psidium guajava* L. (guava), belonging to the family Myrtaceae, was retrieved from the National Center for Biotechnology Information (NCBI).

The selected reference genome has accession number **NC_033355.1**, corresponding to GenBank accession **KX364403.1**. The genome was verified as a complete, circular chloroplast genome.

Two sequence files were downloaded from NCBI:

- FASTA format (`psidium.fasta`) for sequence analysis.
- GenBank format (`psidium_genbank.gb`) for gene annotation and genome characterization.

### 3.2 Sequence Analysis Using Galaxy

The FASTA file was uploaded to the Galaxy platform (usegalaxy.org).

A Galaxy history named **Plastid_Psidium_Trayvilla** was created to organize the analysis.

The following tools were used:

1. **Compute sequence length** — Used to determine the total genome length. The output showed one sequence record measuring 158,841 base pairs.
2. **geecee** — Used to calculate the GC content of the chloroplast genome. The output reported a GC fraction of 0.37, equivalent to approximately 37%.

The analysis outputs were downloaded and saved in the GitHub repository's `results/` folder. Screenshots of the Galaxy results were saved in the `figures/` folder.

### 3.3 GenBank Annotation Analysis

The annotated GenBank record was examined to identify protein-coding genes, transfer RNA (tRNA) genes, ribosomal RNA (rRNA) genes, intron-containing genes, and pseudogenes.

The annotation was also used to examine gene functions and identify notable features, including the trans-spliced `rps12` gene.

Gene annotation tables and a genome summary were saved as CSV files in the `results/` folder.

### 3.4 Chloroplast Genome Organization

The large single-copy (LSC), small single-copy (SSC), and two inverted-repeat (IRa and IRb) regions were described using published information for the selected chloroplast genome.

These region sizes were obtained from the literature rather than calculated directly using Galaxy.

### 3.5 Documentation and Reproducibility

The complete activity was documented in a GitHub repository containing:

- `data/` — Original FASTA and GenBank files.
- `results/` — Galaxy outputs, genome summary, and annotated gene table.
- `figures/` — Screenshots of Galaxy analyses.
- `report/` — Gene characterization, genome comparisons, interpretations, and final laboratory report.

The original NCBI accession number, Galaxy history name, and analysis tools were recorded to support reproducibility.

### 3.6 Reference

Jo, S., et al. (2016). Complete plastome sequence of *Psidium guajava* L. (Myrtaceae). *Mitochondrial DNA Part B*, 1(1), 612–614. https://doi.org/10.1080/23802359.2016.1209096
