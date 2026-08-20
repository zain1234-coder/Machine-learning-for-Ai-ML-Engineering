# 📁 Repository Structure — `Machine-learning-for-Ai-ML-Engineering`

**Repo:** [zain1234-coder/Machine-learning-for-Ai-ML-Engineering](https://github.com/zain1234-coder/Machine-learning-for-Ai-ML-Engineering)

> A hands-on collection of Machine Learning concepts, data preprocessing, feature engineering, model building, evaluation, and practical projects focused on AI/ML Engineering.

---

## 🌳 Full Directory Tree

```
Machine-learning-for-Ai-ML-Engineering-main/
├── 01_Python/
│   └── 01_Tensors.ipynb
├── 02_project/
│   ├── 01_end_to_end_toy_project.ipynb
│   ├── model.pkl
│   └── placement.csv
├── 03_DataUnderstanding/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_EDA_Univriate.ipynb
│   ├── 03_EDA_Bivariate.ipynb
│   ├── 04_pandas_profiling.ipynb
│   ├── Output.html
│   └── train.csv
├── 04_Feature Engineering/
│   ├── Column_Transformer/
│   │   ├── Column_transformation.ipynb
│   │   └── covid_toy.csv
│   ├── Encoding Categorical Data/
│   │   ├── 01_Ordinal_Encoding.ipynb
│   │   ├── 02_OHE.ipynb
│   │   ├── cars.csv
│   │   └── customer.csv
│   ├── Encoding_Numerical/
│   │   ├── 01_Bining.ipynb
│   │   ├── 02_Binarization.ipynb
│   │   └── train.csv
│   ├── Feature Scaling/
│   │   ├── 01_Standarization.ipynb
│   │   ├── 02_Normaliation.ipynb
│   │   ├── Social_Network_Ads.csv
│   │   └── wine_data.csv
│   ├── Handling Mixed Data/
│   │   ├── Handling_Date_Time/
│   │   │   ├── 01_Work_with_date_time.ipynb
│   │   │   ├── messages.csv
│   │   │   └── orders.csv
│   │   ├── 01_Work_with_mixed_data.ipynb
│   │   └── titanic.csv
│   ├── Handling_missing_values/
│   │   ├── 01_Complete_case_analysis.ipynb
│   │   ├── 02_handling_num_missing_val.ipynb
│   │   ├── 03_Arbitrary_value_imputation.ipynb
│   │   ├── 04_End-of-dist.ipynb
│   │   ├── 05_End_of_dist.ipynb
│   │   ├── data_science_job.csv
│   │   ├── skewed_missing_dataset.csv
│   │   ├── titanic_toy.csv
│   │   └── train.csv
│   ├── Mathematical Transformation/
│   │   ├── 01_Function_trans.ipynb
│   │   ├── 02_Power_Transformers.ipynb
│   │   ├── concrete_data.csv
│   │   └── train.csv
│   ├── Proj-without_pipeline/
│   │   ├── models/
│   │   │   ├── Clf.pkl
│   │   │   ├── ohe_Embarked.pkl
│   │   │   ├── ohe_sex.pkl
│   │   │   ├── si_age.pkl
│   │   │   └── si_Embarked.pkl
│   │   ├── 01_Ml_Pro.ipynb
│   │   ├── 01_predict.ipynb
│   │   └── train.csv
│   └── sklearn-Pipelne/
│       ├── 01_Sklearn_Pipeline.ipynb
│       ├── 02_pipeline_prediction.ipynb
│       ├── pipe.pkl
│       └── train.csv
├── 0_3_Data Gathering/
│   ├── 01_Work_With_CSV.ipynb
│   ├── 02_Work_With_Json_&_SQL.ipynb
│   ├── 03_Work_with_API.ipynb
│   ├── 04_Work_With_Web_scrapping.ipynb
│   ├── Books Inventory Dataset.csv
│   ├── Books.html
│   ├── file.tsv
│   ├── ipl-matches.csv
│   ├── placement.csv
│   ├── students_bad.csv
│   ├── Test.csv
│   ├── train.json
│   └── world.sql
└── README.md
```

---

## 📂 Folder-by-Folder Breakdown

### `01_Python/`
Intro Python/tensor fundamentals used as a warm-up before the ML content.
- `01_Tensors.ipynb` — working with tensors.

### `02_project/`
A first end-to-end toy ML project (placement prediction).
- `01_end_to_end_toy_project.ipynb` — full pipeline walkthrough.
- `model.pkl` — trained/pickled model artifact.
- `placement.csv` — dataset used for the project.

### `03_DataUnderstanding/`
Exploratory Data Analysis (EDA) notebooks.
- `01_Data_Understanding.ipynb` — initial data understanding.
- `02_EDA_Univriate.ipynb` — univariate analysis.
- `03_EDA_Bivariate.ipynb` — bivariate analysis.
- `04_pandas_profiling.ipynb` — automated profiling report generation.
- `Output.html` — exported profiling report.
- `train.csv` — dataset used across the EDA notebooks.

### `04_Feature Engineering/`
The largest section — covers the full feature engineering toolkit, broken into sub-topics:

| Subfolder | Focus |
|---|---|
| `Column_Transformer/` | Using `ColumnTransformer` to apply different preprocessing to different columns. |
| `Encoding Categorical Data/` | Ordinal encoding & One-Hot Encoding (OHE). |
| `Encoding_Numerical/` | Binning and binarization of numeric features. |
| `Feature Scaling/` | Standardization and normalization techniques. |
| `Handling Mixed Data/` | Mixed-type columns, including a nested `Handling_Date_Time/` subfolder for date/time feature extraction. |
| `Handling_missing_values/` | Complete-case analysis, numerical imputation, arbitrary-value imputation, and end-of-distribution imputation. |
| `Mathematical Transformation/` | Function transformers and power transforms. |
| `Proj-without_pipeline/` | A manual (non-pipeline) preprocessing project, with a `models/` folder storing individual pickled encoders/imputers/classifier. |
| `sklearn-Pipelne/` | Rebuilding the same workflow using `sklearn.pipeline.Pipeline`, with predictions via a saved pipeline (`pipe.pkl`). |

### `0_3_Data Gathering/`
Notebooks on collecting data from various sources.
- `01_Work_With_CSV.ipynb` — reading/writing CSV files.
- `02_Work_With_Json_&_SQL.ipynb` — working with JSON and SQL data.
- `03_Work_with_API.ipynb` — pulling data from APIs.
- `04_Work_With_Web_scrapping.ipynb` — web scraping basics.
- Supporting datasets: `Books Inventory Dataset.csv`, `Books.html`, `file.tsv`, `ipl-matches.csv`, `placement.csv`, `students_bad.csv`, `Test.csv`, `train.json`, `world.sql`.

