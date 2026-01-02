# Pairwise Sequence Alignment of HBB Gene Using Biopython

## 📌 Overview
This project performs **pairwise sequence alignment** of the **Hemoglobin Beta (HBB) gene** among:
- Human (*Homo sapiens*)
- Mouse (*Mus musculus*)
- Chimpanzee (*Pan troglodytes*)

The analysis uses **Biopython** to compare global and local alignment scores and infer evolutionary relationships.

---

## 🎯 Objectives
- Retrieve HBB gene sequences from NCBI
- Perform global and local alignments
- Compare alignment scores between species
- Interpret evolutionary similarity

---

## 🧬 Data Source
Sequences were fetched from the **NCBI Nucleotide Database** using the following accession numbers:

- Human: `NM_000518.5`
- Mouse: `NM_008220.2`
- Chimpanzee: `XM_016928727.2`

---

## 🛠 Tools & Technologies
- Python
- Biopython
- NCBI Entrez
- Google Colab / Jupyter Notebook

---

## 🔬 Methodology
1. Installed Biopython
2. Retrieved sequences using Entrez API
3. Performed:
   - **Global Alignment**
   - **Local Alignment**
4. Compared alignment scores across species

---

## 📊 Results Summary

| Comparison | Global Alignment Score | Local Alignment Score |
|-----------|------------------------|-----------------------|
| Human vs Mouse | 484.0 | 484.0 |
| Human vs Chimpanzee | -2562.0 | 273.0 |

---

## 📌 Conclusion
The alignment results indicate that the **chimpanzee HBB gene is more similar to the human HBB gene than mouse**, supporting known evolutionary relationships.


