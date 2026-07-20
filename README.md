<!-- Importación de Fuentes de Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Nunito:wght@400;600;800&family=Tinos:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">

<!-- Banner Principal con Gradiente de la Marca Personal -->
<div style="background: linear-gradient(135deg, #fce1ec 0%, #f0c5df 35%, #eae7fa 70%, #eff0f8 100%); padding: 40px 30px; border-radius: 20px; text-align: center; box-shadow: 0 10px 25px rgba(0,0,0,0.05); font-family: 'Nunito', sans-serif;">
    <h1 style="color: #2c3e50; font-size: 2.5em; font-weight: 800; margin: 0; font-family: 'Nunito', sans-serif;">🧬 Sliding Window GC Content Analysis</h1>
    <h3 style="color: #4a5568; font-weight: 600; margin-top: 10px; font-family: 'Tinos', serif; font-style: italic; font-size: 1.3em;">A Data Science & Bioinformatics Exploration of the pBR322 Plasmid</h3>
    <hr style="border: 0; height: 2px; background: linear-gradient(to right, transparent, #c95c9e, transparent); margin: 20px auto; width: 60%;">
    <p style="color: #2c3e50; font-size: 1em; font-weight: 600; margin-bottom: 0;">
        <b>Author:</b> Valeria Velázquez Vázquez &nbsp;|&nbsp; 
        <b>Tools:</b> Python 3 • Biopython • Matplotlib
    </p>
</div>

<br>

> 🌐 **Select Language / Selecciona tu Idioma / Sprache Wählen:**
>
> <details>
> <summary><b>🇲🇽 Español (Haz clic para desplegar)</b></summary>
>
> <br>
>
> <div style="font-family: 'Nunito', sans-serif; color: #2c3e50;">
>
> ### 📖 Descripción del Proyecto
> ¡Bienvenidos a este repositorio! En este proyecto realizamos la transición del aprendizaje básico de sintaxis en Python hacia la **Ciencia de Datos aplicada a la Bioinformática**. 
>
> Analizamos la secuencia genómica completa de **pBR322**, uno de los primeros y más importantes plásmidos vectores de clonación en *Escherichia coli*.
>
> <div style="background-color: #eff0f8; border-left: 6px solid #f0c5df; padding: 18px; border-radius: 8px; margin: 20px 0;">
>    <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-family: 'Nunito', sans-serif;">💡 ¿Por qué es importante el contenido GC?</h4>
>    <p style="margin: 0; color: #4a5568; font-family: 'Tinos', serif; font-size: 1.05em;">
>       A nivel molecular, la Guanina (G) y la Citosina (C) están unidas por <b>tres puentes de hidrógeno</b> (en comparación con los dos de Adenina y Timina). Esto otorga una mayor estabilidad física a las regiones ricas en GC. Mediante un algoritmo de <b>ventana deslizante</b>, podemos detectar cómo varía esta proporción e identificar características biológicas clave como el <b>Origen de Replicación (Ori)</b>, regiones codificantes o eventos de transferencia horizontal de genes.
>    </p>
> </div>
>
> ### 🛠️ Características Principales
> - **Extracción de datos:** Procesamiento de archivos `.fasta` con el módulo `Bio.SeqIO` de **Biopython**.
> - **Cálculo de Métricas:** Determinación del promedio global de contenido GC ($\approx 53.75\%$).
> - **Algoritmo de Ventana Deslizante:** Implementación iterativa dividiendo la secuencia en fragmentos de $500 \text{ bp}$ con pasos de $100 \text{ bp}$.
> - **Visualización:** Gráfico con `matplotlib`, incluyendo la línea base del promedio y áreas bajo la curva coloreadas con la paleta de la marca personal.
>
> </div>
>
> </details>
>
> <details>
> <summary><b>🇩🇪 Deutsch (Klicken zum Ausklappen)</b></summary>
>
> <br>
>
> <div style="font-family: 'Nunito', sans-serif; color: #2c3e50;">
>
> ### 📖 Projektübersicht
> Willkommen zu diesem Repository! In diesem Projekt verbinden wir grundlegende Python-Programmierung mit angewandter **Datenwissenschaft in der Bioinformatik**.
>
> Wir analysieren die vollständige Genomsequenz von **pBR322**, einem der ersten und am häufigsten verwendeten Klonierungsvektor-Plasmide in *Escherichia coli*.
>
> <div style="background-color: #eff0f8; border-left: 6px solid #f0c5df; padding: 18px; border-radius: 8px; margin: 20px 0;">
>    <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-family: 'Nunito', sans-serif;">💡 Warum ist der GC-Gehalt wichtig?</h4>
>    <p style="margin: 0; color: #4a5568; font-family: 'Tinos', serif; font-size: 1.05em;">
>       Auf molekularer Ebene sind Guanin (G) und Cytosin (C) durch <b>drei Wasserstoffbrückenbindungen</b> verbunden (im Vergleich zu zwei bei Adenin und Thymin). Dies verleiht GC-reichen Regionen eine höhere thermische und physische Stabilität. Durch einen <b>Schiebefenster-Algorithmus (Sliding Window)</b> können wir Schwankungen im GC-Gehalt kartieren und wichtige biologische Strukturen wie den <b>Replikationsursprung (Ori)</b> oder genreiche Regionen identifizieren.
>    </p>
> </div>
>
> ### 🛠️ Hauptmerkmale
> - **Datenverarbeitung:** Einlesen von `.fasta`-Dateien mit `Bio.SeqIO` aus **Biopython**.
> - **Metrik-Berechnung:** Bestimmung des globalen durchschnittlichen GC-Gehalts ($\approx 53.75\%$).
> - **Schiebefenster-Algorithmus:** Iterative Analyse der Sequenz in Abschnitten von $500 \text{ bp}$ mit Schritten von $100 \text{ bp}$.
> - **Visualisierung:** Professionelles Diagramm mit `matplotlib` unter Verwendung der individuellen Farbpalette.
>
> </div>
>
> </details>

