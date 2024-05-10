# Hate Speech Detection

## Description

This project explores three resampling methods: SMOTE for oversampling, ENN for undersampling, and SMOTE-ENN for a combined approach, and applies these methods alongside the BERTweet model and baseline models like Logistic Regression and Random Forest to conduct multiclass classification of Tweets into hate speech, offensive language, and neutral language.

## Setup
To get started with this project, follow these steps:

1. Clone the repository with the following command:
``` python
git clone https://github.com/wh476/ML4health.git
```
2. Create and activate a virtual environment, then install the required dependencies:
Run the following command:
``` python
python -m venv env
source env/bin/activate
```
``` python
pip install -r requirements.txt
```

3. Run the following Jupyter Notebook one by one:
- `src/data_cleaning.ipynb`
- `src/word_importance.ipynb`
- `src/baseline_models_auto.ipynb`
- `src/BERTweet_multiclass.ipynb`
- `src/visualization_of_comparison.ipynb`

## File Structure
- `dataset/`: Contains raw data and processed dataset.
- `src/`: Source code files for the project.
   - `data_cleaning.ipynb`: Script to clean and prepare data. Conducts statistical analysis and visualization on the raw data.
   - `word_importance.ipynb`: Conducts TF-IDF analysis, specifically unigrams and bigrams across three categories.
   - `baseline_models_auto.ipynb`: Sets up and evaluates 2 baseline models: linear regression and random forest.
   - `BERTweet_multiclass.ipynb`: Trains and evaluates the BERTweet model for the multiclass classification task.
   - `visualization_of_comparison.ipynb`: Generates graphs and figures to compare the outcomes of different models and parameters.
- `results/`: Stores output from scripts.






