# Cell and Molecular Biology Laboratory Activity
# Characterization of a Plastid Genome

## Student Information
**Name:** Hobe Palopalo

**Course/Section:** Cell and Molecular Biology - A

---

# Selected Organism

| Item | Information |
|--------|------------|
| Genus | Coffea |
| Species | Coffea arabica L. |
| Family | Rubiaceae |
| Database Source | NCBI GenBank |
| Accession Number | EF044213.1 |
| Genome Type | Complete Chloroplast Genome |
| Genome Size | 155,189 bp |
| GC Content | 37.43% |
| Number of Sequences | 1 |

---

# Question 1:  Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

The selected organism is *Coffea arabica* L., belonging to the family Rubiaceae. The chloroplast genome sequence was obtained from the NCBI GenBank database under accession number EF044213.1. The complete plastid genome has a total length of 155,189 base pairs and is reported as a complete chloroplast genome.

---

# Question 2: What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, fragment, or nuclear sequence?

The GenBank record specifically identifies the sequence as a complete chloroplast genome. The genome consists of 155,189 bp, which is much larger than common barcode markers such as rbcL and matK. The sequence also contains the complete set of chloroplast genes, including protein-coding genes, transfer RNAs, and ribosomal RNAs. In addition, the genome exhibits the typical quadripartite plastid structure consisting of LSC, SSC, and inverted repeat regions.

---

# Question 3: Describe the overall organization of the plastid genome.

The chloroplast genome of *Coffea arabica* contains the typical quadripartite organization present in most flowering plants.

| Region | Size (bp) |
|----------|----------:|
| Large Single Copy (LSC) | 85,159 |
| Small Single Copy (SSC) | 18,135 |
| Inverted Repeat A (IRa) | 25,946 |
| Inverted Repeat B (IRb) | 25,946 |

The overall arrangement follows the standard LSC-IR-SSC-IR structure.

---

# Question 4: Summarize the annotated gene content.

The plastid genome contains 131 annotated genes.

| Gene Type | Number |
|------------|---------:|
| Protein-coding genes | 86 |
| tRNA genes | 37 |
| rRNA genes | 8 |
| Total genes | 131 |

Genes found inside the inverted repeat regions appear twice because the entire IR region is duplicated. Therefore, genes located within one inverted repeat are also present in the second inverted repeat copy.

---

# Question 5: Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| Gene | Functional Group | Function |
|---------|-----------------|-----------|
| psaA | Photosystem I | Encodes a reaction center protein involved in photosynthesis |
| psbA | Photosystem II | Encodes the D1 reaction center protein |
| atpA | ATP Synthase | Participates in ATP production during photosynthesis |
| petA | Cytochrome b6f Complex | Functions in electron transport |
| rbcL | Carbon Fixation | Encodes the large subunit of RuBisCO |
| rpoA | RNA Polymerase | Involved in plastid gene transcription |
| rpl2 | Ribosomal Protein | Component of the large ribosomal subunit |
| rps12 | Ribosomal Protein | Component of the small ribosomal subunit |

These genes are involved in photosynthesis, transcription, translation, and carbon fixation.

---

# Question 6: Identify important RNA and RNA-processing features.

### rRNA Genes

- rrn16
- rrn23
- rrn4.5
- rrn5

### Examples of tRNA Genes

- trnH-GUG
- trnK-UUU
- trnL-UAA
- trnA-UGC

### Genes with Introns

- rpl2
- ndhB
- clpP
- ycf3

Introns are non-coding regions removed from RNA transcripts during RNA processing before translation.

---

# Question 7: Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome.

No major genome rearrangements or gene losses have been reported in the chloroplast genome of *Coffea arabica*. Published studies indicate that coffee plastomes are highly conserved and display only minor nucleotide substitutions and insertions/deletions among cultivars. Gene duplications occur primarily within the inverted repeat regions where genes are naturally duplicated as part of the chloroplast genome structure.

---

# Question 8: What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

Galaxy FASTA Statistics analysis produced the following results:

- Genome size: 155,189 bp
- Number of sequence records: 1
- GC content: 37.43%

Two notable observations are:

1. The plastome is represented by a single sequence record, indicating that the chloroplast genome assembly is complete.
2. The genome contains two large inverted repeat regions, which contribute to structural stability and duplication of several genes.

---

# Question 9: Compare plastid and mitochondrial genomes. Give at least five similarities and five differences.

### Similarities

1. Both are organellar genomes.
2. Both contain their own DNA.
3. Both possess rRNA and tRNA genes.
4. Both are involved in energy-related cellular processes.
5. Both are generally maternally inherited in plants.

### Differences

| Feature | Plastid Genome | Mitochondrial Genome |
|----------|---------------|----------------------|
| Main Function | Photosynthesis | Cellular Respiration |
| Structure | Highly conserved | More variable |
| Gene Content | Photosynthesis-related genes | Respiration-related genes |
| Rearrangements | Rare | Frequent |
| Evolutionary Pattern | Conserved | Dynamic |

---

# Question 10: Explain the practical value of plastid genomes in research.

### Advantages

1. Smaller genome size than nuclear genomes.
2. Easier genome assembly and annotation.
3. High copy number in plant cells.
4. Conserved gene order and structure.
5. Useful for DNA barcoding.
6. Useful for species identification.
7. Useful for phylogenetic studies.
8. Valuable for evolutionary research.
9. Less repetitive DNA than nuclear genomes.
10. Suitable for comparative genomics.

### Limitations

1. Represents only one parental lineage in most plants.
2. Contains less genetic variation than nuclear genomes.
3. Cannot explain many complex traits.
4. Does not fully represent species-wide genetic diversity.
5. Less useful than nuclear genomes for studying quantitative traits.

---

# Plastid vs. Mitochondrial Genome Comparison Table

| Feature | Plastid Genome | Mitochondrial Genome |
|----------|---------------|----------------------|
| Cellular Location | Chloroplast | Mitochondrion |
| Main Biological Function | Photosynthesis | Cellular Respiration |
| Typical Genome Organization | Circular with LSC, SSC, and IR regions | Circular or multipartite |
| Relative Genome Size | Approximately 155 kb | Generally larger and more variable |
| Gene Content | Photosynthesis, transcription, translation | Respiration and ATP production |
| Copy Number | High | High |
| Inheritance | Usually maternal | Usually maternal |
| Recombination and Structural Change | Relatively stable | Frequent rearrangements |
| Mutation Pattern | Conserved | More variable |
| Common Research Applications | DNA barcoding, phylogeny, evolution | Evolutionary and organelle studies |

---

# Galaxy Workflow

## History Name

Plastid_Coffea_Palopalo

## Procedure

1. Downloaded the complete chloroplast genome of *Coffea arabica* from NCBI GenBank.
2. Saved the genome sequence in FASTA format.
3. Uploaded the FASTA file to useGalaxy.org.
4. Created a history named `Plastid_Coffea_Palopalo`.
5. Performed FASTA Statistics analysis.
6. Recorded the sequence length, number of sequences, and GC content.

## Galaxy Results

| Statistic | Value |
|------------|--------|
| Number of Sequences | 1 |
| Genome Length | 155,189 bp |
| GC Content | 37.43% |

---

# References

1. NCBI GenBank. *Coffea arabica* chloroplast complete genome (EF044213.1).

2. Park J. et al. Complete chloroplast genome of *Coffea arabica* 'Typica'.

3. Park J. et al. Complete chloroplast genome of *Coffea arabica* high-production individual.

4. Park J. et al. Complete chloroplast genome of *Coffea arabica* 'Blue Mountain'.

5. useGalaxy.org.
