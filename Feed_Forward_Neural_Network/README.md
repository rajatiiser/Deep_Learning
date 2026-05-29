# Website Phishing Detection using Feedforward Neural Network (FNN)

## 📌 Project Overview
This project implements a Feedforward Neural Network (FNN) for multiclass classification of websites as phishing, legitimate, or suspicious.

The model is trained using the Website Phishing dataset from the UCI Machine Learning Repository (Dataset ID: 379). Different optimization techniques and hyperparameters are tested to improve model performance.

---

## 📂 Dataset Information

- Dataset: Website Phishing Dataset
- Source: UCI Machine Learning Repository
- Dataset ID: 379
- Total Samples: 1353

### Class Distribution
- Phishing Websites → 702
- Legitimate Websites → 548
- Suspicious Websites → 103

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Model Architecture

The project uses a Feedforward Neural Network (FNN) with:

- Dense layers using ReLU activation
- Dropout layers for regularization
- Softmax output layer for multiclass classification

### Final Model Configuration
- Optimizer: RMSprop
- Neurons: 128
- Dropout Rate: 0.2
- Loss Function: Sparse Categorical Crossentropy

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Label Encoding (`-1, 0, 1 → 0, 1, 2`)
- Feature Scaling using `StandardScaler`
- Train-Test Split (80:20)

---

## 🔍 Hyperparameter Tuning

Different experiments were performed to improve the model.

### Optimizers Tested
- SGD
- Adam
- RMSprop

### Hyperparameters Tuned
- Number of Neurons
- Dropout Rate

### Cross Validation
5-Fold Cross Validation was used to evaluate model stability.

---

## 📊 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Learning Curves

---

## 📈 Results

### Initial Model Accuracy
- ~84%

### Final Tuned Model Accuracy
- ~87%

### Cross Validation Accuracy
- 0.8589

The final tuned model showed improved and stable performance across different data splits.

---

## 📉 Visualizations Included

- Class Distribution
- Loss Curves
- Accuracy Curves
- Confusion Matrix
- ROC Curve
- Hyperparameter Comparison Plots

---

## 🚀 How to Run the Project


### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

Open the Jupyter Notebook or Google Colab notebook and run all cells.

---

## 📚 Learning Outcomes

This project helped in understanding:

- Feedforward Neural Networks
- Multiclass Classification
- Hyperparameter Tuning
- Optimization Techniques
- Regularization
- Cross Validation
- Model Evaluation and Visualization

---

## 📌 Conclusion

This project demonstrates how Feedforward Neural Networks can be applied to phishing website detection. By tuning hyperparameters and comparing optimization techniques, the final model achieved improved performance and stable generalization on unseen data.

---

## 👨‍💻 Author

Rajat Kumar
