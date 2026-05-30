# 🏠 House Price Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts California house prices using Linear Regression.

## 📁 Recommended Folder Structure for Submission

```
House_Price_Prediction/
│
├── House_Price_Prediction.ipynb    # Main Jupyter Notebook (code + analysis)
├── linear_regression_model.pkl     # Saved trained model (generated after running)
│
├── Report.md                       # Project report (2-4 pages)
├── Presentation_Outline.md         # PowerPoint presentation outline
├── README.md                       # This file
├── requirements.txt                # Python dependencies
│
├── images/                         # Generated visualizations (after running notebook)
│   ├── correlation_heatmap.png
│   ├── price_distribution.png
│   ├── income_vs_price.png
│   ├── feature_distributions.png
│   ├── actual_vs_predicted.png
│   └── residuals_distribution.png
│
└── presentation/                   # (Optional) Your final PowerPoint file
    └── House_Price_Prediction.pptx
```

> **Note:** The `images/` folder and `linear_regression_model.pkl` will be generated automatically when you run the notebook. The plots are saved in the same directory as the notebook by default — you can move them to `images/` for organization.

## 🚀 How to Run

### Prerequisites
Make sure you have Python 3.7+ installed. Then install the required libraries:

```bash
pip install -r requirements.txt
```

### Running the Notebook
1. Open a terminal in this folder.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `House_Price_Prediction.ipynb`.
4. Run all cells sequentially (Cell → Run All).

## 📊 Dataset
- **Name:** California Housing Dataset
- **Source:** scikit-learn (`sklearn.datasets.fetch_california_housing`)
- **Samples:** 20,640
- **Features:** 8 numerical features
- **Target:** Median House Value (in $100,000s)

## 🧠 Model
- **Algorithm:** Linear Regression
- **Train/Test Split:** 80/20
- **R² Score:** ~0.60

## 📦 Technologies Used
- Python 3.x
- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- pickle

## 👤 Author
- **Name:** Vanshika Dongre
- **Course:** B.Tech CSE
- **Year:** 2nd Year

---
*Created as part of the Machine Learning course project.*
