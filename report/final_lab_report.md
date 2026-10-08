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

## 4. Results

### 4.1 General Characteristics of the Chloroplast Genome

The complete chloroplast genome of *Psidium guajava* (NC_033355.1) was characterized using NCBI sequence information and Galaxy analysis.

| Characteristic | Result |
|---|---|
| Scientific name | *Psidium guajava* L. |
| Family | Myrtaceae |
| NCBI RefSeq accession | NC_033355.1 |
| GenBank accession | KX364403.1 |
| Genome type | Chloroplast |
| Genome topology | Circular |
| Genome length | 158,841 bp |
| Number of sequence records | 1 |
| GC content | Approximately 37% |

Galaxy's Compute sequence length tool confirmed a sequence length of 158,841 bp. The geecee tool reported a GC fraction of 0.37.

### 4.2 Chloroplast Genome Organization

The chloroplast genome has a quadripartite structure consisting of a large single-copy (LSC) region, a small single-copy (SSC) region, and two inverted-repeat regions (IRa and IRb).

| Region | Length (bp) |
|---|---:|
| Large single-copy (LSC) | 87,675 |
| Small single-copy (SSC) | 18,464 |
| Inverted repeat A (IRa) | 26,351 |
| Inverted repeat B (IRb) | 26,351 |
| Total genome length | 158,841 |

These region lengths were obtained from the published genome characterization by Jo et al. (2016), rather than measured directly in Galaxy.

### 4.3 Gene Annotation

The GenBank annotation was examined to identify the gene content of the chloroplast genome.

| Gene category | Number |
|---|---:|
| Unique protein-coding genes | 78 |
| Unique tRNA genes | 30 |
| Unique rRNA genes | 4 |
| Total unique protein-coding and RNA genes | 112 |
| Annotated gene features, including duplicated copies | 132 |
| Annotated pseudogene features | 3 |

The number of annotated gene features is greater than the number of unique genes because some genes occur in duplicated regions.

### 4.4 Functional Gene Categories

The annotated chloroplast genes participate in several important biological processes.

| Gene group | Examples | Main function |
|---|---|---|
| Photosystem I | psaA | Light-dependent electron transport |
| Photosystem II | psbA | Light-dependent electron transport |
| ATP synthase | atpB | ATP production |
| Cytochrome b6f complex | petB | Photosynthetic electron transport |
| Carbon fixation | rbcL | Carbon dioxide fixation |
| RNA polymerase | rpoB | Transcription |
| Ribosomal proteins | rpl2 | Protein synthesis |
| RNA processing | matK | RNA splicing |

### 4.5 RNA Genes, Introns, and Pseudogenes

The genome annotation includes 30 unique tRNA genes and 4 unique rRNA genes. These genes contribute to protein synthesis within the chloroplast.

Intron-containing genes include clpP and ycf3. The rps12 gene is notable for its trans-splicing arrangement.

Three pseudogene features were identified in the annotation: infA, ycf1, and rps19.

### 4.6 Galaxy Analysis Outputs

The following results were generated using Galaxy and documented in GitHub:

- Sequence-length output from Compute sequence length.
- GC-content output from geecee.
- Screenshots showing the completed Galaxy analyses.

The original sequence files, gene annotation tables, and genome summary are available in the repository's `data/`, `results/`, and `figures/` folders.

**Data sources:** NCBI NC_033355.1; Galaxy analysis outputs; Jo et al. (2016).

## 5. Discussion and Interpretation

### 5.1 Chloroplast Genome Characteristics

The complete chloroplast genome of *Psidium guajava* contains 158,841 base pairs and has a GC content of approximately 37%, based on the Galaxy analysis. These results describe the genome's basic sequence characteristics.

The genome has a circular, quadripartite organization consisting of the large single-copy (LSC), small single-copy (SSC), and two inverted-repeat (IR) regions. The region sizes reported by Jo et al. (2016) are consistent with the total genome length obtained using Galaxy.

### 5.2 Gene Content and Biological Functions

The chloroplast genome contains genes involved in photosynthesis, ATP synthesis, transcription, translation, and RNA processing.

Genes such as *psaA* and *psbA* participate in photosynthetic electron transport, while *rbcL* contributes to carbon fixation. The *atpB* gene is involved in ATP production, and *rpoB* participates in transcription.

