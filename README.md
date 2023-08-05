# Deep-Learning-GAIN-Pharmacogenetic-Analysis
The proposed architecture utilizes EPH-Gain for imputation in tabular data and incorporates a CNN for image processing. The model aims to predict residual dosage and also employs LASSOCV for signature identification.

Executing various notebook files, each serving a specific purpose. Here is a summary of each file and its corresponding functionality:

The notebook named 'gexpGAIN.ipynb' is dedicated to implementing the EPH (Enhanced Population Health) technique for imputing missing gene tissue expression data. It carries out this imputation process for the AA Cohort, EUR Cohort, and the entire Total Data, effectively handling missing values across the gene tissue expression dataset.

The 'baseline.ipynb' notebook conducts a comparative analysis of several imputation methods, including Average, Median, KNN, and MICE. Its primary objective is to assess and contrast the performance of these baseline techniques when applied to impute gene tissue expressions.

The 'SignatureIdentification.ipynb' notebook serves the purpose of identifying cohort-specific signatures related to the response to warfarin. By executing this notebook on both the AA Cohort and EUR Cohort datasets, specific genes and tissues associated with warfarin response can be detected using the LASSO-CV (Least Absolute Shrinkage and Selection Operator with Cross-Validation) technique.

The 'IGTD.ipynb' notebook is employed to transform tabular data into images. To achieve this, it requires specific modifications to the code in order to set the correct path for either the cohort-specific data or the entire total dataset. When executed, this notebook generates images corresponding to the AA, EUR, or Total Data, depending on the path specified during the run.

Three distinct notebook files are provided for building models that predict warfarin dosage. The 'CNN - No Scaling implementation.ipynb' notebook is designed to create models for the entire dataset. On the other hand, the 'CNN - No Scaling implementation -AA.ipynb' notebook is dedicated to generating models specifically tailored to the AA Cohort. Similarly, the 'CNN - No Scaling implementation -EUR.ipynb' notebook is utilized for creating models specific to the EUR Cohort.

gexpGAINCNNtry.ipynb file is not part of the main project, it was an experiment to create a convolutional Neural Network with GAIN model to apply imputation on missing pixels of IGTD generated images.

By running the relevant notebook files and making the necessary path adjustments, each component of the project can be successfully implemented. These files together facilitate gene tissue expression imputation, baseline method comparisons, signature identification, image generation, and model building for predicting warfarin dosage.
