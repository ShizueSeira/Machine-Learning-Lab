<div align="center">

# Machine Learning Portfolio

A collection of machine learning projects covering regression analysis, CNN image classification, RNN time-series forecasting, dimensionality reduction, and neural networks.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

</div>

---

## 📁 Summative Projects

### 1. Boston House Price Prediction
> **📊 Regression Analysis | 🏠 Real Estate**
> 
> Predicting median house prices in Boston using various regression techniques.

- **Models**: Simple Linear, Ridge, Lasso, Elastic Net Regression
- **Key Features**: RM, LSTAT, DIS, AGE, PTRATIO
- **Best Model**: Simple Linear Regression (R²: 0.80, RMSE: 2.25)
- **Insights**: Number of rooms (RM) strongly increases prices, while lower-status population (LSTAT) decreases them

**Files**: 
- 💻 **Code:** [Boston_House_Price_Prediction.ipynb](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Boston_House_Price_Prediction.ipynb)
- 📄 **Report:** [Inventado-Boston_House_Price_Report.pdf](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Inventado-Boston_House_Price_Report.pdf)

---

### 2. Hair Type Classification with CNN
> **🖼️ Image Classification | 💇 Hair Types**
> 
> Multi-class classification of hair types (Curly, Straight, Wavy) using Convolutional Neural Networks.

- **Models**: Custom CNN architectures built from scratch
- **Dataset**: 985 images across 3 classes
- **Best Model**: 4 Conv layers, 128 neurons, learning rate 1e-4
- **Results**: 88% training accuracy, 61% validation accuracy, 0.81 ROC-AUC

**Files**:
- 💻 **Code:** [SummativeLabExercise.ipynb](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/SummativeLabExercise.ipynb)
- 📄 **Report:** [Inventado_Valles_Summative-Lab-Exercise_Identifying_Hair_Types.pdf](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Inventado_Valles_Summative-Lab-Exercise_Identifying_Hair_Types.pdf)

---

### 3. Stock Price Prediction with RNN
> **📈 Time Series Forecasting | 💹 Finance**
> 
> Predicting Amazon and IBM stock prices using Recurrent Neural Networks.

- **Models**: LSTM, GRU, Bi-RNN architectures
- **Data**: 2006–2018 stock price history
- **Best Model**: GRU with 50/20 units, Adam optimizer, rolling averages
- **Results**: R² > 0.98, RMSE: 13.80 (AMZN), 1.68 (IBM)

**Files**:
- 💻 **Code:** [Summative Lab Exercise 4_Predicting Stock Prices.ipynb](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Summative%20Lab%20Exercise%204_Predicting%20Stock%20Prices.ipynb)
- 📄 **Report:** [Inventado_Valles_Summative-Lab-Exercise-Predictin-Stock-Prices.pdf](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Inventado_Valles_Summative-Lab-Exercise-Predictin-Stock-Prices.pdf)
- 📊 **Datasets**:
  - [AMZN_2006-01-01_to_2018-01-01.csv](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/AMZN_2006-01-01_to_2018-01-01.csv)
  - [IBM_2006-01-01_to_2018-01-01.csv](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/IBM_2006-01-01_to_2018-01-01.csv)

---

## 🧪 Formative Lab Exercises

### Formative Lab Exercise #2: Linear Regression & Logistic Regression
> **📉 Supervised Learning | 📊 Regression & Classification**

- **Linear Regression Task**: Predicting student performance metrics.
- **Logistic Regression Task**: Diagnostic classification of breast cancer tissue samples.
- **Files**:
  - 💻 **Code:** [Inventado_Formative Lab Exercise 2 HandsOn Linear Regression and Logistic Regression.ipynb](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Inventado_Formative%20Lab%20Exercise%202%20HandsOn%20Linear%20Regression%20and%20Logistic%20Regression.ipynb)
  - 📊 **Linear Regression Dataset:** [CSE_student_performances.csv](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/CSE_student_performances.csv)
  - 📊 **Logistic Regression Dataset:** [breast_cancer_cleaned.csv](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/breast_cancer_cleaned.csv)

---

### Formative Lab Exercise #4: Multilayer Perceptron (MLP)
> **🧠 Deep Learning | 💰 Income Classification**

- **Description**: Construction and training of a Multilayer Perceptron neural network to classify individual income levels based on census attributes.
- **Files**:
  - 💻 **Code:** [Inventado_FormativeLab4.ipynb](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Inventado_FormativeLab4.ipynb)
  - 📊 **Dataset:** [UCI Adult Income Dataset (`adult.data`)](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data)

---

### Formative Lab Exercise #5: Principal Component Analysis (PCA)
> **📐 Unsupervised Learning | 🖼️ Dimensionality Reduction**

- **Description**: Demonstrates Principal Component Analysis (PCA) for dimensionality reduction using the Fashion-MNIST dataset. The 28×28 pixel images are flattened into 784-dimensional feature vectors and normalized to zero mean and unit variance. PCA is applied across varying component sizes (n = 100, 50, 10) to reconstruct images, and Mean Squared Error (MSE) is evaluated to measure information loss.
- **Files**:
  - 💻 **Code:** [Inventado_FormativeLab5.ipynb](https://github.com/ShizueSeira/Machine-Learning-Lab/blob/main/Inventado_FormativeLab5.ipynb)
  - 📊 **Dataset:** Built-in `tensorflow.keras.datasets.fashion_mnist`

---

## 🛠️ Technologies Used

- **Python** with Jupyter Notebooks
- **Machine Learning**: Scikit-learn, TensorFlow/Keras
- **Data Analysis**: Pandas, NumPy, Matplotlib, Seaborn
- **Specialized Models**: CNNs, RNNs (LSTM/GRU), Multilayer Perceptron, PCA, Linear/Logistic Regression

---

## 📊 Key Skills Demonstrated

- Data preprocessing, normalization, and feature engineering
- Dimensionality reduction and variance analysis with PCA
- Hyperparameter tuning and deep learning optimization
- Supervised learning with regression analysis and binary/multiclass classification
- CNN architecture design for computer vision applications
- Time-series modeling using Recurrent Neural Networks (LSTM/GRU)
- Comprehensive evaluation metrics interpretation (R², RMSE, ROC-AUC, Reconstruction MSE)

---

## 👥 Authors

<div align="center">

**Charles Fredric G. Inventado** & **James Vincent V. Valles (For Lab 3 and Lab 4)**  
*University of Santo Tomas - College of Information and Computing Sciences*

</div>
