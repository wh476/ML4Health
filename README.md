# Hate Speech Detection

## Description

This project utilizes the pretrained BERTweet model to conduct multiclass classification of Tweets into hate speech, offensive language, and neutral language.

## Setup
To get started with this project, follow these steps:

1. Clone the repository with the following command:
git clone https://github.com/wh476/ML4health.git
  
2. Install the required dependencies:
Run the following command:
pip install -r requirements.txt

3. Run the following Jupyter Notebook one by one:
- `src/data_cleaning.ipynb`
- `src/baseline_models_auto.ipynb`
- `src/BERTweet_multiclass.ipynb`
- `src/visualization_of_comparison.ipynb`

## File Structure
- `dataset/`: Contains raw data and processed dataset.
- `src/`: Source code files for the project.
   - `data_cleaning.ipynb`: Script to clean and prepare data. Conducts statistical analysis and visualization on the raw data.
   - `baseline_models_auto.ipynb`: Sets up and evaluates 2 baseline models: linear regression and random forest.
   - `BERTweet_multiclass.ipynb`: Trains and evaluates the BERTweet model for the multiclass classification task.
   - `visualization_of_comparison.ipynb`: Generates graphs and figures to compare the outcomes of different models and parameters.
- `results/`: Stores output from scripts, specifically figures.






