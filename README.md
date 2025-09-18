# Life Expectancy Model



Life Expectancy Data Analysis

This project analyzes global life expectancy using data from the World Health Organization (WHO) and the United Nations (UN) for 193 countries (2000–2015). The notebook covers:

- Data cleaning and imputation for missing values
- Exploratory data analysis (EDA) with visualizations
- Outlier detection and handling
- Feature selection using correlation and Kruskal-Wallis tests
- Data transformation (log, normalization, encoding)
- Model training and hyperparameter tuning for:
- Linear Regression
- Random Forest
- XGBoost
- LightGBM
- Gradient Boosting
- Model evaluation using RMSE, R², and confidence within a 3-year tolerance
- Comparison of all models to identify the best performer
The project demonstrates a full machine learning workflow for predicting life expectancy and identifying key health, economic, and social factors that influence it.

This project produce model that can predict Life expectancy with 90 percent confidence with tolerance of 3 years 
## Use Cases
- Healthcare Planning:
Hospitals and clinics can use the model to prioritize patient care, allocate resources, and plan interventions for at-risk individuals.

- Insurance Underwriting:
Insurance companies can assess risk more accurately for life insurance policies, leading to fairer premiums and better risk management.

- Public Health Policy:
Governments and NGOs can identify populations with lower life expectancy, enabling targeted health campaigns and resource allocation.

- Personal Health Management:
Individuals can use predictions to make informed lifestyle changes, seek preventive care, or plan for retirement and long-term care.

- Clinical Trials:
Pharmaceutical companies can select suitable candidates for clinical trials based on predicted life expectancy, improving study outcomes.

- Elderly Care Services:
Assisted living facilities can tailor care plans and services based on residents’ predicted life expectancy.

- Actuarial Analysis:
Actuaries can use the model for pension planning, social security forecasting, and other long-term financial products.
# Setup:
Run the `SetYouUp.ipynb` file to get started.

# Running the Project
0. Run `SetYouUp.ipynb`
1. Open the project folder in your terminal.
2. Start Jupyter Lab with `poetry run jupyter lab` or launch Visual Studio Code with `poetry run code .` (ensure VS Code is added to your system PATH to use the latter command).
3. If using VS Code, select the kernel that matches the project folder name.


## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. 
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         stats_model and configuration for tools like black
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── stats_model   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes stats_model a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    └─── dataset.py              <- Scripts to download or generate data
```

--------

