# 🧬 DNA Bioinformatics Toolkit

The DNA Bioinformatics Toolkit is a browser-based tool designed for basic genetic sequence analysis. It allows users to input DNA sequences or upload FASTA files and instantly perform common bioinformatics operations.

---

## 🚀 Features

- ✅ DNA sequence validation (A, T, G, C)
- 🔁 DNA → RNA transcription
- 🔄 Reverse complement calculation
- 📊 GC content analysis
- 📂 FASTA file parsing support
- 🧪 Protein translation (single-letter amino acid code)

---

## 🧪 Protein Translation

The toolkit translates DNA sequences into proteins using the standard genetic code:

- Reads DNA in **codons (triplets)**
- Converts each codon into a **single-letter amino acid**
- Stop codons are represented as `*`
- Unknown codons are represented as `X`

---

## 📥 Input Methods

You can provide DNA sequences in two ways:

### 1. Manual Input
Paste a DNA sequence directly into the text area.

### 2. FASTA File Upload
Upload `.fasta` or `.txt` files.  
FASTA headers (`>sequence_name`) are automatically ignored.

---

## 🧬 Example Input

ATGGCCATTGTAATA

---

## 📊 Example Output

DNA Sequence:
ATGGCCATTGTAATA

RNA Sequence:
AUGGCCAUUGUAAUA

Reverse Complement:
TATTACAATGGCCAT

GC Content:
33.33%

Protein (1-letter AA):
MAIVI


---

## ⚙️ How It Works

- JavaScript processes raw DNA input in real time
- Codon table maps triplets → amino acids
- FASTA parser extracts sequences from headers
- GC content calculated using frequency of G and C bases

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks or dependencies)

---

## 📈 Future Improvements

- 🧬 3-frame translation support
- 🔍 Open Reading Frame (ORF) detection
- 🎨 Codon highlighting visualization
- 📦 Export results as FASTA/JSON
- 🧠 Protein molecular weight calculator
- 🌐 Integration with UniProt API

---

## 👨‍💻 Author

Built as a **bioinformatics + coding learning project**, combining:

- Genetics 🧬  
- AI exploration 🤖  
- Software engineering 💻  
- Experimental tools development ⚙️

I first built this bioinformatics tool in Perl during a programming course at the University of Glasgow while completing my PhD, to support my PCR and DNA sequence analysis workflows. Recently, I rebuilt it with AI using HTML, CSS, and JavaScript as a simple browser-based application. This version also supports DNA sequence file uploads for quick and accessible analysis.

---

## ⭐ Purpose

This project is designed for:
- Learning bioinformatics basics
- Practicing JavaScript development
- Exploring DNA → protein translation

---

## 📜 License

This project is open-source and free to use for educational purposes.
