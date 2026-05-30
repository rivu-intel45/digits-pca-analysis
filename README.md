# PCA Calculation on Digits Dataset

An interactive Jupyter Notebook project that applies **Principal Component Analysis (PCA)** on a handwritten digits dataset to reduce dimensionality and visualize high-dimensional pixel data.

---

## Project Overview

This project walks through a basic PCA workflow:

- Loading and exploring the digits dataset
- Separating pixel features from the target digit labels
- Visualizing a single digit image using Matplotlib and Seaborn
- Standardizing pixel values using `StandardScaler`
- Applying PCA for dimensionality reduction
- Visualizing digit clusters in 2D and 3D PCA space
- Understanding explained variance from principal components

---

## Dataset

The project uses a CSV file named:

```text
digits.csv
```
The dataset contains handwritten digit image data where:

- Each row represents one digit image
- Pixel columns represent the intensity values of the image
-`number_label` represents the actual digit class
```text

PCA-Calculation/
├── PCA calculation.ipynb
├── data/
│   └── digits.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Key Concepts Covered

- Principal Component Analysis
- Dimensionality Reduction
- Data Standardization
- Feature Scaling
- 2D Data Visualization
- 3D Data Visualization
- Explained Variance Ratio

---

## Installation

Clone the repository:
```text
git clone https://github.com/your-username/PCA-Calculation.git
cd PCA-Calculation
```

Install the required libraries:
```text
pip install -r requirements.txt
```

## How to Run
Open the notebook:
```text
jupyter notebook "PCA calculation.ipynb"
```
Then run all cells from top to bottom.

## Output Visualizations

The notebook generates:

- A grayscale image visualization of a handwritten digit
- A heatmap of pixel intensity values
- A 2D PCA scatter plot
- A colored 2D PCA scatter plot by digit label
- A 3D PCA scatter plot of digit clusters

## Project Workflow
```text
Load Dataset
     ↓
Separate Features and Labels
     ↓
Visualize Sample Digit
     ↓
Standardize Pixel Values
     ↓
Apply PCA
     ↓
Analyze Explained Variance
     ↓
Visualize PCA Components
```

## Requirements
```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```
## Author

**Protyay Saha**

- GitHub: [rivu-intel45](https://github.com/rivu-intel45)
- LinkedIn: [Protyay Saha](https://www.linkedin.com/in/protyay-saha-12a892333)
