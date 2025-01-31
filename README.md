# 🧬 DNA to Protein Translator

This was the first project I completed as part of a course. The task was not very difficult: to create a code that **automatically reads DNA sequences**, **performs transcription and translation**, and **saves the result to a file**.

---

## 📋 **Table of Contents**
- [Project Description]
- [Technologies Used]
- [Installation]
- [Usage]
- [Example Data]
- [MOST Important Note]

---

## 📝 **Project Description**

The project performs the following tasks:
1. **Reads DNA sequences** from a FASTA file.
2. **Transcribes** DNA into RNA.
3. **Translates** RNA into a protein using a codon table.
4. **Saves the results** to an output file.

---

## 🔧 **Technologies Used**

The project is implemented in **Python** and uses the **Biopython** library to handle FASTA files.

---

## 🚀 **Installation**

1. Clone the repository from GitHub:
   git clone **https://github.com/Elskene-Sashina/Course---Python-for-Data-analysis-in-Science.-Project-1.git**

2. Install biopython library and import SeqIO:
**pip insall biopython**
**from Bio import SeqIO**

---

## ⚙️ **Usage**

1.Place your FASTA file in the project directory.

2.Find the section with the comment #TRY at the end of the code and update the file name:
resulting_function('PUT_YOUR_NAME_FILE.fasta')

3.The results will be saved to the specified output file.

---

## 📊 **Example Data**

Input File ('PUT_YOUR_NAME_FILE.fasta'):

\>Example DNA sequence

ATGGCCATTGTAATGGGCCGCTGAAAGGGTGCCCGATAG

---

## 🔍 **MOST Important Note**

At the end of the code, you will see the following section:

**#TRY**
**resulting_function('PUT_YOUR_NAME_FILE.fasta')**

Here, you must specify the name of your input FASTA file.

Good luck! 🍀
