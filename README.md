# Healthcare_ML_Project

# Cardiovascular Disease Prediction

This project aims to predict the risk of cardiovascular disease (CVD) using machine learning techniques. It involves analyzing a dataset containing various factors that may impact cardiovascular health, such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more. By building predictive models, we can identify the key factors associated with CVD and develop a system for effective heart attack prediction.

## Dataset Description

The dataset used in this project contains the following variables:

- Age: Age in years
- Sex: 1 = male; 0 = female
- cp: Chest pain type
- trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
- chol: Serum cholesterol in mg/dl
- fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise-induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: Slope of the peak exercise ST segment
- ca: Number of major vessels (0-3) colored by fluoroscopy
- thal: 3 = normal; 6 = fixed defect; 7 = reversible defect
- Target: 1 or 0 (indicating the presence or absence of cardiovascular disease)

## Project Structure

- `Healthcare_ML_dataset.xlsx`: Excel file containing the dataset
- `Healthcare_ML_Project.ipynb`: Jupyter Notebook with the code for data analysis and model building
- `Requirements.txt`: Text file listing the required libraries and their versions
- `README.md`: Markdown file providing an overview of the project

## Instructions

1. Install the required libraries by running `pip install -r requirements.txt`.
2. Open the `Healthcare_ML_Project.ipynb` notebook in Jupyter Notebook or any compatible environment.
3. Run the notebook cells sequentially to perform data inspection, preprocessing, exploratory data analysis, and model building.
4. Adjust the data preprocessing and model parameters as needed.
5. Explore the findings and insights from the data analysis and model results.
6. Modify or extend the code to further investigate additional research questions or improve model performance.
7. Share your feedback or contributions by creating an issue or pull request in the GitHub repository.

## Results

The data analysis and model building process provide insights into the factors influencing cardiovascular disease. The project includes the following key findings:

- Distribution of CVD across different age categories.
- Composition of patients with respect to sex and their relationship to CVD.
- Anomalies in resting blood pressure and their association with heart attacks.
- Relationship between cholesterol levels and the occurrence of CVD.
- Impact of peak exercising on the likelihood of a heart attack.
- The role of thalassemia in cardiovascular disease.
- The contribution of other factors in determining the occurrence of CVD.

The baseline models, logistic regression, and random forest, achieved an accuracy of X% and X%, respectively, in predicting the risk of heart attacks. The correlation analysis and feature selection techniques provided insights into the importance of different variables in the prediction models.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use the code and findings for research or educational purposes.

## Acknowledgements

We are grateful to the open-source community for the valuable resources and libraries that contributed to this project.

Please feel free to reach out with any questions, suggestions, or collaborations.

---
