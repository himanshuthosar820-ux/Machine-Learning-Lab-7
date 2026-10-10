# Machine Learning Lab 7 — Raisin Classification

## Student Details

- **Name:** Daksh Khandelwal
- **Class:** B-B3
- **Roll Number:** 45

## Project Overview

This lab uses the Raisin dataset to explore the data and build a **Gaussian Naive Bayes classification model**. The notebook performs basic data inspection, encodes the target class, splits the data into training and testing sets, trains the model, and evaluates its predictions.

## Dataset

The dataset contains 900 records and 8 columns describing raisin characteristics.

Features include:

- `Area`
- `MajorAxisLength`
- `MinorAxisLength`
- `Eccentricity`
- `ConvexArea`
- `Extent`
- `Perimeter`

The target column is `Class`, which contains raisin categories such as `Kecimen` and `Besni`.

**Dataset file:** `Raisin_Dataset.csv`

## Files in This Repository

- `Ml_lab7.ipynb` — Jupyter Notebook containing the data analysis and classification workflow.
- `Raisin_Dataset.csv` — Dataset used for the experiment.
- `README.md` — Project information and instructions.

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Steps Performed

1. Load and inspect the dataset.
2. Check the dataset's structure, summary statistics, data types, duplicate records, and missing values.
3. Encode the target class using `LabelEncoder`.
4. Split the data into training and testing sets using an 80:20 ratio.
5. Train a `GaussianNB` model.
6. Generate predictions on the test data.
7. Evaluate the model using accuracy, precision, recall, F1-score, a classification report, and a confusion matrix.
8. Compare training and testing accuracy.

## How to Run

1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter
   ```

3. Open `Ml_lab7.ipynb` in Jupyter Notebook or VS Code.
4. Make sure the dataset is in the same folder as the notebook.
5. Run the notebook cells in order.

### Dataset loading note

The uploaded dataset is a CSV file. If you save it as `Raisin_Dataset.csv`, load it in the notebook with:

```python
df = pd.read_csv("Raisin_Dataset.csv")
```

If you instead use an Excel `.xlsx` dataset, use `pd.read_excel(...)` and keep the filename consistent with the file in the repository.

## Author

**Daksh Khandelwal**  
Class: B-B3 | Roll No.: 45
