# BlindFold

**BlindFold** is a lightweight Python utility for **blinding and anonymizing image datasets** prior to analysis.  
It enables unbiased, reproducible scoring of microscopy and image-based assays by removing condition labels while preserving a secure unblinding key.

> *See the data, not the labels.*

## Why BlindFold?

Unblinded image analysis introduces unconscious bias. BlindFold provides a simple, transparent way to enforce blinding without changing downstream workflows.

Blindfold helps you:

- Anonymize image filenames
- Randomize image order
- Strip identifying metadata
- Preserve a secure key for later unblinding

Blindfold is designed for **scientific rigor**, making it appropriate for **methods sections, grants, and regulated research workflows**.

## Features

- 🔒 **Image blinding** via randomized filenames  
- 🗂️ **Original data preserved** (input files are never modified)  
- 🧾 **Key file generation** (CSV mapping original → blinded names)  
- 🧹 **Optional metadata stripping** (EXIF and related metadata)  
- 🔀 **Optional randomized viewing order** for scoring  
- 📁 **Flat or recursive directory support**  
- ⚡ **Single-file Python script** with minimal dependencies  

## Installation

Clone the repository:

```bash
git clone https://github.com/thedavidlab/blindfold.git
cd blindfold
