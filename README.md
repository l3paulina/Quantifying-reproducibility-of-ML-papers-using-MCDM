# ReadMe for the Quantifying reproducibility of ML papers using MCDM Research Paper Computation

## Python Version and Library Versions:
- python 3.13.3,
- pandas: 2.2.2,
- numpy: 1.26.4,
- matplotlib: 3.9.2,
- seaborn: 0.13.2,
- scipy: 1.13.1,
- statsmodels: 0.14.2,
- scikit-learn: 1.5.1,
- xgboost: 3.1.0

## Dataset Files:

### 1. Dataset 1.csv
The first dataset used in the research paper from D. Olszewski, et al, for the creation of reproducibility criteria for machine learning research papers. This file already contains data after part of the filtering from the 3.2 section was performed in Excel: the "Reproduced" column was filtered to only "0" and "1" values.

### 2. Dataset 2.csv
The second dataset used in the research paper from E. Raff, for the creation of reproducibility criteria for machine learning research papers. This file already contains data after most of the data transformations from the 3.2 section were performed in Excel: the values were replaced respectively to the instructions given in that section.

### 3. New Annotated Dataset.xlsx
The new dataset created from sampling a subset of from D. Olszewski, et al., containing 139 research papers, described in section 3.3, used in the evaluation and example analyses of the created quantitative reproducibility measure with WSM and TOPSIS for machine learning research papers. The first page in the Excel file is the authors' annotation of the research paper's reproducibility criteria scores, the second page contains "ChatGPT" annotations of the research paper's reproducibility criteria scores, the third page contains the final reproducibility criteria score annotation for the research papers.

### 4. 10 Research Papers Dataset 1.csv
10 research paper dataset randomly sampled from the new annotated dataset, used in the example analysis of the quantitative reproducibility measure for machine learning research papers.

## Code Files:

### 1. Code for Dataset 1 Analysis.ipynb
The code for the data analysis: exploratory data analysis, hypothesis testing, logistic regression and classification tasks with the dataset 1, from D. Olszewski, et al. Additionally, the random sampling is shown to sample a subset of the dataset 1, containing 139 research papers, described in section 3.2, used in the evaluation and example analyses of the created quantitative reproducibility measure with WSM and TOPSIS for machine learning research papers. The code is provided with the outputs.

### 2. Code for Dataset 2 Analysis.ipynb
The code for the data analysis: exploratory data analysis, hypothesis testing, logistic regression and classification tasks with the dataset 2, from E. Raff. The code is provided with the outputs.

### 3. Code for Evaluation and Example Analyses.ipynb
The code for the evaluation and example analyses of the created quantitative reproducibility measure with WSM and TOPSIS for machine learning research papers. In addition, the code includes the evaluation of simple single/two-criterion baseline models (code availability, data availability, code OR data, and code AND data) and a sensitivity analysis for the AHP derived weights. The code is provided with the outputs.

### 4. Code for Cohen's kappa calculation.ipynb
The code for the Cohen's kappa calculation to assess annotation reliability, inter-annotator agreement between human and ChatGPT-assisted annotations. The code is provided with the outputs.