<br>

<!-- Sección predeterminada en Inglés -->
<div style="font-family: 'Nunito', sans-serif; color: #2c3e50;">

## 🇬🇧 English Overview

### 📖 Project Description
Welcome! This project transitions core Python programming skills into **Applied Data Science in Computational Biology**. 

Here, we analyze the complete genomic sequence of **pBR322**, one of the earliest and most fundamental *E. coli* cloning vector plasmids.

<div style="background-color: #eff0f8; border-left: 6px solid #f0c5df; padding: 18px; border-radius: 8px; margin: 20px 0;">
   <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-family: 'Nunito', sans-serif;">💡 Why GC Content Matters</h4>
   <p style="margin: 0; color: #4a5568; font-family: 'Tinos', serif; font-size: 1.05em;">
      At the molecular level, Guanine (G) and Cytosine (C) form <b>three hydrogen bonds</b> (compared to two between Adenine and Thymine). This endows GC-rich regions with higher physical stability. By implementing a <b>sliding window algorithm</b> across the genome, bioinformaticians can detect structural variations to pinpoint critical biological milestones, such as <b>Origins of Replication (Ori)</b>, gene density shifts, or horizontal gene transfer events.
   </p>
</div>

---

### 💻 Code Highlight

Below is a snippet demonstrating sequence extraction and global baseline calculation using **Biopython**:

```python
from Bio import SeqIO

# 1. Load Plasmid Sequence
record = SeqIO.read("pBR322.fasta", "fasta")
sequence = record.seq

# 2. Global Baseline Formula
gc_percentage = (sequence.count("G") + sequence.count("C")) / len(sequence) * 100
print(f"pBR322 Length: {len(sequence)} bp | Global GC: {gc_percentage:.2f}%")
```
## How to Run This Project
Want to run this notebook on your local machine? Follow these simple steps:
1. Clone this repository:
```bash
git clone [https://github.com/val-velvaz/Bioinformatics-GC-Content-Analysis.git](https://github.com/val-velvaz/Bioinformatics-GC-Content-Analysis.git)
cd Bioinformatics-GC-Content-Analysis
```
2. Install required packages:
```bash
pip install biopython matplotlib jupyter
```
3. Launche the Jupyter Notebook:
```bash
jupyter notebook Bioinformatics_GC_Content_Project.ipynb
```
## 🗂️ Code Structure
```
├── Bioinformatics_GC_Content_Project.ipynb   # Main documented Jupyter Notebook
├── pBR322.fasta                              # Plasmid genomic data (NCBI J01749.1)
└── README.md                                 # Project documentation
```
## 🧬 Where to Find Genomic Databases?
If you want to replicate this project with other plasmids, bacteria, viruses, or complete genomes, the following public repositories are among the most widely used in computational biology and bioinformatics.

