# EDS-Kcr: Deep supervision based on large language model for identifying protein lysine crotonylation sites across multiple species

**EDS-Kcr** is a novel bioinformatics tool designed to identify lysine crotonylation (Kcr) sites in proteins using advanced deep learning techniques. It integrates the **ESM2 protein language model** with **deep supervision** to improve prediction accuracy across multiple species. This tool can aid researchers in understanding protein post-translational modifications (PTMs), which play key roles in biological processes, disease diagnosis, and drug development.

## Features

- **Deep Supervision**: Enhances prediction accuracy by simultaneously training on multiple tasks.
- **ESM2 Protein Language Model**: Leverages a state-of-the-art protein language model for superior feature extraction.
- **Cross-Species Generalization**: Demonstrates high accuracy across various species, including humans, plants, animals, and microorganisms.
- **User-Friendly Web Interface**: Allows easy input of protein sequences to obtain predictions via a web server.

## Table of Contents
1. [Installation](#installation)
2. [Data Preparation](#data-preparation)
3. [Web Server](#web-server)

## Installation

To use EMT-Kcr, follow these installation steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ZhangHongqi215/EDS-Kcr.git
   cd EMT-Kcr
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```


## Data Preparation

EMT-Kcr accepts protein sequences as input. You can format your data as follows:

- Each sequence should be in the **FASTA** format.

To prepare your dataset, place your input files in the `data/` directory or the specified location in the configuration.

## Web Server

A web-based interface for EMT-Kcr is available, allowing you to input protein sequences and get Kcr site predictions. Visit:

[http://eds-kcr.lin-group.cn](http://eds-kcr.lin-group.cn)

- Navigate to the **TOOL** tab.
- Input a protein sequence or upload a FASTA file.
- Click **Submit** to view the predicted Kcr sites.



