# Machine Learning Project

## Introduction
This repository contains a machine learning project focused on predicting the chance of admission for prospective students based on various features such as GRE score, TOEFL score, university rating, statement of purpose (SOP), letter of recommendation (LOR), CGPA, and research experience. The project is implemented in a single Jupyter notebook.

## Dataset
The project utilizes the "Admission_Predict_Ver1.1.csv" dataset, which includes information on 500 applicants and their corresponding chance of admission. The dataset contains the following columns:

- Serial No.: Unique identifier for each applicant
- GRE Score: Applicant's GRE score
- TOEFL Score: Applicant's TOEFL score
- University Rating: Rating of the university the applicant is applying to (on a scale of 1 to 5)
- SOP: Statement of Purpose score (on a scale of 1 to 5)
- LOR: Letter of Recommendation score (on a scale of 1 to 5)
- CGPA: Applicant's undergraduate CGPA (on a scale of 1 to 10)
- Research: Research experience (0 for no experience, 1 for experience)
- Chance of Admit: Probability of admission (target variable)

## Project Structure
The project is implemented in a single Jupyter notebook named "admission.ipynb". The notebook contains the following sections:

1. Data Exploration: Explore the dataset, visualize distributions, and analyze correlations between features.
2. Data Preprocessing: Preprocess the data by handling missing values, scaling features, and encoding categorical variables.
3. Model Training: Train various machine learning models on the preprocessed data.
4. Model Evaluation: Evaluate the trained models using performance metrics and visualize the results.

## Getting Started
To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/omarhashem80/graduate-admission`
2. Navigate to the project directory: `cd graduate-admission`
3. Launch Jupyter Notebook: `jupyter notebook`
4. Open the "admission.ipynb" notebook.
5. Run each cell in the notebook sequentially to execute the code and see the results.

## Conclusion
This machine learning project aims to predict the chance of admission for prospective students based on their academic and research profiles. By running the "admission.ipynb" notebook, you can explore the dataset, preprocess the data, train different models, and evaluate their performance. The notebook provides a comprehensive implementation of the entire project in a single file for convenience. Feel free to modify or extend the notebook to suit your specific needs.

Enjoy the project and feel free to contribute or provide feedback!