The presence of these genes demonstrates that the chloroplast genome encodes components needed for its specialized functions. However, many other proteins required for chloroplast activities are encoded by nuclear genes.

### 5.3 RNA Genes and Introns

The tRNA and rRNA genes are important for protein synthesis within the chloroplast. Transfer RNAs deliver amino acids during translation, while ribosomal RNAs form essential components of ribosomes.

Intron-containing genes, including *clpP* and *ycf3*, require RNA processing to produce mature transcripts. The *rps12* gene is particularly interesting because it undergoes trans-splicing, in which RNA segments originating from separate genomic regions are joined together.

These features demonstrate that chloroplast gene expression involves RNA processing in addition to transcription and translation.

### 5.4 Pseudogenes and Duplicated Genes

The GenBank annotation identifies pseudogene features associated with *infA*, *ycf1*, and *rps19*. Pseudogenes may result from gene disruption, sequence changes, or the presence of incomplete gene copies.

The two inverted-repeat regions also contribute to gene duplication. As a result, the total number of annotated gene features can exceed the number of unique genes.

These observations highlight the importance of distinguishing unique gene counts from total annotated gene copies.

### 5.5 Comparison with Mitochondrial and Nuclear Genomes

Plastid and mitochondrial genomes share characteristics such as their endosymbiotic origins, possession of their own DNA, and dependence on nuclear-encoded proteins.

However, plastid genomes primarily encode proteins associated with photosynthesis and related processes, while mitochondrial genomes encode proteins involved in cellular respiration and energy metabolism.

Compared with nuclear genomes, plastid genomes are generally smaller and often more conserved in gene organization. This makes them useful for evolutionary studies and species identification. However, plastid genomes provide only part of the genetic information needed to understand an organism.

### 5.6 Significance and Limitations of the Analysis

This activity demonstrated how publicly available genome sequences and bioinformatics tools can be used to characterize a chloroplast genome.

Galaxy provided measurements of sequence length and GC content, while the NCBI GenBank annotation provided information about gene content and organization.

One limitation is that the LSC, SSC, and inverted-repeat boundaries were not independently determined using Galaxy. Their reported lengths were obtained from the published reference.

Another limitation is that the activity examined existing sequence annotations rather than experimentally confirming gene expression or protein function.

Overall, the analysis provided a useful overview of the structure, composition, and biological significance of the *Psidium guajava* chloroplast genome.

## 6. Conclusion

The complete chloroplast genome of *Psidium guajava* L. was successfully characterized using NCBI sequence information, Galaxy bioinformatics tools, and GenBank annotations.

The genome consists of 158,841 base pairs, with one sequence record and a GC content of approximately 37%. Its quadripartite organization includes a large single-copy region, a small single-copy region, and two inverted-repeat regions.

The annotation-based characterization identified 78 unique protein-coding genes, 30 unique tRNA genes, and 4 unique rRNA genes. Genes involved in photosynthesis, transcription, translation, and RNA processing were also examined, along with intron-containing genes, pseudogenes, and duplicated gene copies.

The activity demonstrated the usefulness of plastid genomes in studying plant genetics, genome organization, and evolutionary relationships. It also highlighted the importance of combining bioinformatics results with published references and existing genome annotations.

Overall, the objectives of the activity were achieved through the analysis and documentation of the *Psidium guajava* chloroplast genome.

## 7. References

1. National Center for Biotechnology Information (NCBI). *Psidium guajava* chloroplast, complete genome. RefSeq accession NC_033355.1. https://www.ncbi.nlm.nih.gov/nuccore/NC_033355.1

2. Jo, S., et al. (2016). Complete plastome sequence of *Psidium guajava* L. (Myrtaceae). *Mitochondrial DNA Part B*, 1(1), 612–614. https://doi.org/10.1080/23802359.2016.1209096

3. Galaxy Community. Galaxy: An accessible platform for reproducible computational research. https://usegalaxy.org/

## 8. Data Availability

The FASTA and GenBank files, Galaxy analysis outputs, screenshots, gene annotation tables, and supporting reports are documented in the GitHub repository:

https://github.com/trayvillashekhan-oss/cmb-plastid-genome-psidium-trayvilla

The Galaxy analysis history is named **Plastid_Psidium_Trayvilla**.

The original sequence data are publicly available through NCBI under accession **NC_033355.1**.
