# resume_shortlisting_model
This project focuses on analyzing resume data and building machine learning models to predict whether a resume will be shortlisted based on various extracted features.
## Project Overview
- The dataset contains resume details with multiple fields such as career objectives, skills, education, experience, and matching scores.
- Extensive preprocessing was done to handle missing values and combine text features.
- Feature engineering involved merging relevant text columns and vectorizing them using TF-IDF.
- Three classification models were built and evaluated:
  - Logistic Regression
  - Random Forest with hyperparameter tuning using GridSearchCV
  - Gradient Boosting Classifier
- Performance metrics such as accuracy, classification report, and confusion matrix are used for evaluation.
- 
## How to Run

1. Clone the repository.
2. Install dependencies (pandas, numpy, scikit-learn, matplotlib, seaborn).
3. Run the Jupyter notebook in your environment.
4. Load your dataset in the specified path or update the path in the notebook.

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
