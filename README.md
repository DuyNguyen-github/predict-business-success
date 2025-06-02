# 📊 Business Success Prediction Using Machine Learning, Deep Learning, and Ensemble Methods

**Business Success Prediction Using Machine Learning, Deep Learning, and Ensemble Methods Based on Investor–Business–Market Insights**

---

### 🎯 Introduction
- **Goal**: Build a predictive model to estimate the success probability of businesses (IPO, M&A, or Closed) by leveraging the relationships among investors, businesses, and the market.

---

### 📊 Data
- **Source**: Crunchbase.
- **Scale**: Over 24,000 samples, more than 560 features.
- **Main Features**:  
  - Investor information (total investment, success rate)  
  - Business attributes (company age, industry)  
  - Market trends (sector dynamics, funding frequency)
- **Labels**:  
  - Success (`1`): if IPO or M&A  
  - Failure (`0`): if Closed

---

### 🧠 Models and Methods
- **Traditional Machine Learning**: Decision Tree, Random Forest, KNN, XGBoost, AdaBoost.
- **Deep Learning**: Neural Networks with 2 and 6 hidden layers.
- **Ensemble Learning**: Stacking combining the above models.
- **Supporting Techniques**: Dropout, Batch Normalization, L2 Regularization, Early Stopping, ReduceLROnPlateau, ModelCheckpoint.

---

### 📈 Results
- **Top Performance**: Tree-based models like Random Forest, XGBoost, and Stacking (Decision Tree – Random Forest – XGBoost) achieved AUC 0.98–0.99.
- **DNN Comparison**: Neural networks with 2 hidden layers outperformed 6 hidden layers.
- **Importance of Preprocessing**: Data cleaning and feature engineering played a key role in improving model performance.

---

### 🗂️ Repository Structure
- `data/`: Contains dataset files.
- `preprocessing_data.ipynb`: Data preprocessing and feature creation.
- `train_deep_neural_network.ipynb`: Train deep neural networks.
- `train_machine_learning.ipynb`: Train traditional machine learning models.
- `train_machine_learning_cross_validation.ipynb`: Train ML models with cross-validation.
- `train_stacking_DNN_XGB_LR.ipynb`: Stacking DNN, XGBoost, Logistic Regression.
- `train_stacking_DT_RF_XGB.ipynb`: Stacking Decision Tree, Random Forest, XGBoost.

---

### 🔗 Links
- **Repository**: [https://github.com/DuyNguyen-github/predict-business-success](https://github.com/DuyNguyen-github/predict-business-success)
