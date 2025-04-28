# RNA-seq Data Analysis

This repository contains Jupyter notebooks and datasets focused on **RNA sequencing (RNA-seq) data analysis**.  
It explores statistical techniques, dimensionality reduction, data normalization, and exploratory analysis of single-cell RNA-seq datasets.

---

## 📁 Repository Structure and Contents

| Folder | Script | Description |
|:------|:------|:-------------|
| (root) | `AitchisonStats.ipynb` | Statistical analysis based on Aitchison geometry (compositional data analysis). |
|  | `RNA-seq-tut2.ipynb` | Tutorial on RNA-seq data processing and basic analysis. |
|  | `W1stats.ipynb` | Statistical exploration using Wasserstein (W1) distances. |
|  | `artificialdata.ipynb` | Synthetic dataset generation and analysis. |
|  | `cellslog.ipynb` | Log-transformed RNA-seq cell data exploration. |
|  | `exploringScanPy.ipynb` | Initial exploration using ScanPy library for single-cell RNA-seq data. |
| **`12June23/`** | `Cosinedistance.ipynb` | Calculation and exploration of cosine distances between cell profiles. |
|  | `LogTransformingData.ipynb` | Effects of log-transforming RNA-seq data. |
|  | `W1distance.ipynb` | Wasserstein-1 distance calculations between cell populations. |
|  | `artificialdata.ipynb` | More artificial data experiments. |
|  | `cellslog.ipynb` | Log-transformed analysis on another dataset. |
| **`data/`** | Various `.csv` files | Matrices representing RNA-seq expression profiles (ARL, CLR, log-transformed, etc.). |

---

## 📚 Topics Covered

- **Compositional data analysis** using Aitchison geometry
- **Log transformations** and normalization of count data
- **Cosine distances** for similarity analysis between RNA-seq samples
- **Wasserstein distances** for population comparison
- **Dimensionality reduction** and **exploratory analysis** with ScanPy
- Creation and exploration of **artificial RNA-seq datasets**

---

## 🛠 Requirements

- **Python 3.8+**
- Key libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scipy`
  - `scanpy`
  - `scikit-learn`

Install the libraries with:
```bash
pip install numpy pandas matplotlib seaborn scipy scanpy scikit-learn
```

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/RNAseq_dataanalysis.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd RNAseq_dataanalysis
   ```
3. **Open the notebooks**:
   ```bash
   jupyter notebook
   ```
   Then browse and open any of the `.ipynb` files for analysis.

---

## ✨ Highlights

- Hands-on exploration of single-cell RNA-seq datasets.
- Statistical distance calculations between different data representations.
- Techniques for handling and transforming high-dimensional biological data.

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file if available.

---

## 👨‍💻 Author

Developed by Adrian Guel.