| Database | Description | Typical Use |
|----------|-------------|-------------|
| **NCBI GenBank** | One of the largest public repositories of nucleotide sequences, including genomes, plasmids, viruses, genes, and proteins. | Download DNA sequences in FASTA or GenBank format for analysis. |
| **RefSeq (NCBI)** | A curated, non-redundant collection of reference genomes and sequences. | Obtain high-quality reference genomes for comparative analyses. |
| **ENA (European Nucleotide Archive)** | Europe's primary nucleotide sequence archive, synchronized with GenBank and DDBJ. | Access genomic and sequencing data submitted worldwide. |
| **DDBJ (DNA Data Bank of Japan)** | The Japanese partner of the International Nucleotide Sequence Database Collaboration (INSDC). | Retrieve nucleotide sequences shared with GenBank and ENA. |
| **UniProt** | Comprehensive database of protein sequences and functional annotations. | Explore protein function, domains, and biological pathways. |
| **Ensembl** | Genome browser providing annotated genomes for many species. | Gene annotation and comparative genomics. |
| **Protein Data Bank (PDB)** | Repository of experimentally determined 3D protein and nucleic acid structures. | Study protein structure and molecular interactions. |
| **IMG (Integrated Microbial Genomes)** | Database specializing in microbial genomes and metagenomes. | Comparative analysis of bacterial and archaeal genomes. |
| **GISAID** | Repository for influenza and SARS-CoV-2 genomic sequences. | Viral evolution and mutation tracking. |

## 📁 Common File Formats

When downloading genomic data, you'll commonly encounter the following formats:

| Format | Description |
|--------|-------------|
| **FASTA (.fasta, .fa, .fna)** | DNA, RNA, or protein sequences. |
| **GenBank (.gb, .gbk)** | Sequence with annotations (genes, CDS, promoters, etc.). |
| **GFF / GTF** | Genome annotation files describing genomic features. |
| **FASTQ** | Raw sequencing reads including quality scores. |
| **PDB** | Three-dimensional molecular structures. |

## 🔬 Typical Bioinformatics Workflow

A typical computational biology project follows these steps:

1. Download a genomic sequence from a public database.
2. Load the sequence into Python using **Biopython**.
3. Perform basic quality checks (length, GC content, ambiguous bases).
4. Search for genes, motifs, or restriction enzyme recognition sites.
5. Compare sequences using alignment tools such as **BLAST**.
6. Visualize or summarize the results.

## 🌐 Useful Resources

- **NCBI GenBank:** https://www.ncbi.nlm.nih.gov/genbank/
- **NCBI RefSeq:** https://www.ncbi.nlm.nih.gov/refseq/
- **European Nucleotide Archive (ENA):** https://www.ebi.ac.uk/ena/
- **DNA Data Bank of Japan (DDBJ):** https://www.ddbj.nig.ac.jp/
- **UniProt:** https://www.uniprot.org/
- **Ensembl:** https://www.ensembl.org/
- **Protein Data Bank (PDB):** https://www.rcsb.org/
- **Integrated Microbial Genomes (IMG):** https://img.jgi.doe.gov/
- **GISAID:** https://www.gisaid.org/

> **Tip:** If you're just getting started, **NCBI GenBank** is the best place to begin. It provides curated genomic sequences, detailed annotations, and seamless integration with Python libraries such as **Biopython**.

<div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <a href="https://github.com/val-velvaz" target="_blank" style="background-color: #ffffff; color: #2c3e50; padding: 10px 22px; border-radius: 25px; text-decoration: none; font-weight: 700; box-shadow: 0 3px 6px rgba(0,0,0,0.08); border: 1px solid #eae7fa; font-size: 0.95em;">
        🐱 GitHub Profile
    </a>
    <a href="https://www.linkedin.com/in/valeria-vel%C3%A1zquez-v%C3%A1zquez-66bb0a301/" target="_blank" style="background-color: #2c3e50; color: #ffffff; padding: 10px 22px; border-radius: 25px; text-decoration: none; font-weight: 700; box-shadow: 0 3px 6px rgba(0,0,0,0.08); font-size: 0.95em;">
        💼 Connect on LinkedIn
    </a>
</div>
