
# Supervised Cell Type identification using Single-Cell RNA-seq Data

## Algorithms
This project focuses on identifying cell types in single-cell RNA-seq data. Three state-of-the-art algorithms are used for classification in this project. The algorithms used are as follows:
1. SVM
2. Random Forest
3. KNN 

## Feature Selection

Instead of using a correlation matrix, three efficient feature selection techniques are used to identify the essential features. Feature selection is used for determining the most influential features. Regarding the dataset used, these features are referred to as Biomarkers or Highly Variable Genes, which are crucial for deciding the cell type. 

1. Chi2
2. Annova - F Test
3. Information Gain 

## Best Number of Features

We have also identified the best number of feataures used for each model

## Hyperparamater Tuning 

For hyperparameter tuning Bayesian Search Optimization from skopt is used for hyperparameter tuning. This hyperparameter tuning method is faster than Randomized Search and Grid Search CV.

## Libraries  

- Scikit-learn
- Skopt
- Numpy
- Pandas


## Repository Link

To deploy this project the repository can be downloaded from the following link.

https://github.com/yashcoder007/Supervised-Cell-Type-Breast-Cancer-Detection-using-Single-Cell-RNA-seq-Data.git



## Dataset
Three standard scrna-seq datasets are used for experimentation in this project.

- Baron-human1 (Data1) Human-Pancreas, code: GSM2230757 
- Baron-human2 (Data2) Human-Pancreas & code: GSM2230758 
- PBMC (Data3) & Prepheral Blood

The preprocessed datasets are uploaded in the repository for experimentation purposes.




## Link of the Published Paper

This paper was presented in IWBBIO (International Work-Conference on Bioinformatics and Biomedical Engineering) in 2022. The paper was published in Lecture Notes in Bioinformatics. The link of the paper is: https://link.springer.com/chapter/10.1007/978-3-031-07802-6_28
## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yash-trivedi-898004160/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)

