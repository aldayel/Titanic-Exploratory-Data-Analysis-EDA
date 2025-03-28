# Titanic-Exploratory-Data-Analysis-EDA


This project provides an exploratory data analysis (EDA) of the Titanic dataset. The goal of the analysis is to uncover insights and trends from the data, understand patterns related to passenger survival, and gain experience with data manipulation and visualization techniques using Python.



The project aims to explore and analyze the historical dataset of Titanic passengers. By examining various features such as age, gender, passenger class, and embarkation point, the analysis seeks to answer key questions such as:

- Which groups of passengers had higher survival rates?
- How did socioeconomic factors (e.g., passenger class) affect survival?
- What are the correlations between different variables in the dataset?


## Dataset

The analysis uses the Titanic dataset, which includes information on passengers such as:

- **Passenger ID**
- **Name**
- **Age**
- **Gender**
- **Passenger Class (Pclass)**
- **Survival Status (Survived)**
- **Fare**
- **Embarked Port**
- **Other relevant features**


## Libraries

The project is implemented in Python using :

- **Pandas** for data manipulation and analysis.
- **NumPy** for numerical operations.
- **Matplotlib** and **Seaborn** for data visualization.
- **Jupyter Notebook** for interactive analysis and presentation.


## Project Structure

```
titanic_EDA/
├── data/
│   └── titanic.csv         
├── notebooks/
│   └── titanic_EDA.ipynb    
├── README.md               
└── requirements.txt        
```

## Usage
To set up and run the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/titanic_EDA.git
   cd titanic_EDA
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Jupyter Notebook:**

   ```bash
   jupyter notebook notebooks/titanic_EDA.ipynb
   ```

5. **Explore the analysis:**

   Open the `titanic_EDA.ipynb` notebook in your browser to follow the data exploration, visualization, and insights step-by-step.

## Key Findings

Some insights derived from the analysis include:

- **Survival Analysis:** Identification of key factors influencing survival, such as gender and passenger class.
- **Feature Distributions:** Visualization of age, fare, and other continuous variables to understand their distributions.
- **Correlation Insights:** Analysis of relationships between variables to inform potential predictive modeling efforts.

*For a detailed discussion of the findings, please refer to the notebook.*



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
