# Sentiment Analysis on Social Media Comments

This repository contains the materials and code for the project **Sentiment Analysis on Social Media Comments** conducted by Team Delta as part of the Machine Learning course in the MSc Business Analytics program.

## Repository Structure

### /dataset/
This folder contains the datasets used for training and testing our models. The data has been split into indexed and preprocessed versions for different stages of the pipeline.

- **/index/**  
  - `df_test_indexed.csv`: The test dataset with added indexes.  
  - `df_training_indexed.csv`: The training dataset with added indexes.

- **/preprocessed/**  
  - `df_test_preprocessed.csv`: The test dataset after preprocessing.  
  - `df_training_preprocessed.csv`: The training dataset after preprocessing.  
  - `test.csv`: The raw test dataset.  
  - `train.csv`: The raw training dataset.

### /notebooks/
This folder contains Jupyter notebooks used during various stages of the project:

- **indexing.ipynb**: Code for indexing the datasets.
- **preprocessing.ipynb**: Code for data preprocessing (e.g., cleaning, tokenization).
- **training_with_tuning.ipynb**: Code for model training and hyperparameter tuning.

### Report
The full project report is available in PDF format and includes:

- Introduction and problem statement
- Data preprocessing steps
- Model selection and training process
- Hyperparameter tuning
- Results and evaluation metrics
- Conclusion and future work

### Presentation
A presentation summarizing the key points and findings of the project is included in PDF format, covering:

- Project overview
- Machine learning approach
- Key results and insights
- Final conclusions

## Usage
Clone the repository and navigate through the notebooks for detailed code execution. The datasets required for training and testing are located in the `/dataset/` folder.

1. **Indexing:** Run `indexing.ipynb` to add indexes to the raw datasets.
2. **Preprocessing:** Execute `preprocessing.ipynb` to clean and preprocess the data.
3. **Model Training:** Use `training_with_tuning.ipynb` for training the model and performing hyperparameter tuning.

## Contact
For any queries or issues related to the project, please contact **Team Delta**.

