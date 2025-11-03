# Phylogenetic Analysis of 3 SARS-CoV-2 Sequences

This project contains a phylogenetic comparison between three SARS-CoV-2 genomes performed using **Galaxy**.

### Sequences
- **NC_045512.2**  Reference sequence  
- **PQ726075.1** / **PQ726148.1**  Sample sequences

### Software & Workflow
1. **MAFFT Online (Galaxy)** — used for multiple sequence alignment.  
   - Input: `Galaxy20-[sequences (5).fasta] (1).fasta`  
   - Output: `Galaxy21-[MAFFT on data 20] (1).fasta`  
2. **FastTree** — used to build the phylogenetic tree.

### Results
- The aligned sequences are available in the FASTA output file.  
- The phylogenetic tree can be viewed in the `.png` image file included in this repository.

---

> **Note:** All analyses were performed using Galaxy EU (https://usegalaxy.eu) tools.
