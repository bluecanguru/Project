# 🧬 RBP-ID: Web-Based Tool for Phage Receptor-Binding Protein Identification

RBP-ID aims to be a bioinformatics platform for identifying and annotating **receptor-binding proteins (RBPs)** in bacteriophage genomes. Phage RBPs dictate host specificity and are essential in phage therapy, biosensing, and microbiome engineering. However, their detection remains challenging due to structural diversity and low sequence conservation. RBP-ID addresses this through a hybrid computational pipeline combining **homology searches**, **machine learning**, and **comparative genomics**.



## 🔍 Background

Phages infect bacteria with high specificity through RBPs—proteins that recognize and bind to bacterial surface receptors. These proteins are key targets in biotechnology and synthetic biology, enabling:

- *Targeted bacterial control* (e.g., AMR therapies)
- *Microbiome modulation*
- *Biosensor development*
- *Synthetic phage engineering*
- *Structural insights*



## ⚙️ Core Features

- Comprehensive RBP Datasets
- Fast Homology Search
- Machine Learning Integration
- Structural and Domain-Based Insights
- User-Friendly & Reproducible
- Designed with open-source tools and a modular structure for easy reproducibility, customization, and community development.



## 🧪 Methodology

1. **Dataset Compilation**
   - **Validated RBPs** from curated databases (UniProtKB, NCBI, PDB) and literature sources
   - **Computed RBPs** from literature sources

2. **Sequence Comparison & Clustering**
    - **DIAMOND** to map similarities between known and candidate RBPs
    - **K-means** to cluster sequences by similarity (unsupervised)
    - **KNN** to classify new RBPs using Euclidean distance metrics (supervised)

3. **Prediction Validation**
    - RBP FASTA files
    - Statistical assessments (e.g., alignment scores, p-values)



## 📖Repository structure
    📂 data/                # Raw and processed data files
    📂 scripts/             # Scripts for data treatment and methodology
    📂 results/             # Output files, plots, and reports
    📂 docs/                # Documentation and final reports 
    📄 README.md            # Project overview and instructions



## 🛠 Setup
1. Clone the repository:
```bash
git clone https://github.com/bluecanguru/Project
```
2. Install required dependencies:
```bash
pip install -r requirements.txt
```



📚 Dependencies
- Python 3.10+
- Biopython
- Scikit-learn
- DIAMOND
- Pandas, NumPy



## 📝Contribution
- [Cátia Rosário](https://github.com/bluecanguru)

---

## 📜Licença
This project is open source and available under the MIT License.
