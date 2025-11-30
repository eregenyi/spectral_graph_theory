Spectral Clustering: A Gentle Introduction and Genomics Application
===================================================================

This repository contains the Python code, examples, and data used to generate the figures and findings presented in the paper, **"A gentle introduction to spectral clustering"** by Benjamin Couéraud and Enikő Regényi (2025).

The purpose of this code is to synthesize complex mathematical concepts (Graph Theory, Linear Algebra, Probability Theory) and demonstrate their practical application in high-dimensional biological data analysis.

🚀 Repository Structure
-----------------------

The code is organized to mirror the paper's logical flow, moving from fundamental concepts to complex application:

*   theory/
    
    *   continuous\_laplacian.ipynb: Code accompanying Section 1 (Continuous).
        
    *   graph\_laplacian.ipynb: Code accompanying Section 2-5 (Discrete Laplacian, Graph Laplacian, Eigenvalues, and Eigenvectors).
        
    *   spectral\_clsutering.ipynb: Code accompanying Section 6 (Spectral Clustering).
        
    *   random\_walk.ipynb: Code accompanying Section 7 (Probabilistic Interpretation).
        
*   application/
    
    *   application.ipynb: Code accompanying Section 8 (Example application in Bioinformatics).
    
    *   data/input\_data.RData: Processed bulk RNA-seq count matrix, similarity matrix, and metadata used for the genomics application
      
        
*   LICENSE.md: The full text of the MIT License.
  
*   README.md: General information of the repo.
    

🛠️ Setup and Installation
--------------------------

To run the analysis and reproduce the figures locally, follow these steps.

### 1\. Requirements

We recommend setting up a virtual environment (e.g., using conda or venv).

This project requires Python 3.9+ And R 4.4.3+

### 2\. Running the Notebooks

All code is contained within the Jupyter notebooks in the theory and application subdirectories.

1.  Start Jupyter: jupyter lab or jupyter notebook
    
2.  Open the notebooks sequentially to follow the paper's logic.
    

📄 Citation
-----------

If you use this code or the spectral clustering application methodology in your own work, please cite our repository. 
Citation will be updated upon publication of our assocated paper.


📝 License
----------

This project is open-source and licensed under the **MIT License**.

See the [LICENSE.md](LICENSE.md) file for full details.
