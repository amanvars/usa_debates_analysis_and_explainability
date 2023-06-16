# Gaining Insights Into the US Political Landscape Through Congress Speech Analysis

## Structure

### Data Preparation

Data preparation part of the project is implemented in Jupyter notebook and is located in `src/data_preparation.ipynb`.After its execution the raw data as well as the processed data set can be found in the `data` folder.

### Data Analysis

Data analysis part of the project is implemented in R notebook and is located in `src/data_analysis`. The final version with outputs can be found on the generated web page.

### Model and Explainability

Model and Explainability parts of the project project are implemented in Jupyter Notebooks using Pytorch Lightning. Dependencies can be found in `requirements.txt`.

## Source Files

The code within the `src` directory is organized by purpose as folowwing:

- `data_preparation.ipynb`: Download, clean, filter, and prepare speech data.
- `data_analysis`: Analyze the prepared speech dataset.
- `training`: Fine-tune GPT-2 using the aforementioned speeches.
- `prediction_analysis/error_analysis.ipynb`: Analyze a trained model's misclassifications.
- `prediction_analysis/party_switch_analysis.ipynb`: Analyze the model's predictions for the two representatives that switched parties.
- `explainability/shap_and_lime.ipynb`: Explain model predictions using SHAP and LIME methods. Inline comments will help to run some functions according to the requirements.
- `explainability/random_5000.csv`: CSV file of 5000 randomly selected speech from dataset with approximately equal number of R and D classes.
