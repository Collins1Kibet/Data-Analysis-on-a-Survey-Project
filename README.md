### Data-Analysis-Survey-project

This repository contains a Jupyter Notebook that analyzes survey data from an Excel file. The analysis includes data cleaning, visualization, and statistical analysis to extract meaningful insights from the survey responses.
I did this project for learning purposes. 

#### Overview

The goal of this project is to analyze survey data to understand the responses better and draw meaningful conclusions. The analysis covers:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Statistical analysis

#### Dataset

The dataset is provided in the `Survey Output Data.xlsx` file. It contains survey responses collected from participants. The columns include:
- `RespondentID`: Unique identifier for each respondent
- `Dates`: Dates at which the survey was conducted
- `Demographic`: Demographic information of the respondent
- `Question1`, `Question2`, `Response1`, `Response2`, ...: Survey Questions and Responses

### Getting Started

#### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required Python packages listed in `requirements.txt`

#### Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/yourusername/survey-data-analysis.git
    cd survey-data-analysis
    ```

2. **Create a virtual environment and activate it**
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**
    ```sh
    pip install -r requirements.txt
    ```

4. **Install Jupyter Notebook**
    ```sh
    pip install notebook
    ```

### Running the Notebook

1. **Start Jupyter Notebook**
    ```sh
    jupyter notebook
    ```

2. **Open the `Script - Data_Manipulation.ipynb` notebook**
    - Navigate to the `Script - Data_Manipulation.ipynb` file in the Jupyter Notebook interface and open it.

3. **Run the cells**
    - Execute the cells in the notebook to perform the analysis.

#### Usage

The notebook is structured as follows:
1. **Introduction**: Overview of the dataset and analysis goals.
2. **Analysis in Excel:** for this particular data, analysis starts in excel to concat the questions and response rows.
3. **Data Loading**: Loading the survey data from the Excel file.
4. **Data Cleaning**: Handling missing values, correcting data types, etc.
5. **Exploratory Data Analysis (EDA)**: Summary statistics and visualizations.
6. **Statistical Analysis**: Hypothesis testing, correlation analysis, etc.
7. **Conclusions**: Summary of findings and insights.

#### Contributing

We welcome contributions! Please fork the repository and submit pull requests.

#### Acknowledgments

- [Pandas](https://pandas.pydata.org/)
- [Jupyter](https://jupyter.org/)

#### Contact

For any questions or suggestions, please open an issue or contact me at collins1kibet@gmail.com
