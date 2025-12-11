Spectral Clustering: A Gentle Introduction and Genomics Application
===================================================================

This repository contains the code and the data to reproduce all figures and analyses presented in **"Spectral Clustering for Interdisciplinary Research: From Graph Theory to RNA-seq Data Analysis"** by Benjamin Couéraud and Enikő Regényi (2025).

The purpose of this code is to synthesize mathematical concepts (Graph Theory, Linear Algebra, Probability Theory) and demonstrate their practical application in high-dimensional biological data analysis.

🚀 Repository Structure
------------

The code is organized to mirror the paper's logical flow, moving from fundamental concepts to complex application:

*   `theory/`
    
    *   `continuous_laplacian.ipynb`: Code accompanying Section 1 (Continuous).
        
    *   `graph_laplacian.ipynb`: Code accompanying Section 2-5 (Discrete Laplacian, Graph Laplacian, Eigenvalues, and Eigenvectors).
        
    *   `spectral_clustering.ipynb`: Code accompanying Section 6 (Spectral Clustering).
        
    *   `random_walk.ipynb`: Code accompanying Section 7 (Probabilistic Interpretation).
 
    *   `requirements.txt`
        
*   `application/`
    
    *   `application.ipynb`: Code accompanying Section 8 (Example application in Bioinformatics).
    
    *   `data/input_data.RData`: Processed bulk RNA-seq count matrix, similarity matrix, and metadata used for the genomics application.
 
    *   `requirements.txt` 
    

🛠️ Requirements
---------------

This project requires Python 3.9+ (theory) And R 4.4.3+ (application). We recommend setting up a virtual environment (e.g., using conda or venv). Further details can be found in `theory/requirements.txt` and `application/requirements.txt` for notebooks in the respective folders.
    

💾 Data
-------

The bulk RNA-seq data included in this repository were originally produced and published by Bajtai and colleagues. For easy access to the tutorial, the repository includes the normalized data, the PCA embedding, the metadata, the derived Graph Laplacian matrix, and its eigenvalues and eigenvectors.

Bajtai, Eszter, et al. "Therapy-induced senescence is a transient drug resistance mechanism in breast cancer." Molecular Cancer 24.1 (2025): 128.

📄 Citation
-----------

If you use this code or the spectral clustering application methodology in your own work, please cite our paper available [here](https://www.preprints.org/manuscript/202512.1031). 

Couéraud,  B., & Regényi,  E. (2025). Spectral Clustering for Interdisciplinary Research: From Graph Theory to RNA-seq Data Analysis. Preprints. https://doi.org/10.20944/preprints202512.1031.v1



📝 License
----------

This project is open-source and licensed under the **MIT License**. See the [LICENSE.md](LICENSE.md) file for full details.
