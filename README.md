# Enhancing-Population-Health-through-Deep-Learning-Based-Pharmacogenetic-Analysis
EPH-Gain based architecture for imputation, Tabular data - Image - CNN - predict residual dosage, Signature Identification using LASSOCV

The implementation of the project involves running specific notebook files. Here is an overview of each file and its corresponding functionality:

The 'gexpGAIN.ipynb' notebook implements the EPH (Enhanced Population Health) method for imputing missing gene tissue expression data in the AA Cohort, EUR Cohort, and the Total Data. Running this notebook handles the imputation process for the entire gene tissue expression dataset.

In the 'baseline.ipynb' file, various imputation methods such as Average, Median, KNN, and MICE are compared. The purpose of this file is to evaluate and compare the performance of these baseline methods in imputing gene tissue expressions.

The 'SignatureIdentification.ipynb' notebook is used to identify cohort-specific signatures relevant to warfarin response. By running this file on the AA Cohort and EUR Cohort specific genes and tissues associated with warfarin response can be identified using the LASSO-CV method.

To convert tabular data into images, the 'IGTD.ipynb' file is used. The code in this notebook should be modified to specify the correct path for the cohort-specific or total data. Running this notebook generates images for the AA, EUR, or Total Data, depending on the specified path.

For creating models to predict warfarin dosage, three separate notebook files are available. The 'CNN - No Scaling implementation.ipynb' file creates models for the entire dataset. The 'CNN - No Scaling implementation -AA.ipynb' file focuses on models specifically for the AA Cohort, while the 'CNN - No Scaling implementation -EUR.ipynb' file is used for models specific to the EUR Cohort.

gexpGAINCNNtry.ipynb file is not part of the main project, it was an experiment to create a convolutional Neural Network with GAIN model to apply imputation on missing pixels of IGTD generated images.

By executing the appropriate notebook files and modifying necessary paths, each aspect of the project can be implemented. These files collectively enable gene tissue expression imputation, baseline comparisons, signature identification, image creation, and model development for warfarin dosage prediction.
