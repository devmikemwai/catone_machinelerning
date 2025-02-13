# 21/07360 Michael Mwai
# Machine Learning Programming
# BSD 3204
# Cat One

# Food Spoilage Prediction using Machine Learning

## Overview
This project predicts potential food spoilage using machine learning techniques based on supply chain data.

## Project Structure
- **supply_chain_data.csv**: Synthetic dataset generated for training and analysis, the synthetic data was generated due to lack of matching data source online for my problem statement.
- **cleaned_supply_chain_data.csv**: Preprocessed dataset with numeric scaling and encoding.
- **Traffic Ml Notebook.ipynb**: Jupyter notebook with the entire workflow.

## Dependencies
- Python 3.12+
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

## Setup Instructions
1. **Clone the repository:**
    ```bash
    git clone https://github.com/devmikemwai/food-spoilage-prediction.git
    cd food-spoilage-prediction
    ```
2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Running the Project
- Run the Jupyter notebook to generate synthetic data, preprocess it, and visualize insights.
    ```bash
    jupyter lab
    ```

## Key Features
- **Data Generation:** Synthetic data creation for temperature, humidity, transport time, and packaging types.
- **Exploratory Data Analysis (EDA):** Histograms, box plots, and correlation heatmaps.
- **Data Preprocessing:** One-hot encoding and feature scaling.

## Results
- Visualizations for data distribution and correlations.
- Cleaned dataset for model training.

## Acknowlegments
Special thanks to my lecturer Mr. Stanely Munga at KCA University for his taking me through the unit Machine Learning Programming in my Software Development Degree.

## License
This project is licensed under the MIT License.
