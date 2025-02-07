# Biological Data Project: Protein Domain Family Characterization

This repository contains the code, models, data, and documentation for the project *"Functional and Structural Characterization of a Protein Domain Family"*. The focus of the project is the Lipase/Vitellogenin domain family (Pfam ID: PF00151), specifically in Homo sapiens. The analysis integrates model building, functional characterization, and motif identification.

---

## Repository Structure
- **`Function/`**: Contains the outputs generated by the notebook, such as processed data and results.
- **`Model/`**:
  - `Building/`: Contains outputs related to the PSSM and HMM model construction.
  - `Evaluation/`: Contains evaluation results of the models against SwissProt annotations.
- **`Taxonomy/`**: Taxonomic analysis outputs, including lineage data and phylogenetic trees.
- **`Motifs/`**: Outputs related to motif discovery within disordered regions.
- **`BD Report/`**: final PDF of the project report.


---

## Project Overview

### Objective
The aim of the project is to characterize the Lipase/Vitellogenin domain family by:
1. Constructing sequence models (PSSM and HMM).
2. Evaluating these models against SwissProt database annotations.
3. Analyzing taxonomic distribution, functional enrichment, and motif conservation.

### Key Features
- **Sequence Models**: Built using PSI-BLAST and HMMER based on a representative sequence.
- **Taxonomy Analysis**: Phylogenetic insights into protein distribution across species.
- **Functional Insights**: Gene Ontology enrichment analysis for biological functions.
- **Motif Discovery**: Identification of conserved motifs within disordered regions using ProSite and ELM patterns.

---

## Usage

### Prerequisites
- **Software**:
  - [NCBI-BLAST+](https://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/)
  - [HMMER](http://hmmer.org/)
  - [Clustal Omega](http://www.clustal.org/omega/)
  - [JalView](http://www.jalview.org/)
  - Python 3.x

- **Databases**:
  - [UniProt](https://www.uniprot.org/)
  - [Pfam](https://pfam.xfam.org/)
  - [Gene Ontology](http://geneontology.org/docs/download-ontology/)

### Steps to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/maloooon/Protein_Domain_Family_Characterization.git
   cd Protein_Domain_Family_Characterization
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook BD_Project_notebook.ipynb
   ```
3. Follow the steps in the notebook:
   - **Model Building**: Generate PSSM and HMM models.
   - **Evaluation**: Assess the models against SwissProt annotations.
   - **Taxonomy Analysis**: Visualize lineage distribution.
   - **Motif Discovery**: Identify conserved motifs in disordered regions.

---

## Results
- **Model Performance**: PSSM and HMM models evaluated for precision, recall, and other metrics.
- **Taxonomic Insights**: Visualization of domain conservation across species.
- **Functional Enrichment**: Key biological processes identified via GO annotations.
- **Motif Discovery**: Conserved motifs linked to functional hotspots.

---

## Contributions
This project was developed by:
- [**Marlon Helbing**](https://github.com/maloooon)
- [**Alberto Calabrese**](https://github.com/Albi1999)
- [**Lorenzo Baietti**](https://github.com/BaioSbubens)


---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments
- [UniProt Knowledgebase](https://www.uniprot.org/)
- [Pfam Protein Families Database](https://pfam.xfam.org/)
- [Gene Ontology Consortium](http://geneontology.org/)

</div>

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=plastic" height="25"/>
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?logo=Jupyter&logoColor=white&style=plastic" height="25"/>
  <img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual Studio Code-007ACC?logo=VisualStudioCode&logoColor=white&style=plastic" height="25"/>
  <img alt="Anaconda" src="https://img.shields.io/badge/Anaconda-44A833?style=plastic&logo=anaconda&logoColor=white&logoSize=auto" height="25"/>
  <img alt="Google Colab" src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=plastic&logo=googlecolab&logoColor=white&logoSize=auto" height="25"/>
  <img alt="Latex" src="https://img.shields.io/badge/Latex-008080?style=plastic&logo=latex&logoColor=white&logoSize=auto" height="25"/>
  <img alt="Overleaf" src="https://img.shields.io/badge/Overleaf-47A141?style=plastic&logo=overleaf&logoColor=white&logoSize=auto" height="25"/>
</p>
