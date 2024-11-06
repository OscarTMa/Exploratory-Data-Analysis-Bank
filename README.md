# EDA on Banking Dataset

This project provides an in-depth Exploratory Data Analysis (EDA) on a banking dataset, sourced from Kaggle. The goal is to uncover key insights about customer behaviors, relationships between features, and potential predictors for decision-making processes. The analysis is presented in a well-documented notebook, and the project culminates in an interactive dashboard that allows users to explore various data aspects dynamically.

## Project Structure

1. **Introduction to EDA**  
   A theoretical introduction to what EDA is and its importance in the data science workflow. Here, we cover:
   - The objectives of EDA
   - Typical methods and visualizations used in EDA

2. **Dataset Overview**  
   A detailed examination of the dataset, with initial checks and statistics to understand its structure, such as:
   - Dimensions of the dataset
   - Types of data for each column
   - Basic statistical descriptions of numerical variables

3. **Exploratory Data Analysis Notebook**  
   This Jupyter Notebook (`EDA_Banking_Dataset.ipynb`) includes the complete EDA process:
   - **Univariate Analysis**: Studying the distribution of individual features (both numerical and categorical) through histograms and count plots.
   - **Bivariate Analysis**: Examining relationships between pairs of variables using correlation matrices, scatter plots, and box plots.
   - **Multivariate Analysis**: Using correlation matrices and heatmaps to understand how multiple variables interact.
   - **Missing Values**: Identifying and handling missing data, including imputation for both numerical and categorical columns.
   - **Outliers Detection**: Analyzing the presence of outliers using box plots and statistical measures.

4. **Dashboard**  
   An interactive dashboard built with `Plotly Dash` or `Streamlit` to visualize and explore key patterns dynamically. The dashboard allows users to:
   - Filter data by specific categories
   - View the distribution of numerical features based on categories
   - Examine interactive correlation matrices and graphs

5. **Conclusions and Insights**  
   A summary of findings based on the EDA, highlighting key relationships and insights from the dataset.

## Getting Started

### Prerequisites
To run the notebook and dashboard, ensure the following libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn plotly dash streamlit
```

### Running the Notebook
1. Clone this repository to your local machine.
2. Open `EDA_Banking_Dataset.ipynb` in Jupyter Notebook or JupyterLab.
3. Run each cell to follow along with the analysis.

### Running the Dashboard
To launch the dashboard, use one of the following commands, depending on whether you're using Plotly Dash or Streamlit:

For Plotly Dash:
```bash
python app.py  # Assuming the dashboard script is named `app.py`
```

For Streamlit:
```bash
streamlit run app.py
```

## Project Files

- **README.md**: Project overview and setup instructions.
- **EDA_Banking_Dataset.ipynb**: Main notebook with detailed EDA.
- **data/**: Folder containing the dataset (ensure to check licensing from Kaggle if required).
- **app.py**: Dashboard code (either Dash or Streamlit).

## Dataset
The dataset used is from Kaggle and contains banking-related information. This project is only for educational purposes; please refer to Kaggle for the original dataset and its licensing details.

## Contributions
Feel free to submit pull requests for additional features or analysis methods. All contributions are welcome to expand and enhance the project.

## Structure

EDA_Banco_Kaggle/
├── README.md
├── data/
│   └── bank_data.csv
├── notebooks/
│   └── EDA_bank_data.ipynb
└── dashboard/
    ├── app.py
    └── assets/




## License
This project is licensed under the MIT License. Please refer to the LICENSE file for more information.

## Contact
If you have any questions or suggestions, please feel free to open an issue or contact me at oscartibaduiza@hotmail.com.
