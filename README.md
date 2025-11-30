Spectral Clustering: A Gentle Introduction and Genomics Application
===================================================================

This repository contains the Python code, examples, and data used to generate the figures and findings presented in the paper, **"A gentle introduction to spectral clustering"** by Benjamin Couéraud and Enikő Regényi (2025).

The purpose of this code is to synthesize complex mathematical concepts (Graph Theory, Linear Algebra, Probability Theory) and demonstrate their practical application in high-dimensional biological data analysis.

🚀 Repository Structure
-----------------------

The code is organized to mirror the paper's logical flow, moving from fundamental concepts to complex application:

*   notebooks/
    
    *   1\_laplacian\_intuition.ipynb: Code accompanying Sections 1 & 2 (Continuous and Discrete Laplacian).
        
    *   2\_spectral\_basics.ipynb: Code accompanying Sections 3 & 4 (Graph Laplacian, Eigenvalues, and Eigenvectors).
        
    *   3\_random\_walk\_sim.ipynb: Code for the Random Walk simulation (Section 7, Probabilistic Interpretation).
        
    *   4\_genomics\_application.ipynb: Full implementation of the Spectral Clustering methodology on the bulk RNA-seq data (Final Section).
        
*   data/
    
    *   input\_data.RData: Processed bulk RNA-seq count matrix, similarity matrix, and metadata used for the genomics application
        
*   LICENSE.md: The full text of the MIT License.
    

🛠️ Setup and Installation
--------------------------

To run the analysis and reproduce the figures locally, follow these steps.

### 1\. Requirements

We recommend setting up a virtual environment (e.g., using conda or venv).

This project requires Python 3.9+ and the following packages:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   # Recommended environment setup  conda create -n spectral-env python=3.10  conda activate spectral-env  # Install required packages  pip install pandas numpy scikit-learn matplotlib seaborn networkx   `

### 2\. Running the Notebooks

All code is contained within the Jupyter notebooks in the notebooks/ directory.

1.  Start Jupyter: jupyter lab or jupyter notebook
    
2.  Open the notebooks sequentially (1 through 4) to follow the paper's logic.
    

📄 Citation
-----------

If you use this code or the spectral clustering application methodology in your own work, please cite the associated paper:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   @article{coueraud2025spectral,    author = {Couéraud, Benjamin and Regényi, Enik{ő}},    title = {A gentle introduction to spectral clustering},    journal = {Preprint},    year = {2025},    url = {[https://github.com/eregenyi/spectral_graph_theory](https://github.com/eregenyi/spectral_graph_theory)}  }   `

📝 License
----------

This project is open-source and licensed under the **MIT License**.

See the [LICENSE.md](LICENSE.md) file for full details.
